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

## 🔒 PASAR A PRIVADO / ARCHIVAR (no aportan o son ruido)
| Repo | Motivo |
|---|---|
| ScreenStream | Fork de terceros. |
| android-kotlin-loginfacebook | Fork duplicado de tu propio android-kotlin-login-facebook. |
| compose-jb | Fork de JetBrains (102 MB). |
| aviso-legal | Solo aviso legal, no código. |
| BirdNFT | NFT/Web3, no relevante para Android/SDET. |
| editorDeStl | Python/3D, no relevante. |
| tera | Blockchain/NFT (Hardhat), no relevante. |
| vendimia-habita | Web (Next.js) vitivinícola, no relevante. |
| korge-hello-world-master | Template hello world, no aporta. |
| SimpleNotepad | Trivial, sin README. |
| TATETI | Juego simple, sin README. |
| Rob | Trivial, sin README. |
| Constraints | 604 MB (binarios), sin README. Archivar o limpiar. |
| Mercadolibre | Sin README, binarios (jar/mp4/log) 7 MB. Actualizar o privar. |
| MoviesTrivia | Con README pero incluye APK (11 MB). Limpiar binario. |
| ScreenRecorderPlusX | Sin README. |
| ChocoCity | Sin README. |
| appTragos | Sin README. |
| reactiveKotlin | Sin README. |
| springsecurity-login | Sin README (solo pom). |

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