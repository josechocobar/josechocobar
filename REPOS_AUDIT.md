# Auditoría de repositorios públicos — josechocobar

Objetivo: perfil competitivo para **Android Developer / SDET / QA Automation**.

## ✅ MANTENER PÚBLICOS (estrella)
| Repo | Motivo |
|---|---|
| respuestasRapidasAppium | SDET showcase: Appium 2 + WDIO + TS strict, POM, SDD, ESLint/Prettier. |
| NickyApp | Android real (restaurantes), MVVM, Room, Retrofit. |
| nickyapi | Backend Spring Boot para NickyApp (fullstack). |
| MyMovieApp | Android movies, Room, Retrofit. |
| DatosConQr | Android, Room, QR. |
| android-kotlin-login-facebook | Android auth (Facebook SDK). |

## 🔒 YA PRIVADOS (ejecutado)
aviso-legal, BirdNFT, editorDeStl, tera, vendimia-habita, korge-hello-world-master,
SimpleNotepad, TATETI, Rob, Constraints, Mercadolibre, MoviesTrivia, ScreenRecorderPlusX,
ChocoCity, appTragos, reactiveKotlin, springsecurity-login, NickyApp, nickyapi,
MyMovieApp, DatosConQr, android-kotlin-login-facebook.

## 📦 FORKS PÚBLICOS ARCHIVADOS (no se pueden privatizar; quedan archivados)
ScreenStream, android-kotlin-loginfacebook, compose-jb. (GitHub no permite privatizar forks públicos.)

## 🛠️ ACTUALIZAR (agregar README + arquitectura + tests)
Aplicar a los 6 repos estrella (MyMovieApp, NickyApp, nickyapi, DatosConQr,
android-kotlin-login-facebook, respuestasRapidasAppium).

## 🛠️ ACTUALIZAR (agregar README + arquitectura + tests)
Aplicar a: MyMovieApp, NickyApp, nickyapi, DatosConQr, android-kotlin-login-facebook,
ChocoCity, appTragos, ScreenRecorderPlusX, reactiveKotlin, springsecurity-login,
MoviesTrivia, Mercadolibre, Rob, TATETI, Constraints.

Mínimo por repo:
- README con descripción, tech stack, cómo correr, screenshots.
- Arquitectura (MVVM/Clean) documentada.
- Eliminar binarios (.apk, .jar, .mp4, .webm, .pdf) del tracking (git rm --cached + .gitignore).
- Agregar tests + GitHub Actions (al menos en 2-3 repos estrella).

## 🧹 LIMPIEZA DEL REPO PERFIL (josechocobar)
- Eliminar Screen_recording_20261019_202248.webm (20 MB) → subir a YouTube/Drive y linkear.
- Mover cv_jose_chocobar.pdf a Drive/LinkedIn y linkear (o mantener en releases).
- Actualizar README (hecho en este commit).
- Agregar .gitignore para binarios.

## Comandos útiles
```bash
# Hacer un repo privado (requiere token)
curl -X PATCH -H "Authorization: token <TOKEN>" \
  https://api.github.com/repos/josechocobar/<REPO> \
  -d '{"private":true}'

# Quitar binarios del tracking sin borrarlos localmente
git rm --cached *.apk *.jar *.mp4 *.webm *.pdf
echo "*.apk" >> .gitignore
```