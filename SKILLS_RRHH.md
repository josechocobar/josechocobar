# Skills que piden RRHH (extraído de ofertas reales)

Fuentes analizadas (LinkedIn, Argentina, 2026):
- PedidosYa — Software Engineer Android
- Tata Consultancy Services — QA Automation/Appium
- Stefanini LATAM — QA Mobile Automation JR/SSR

## Android Developer (nivel mid/senior)
**Hard skills**
- Kotlin sólido + Android SDK + ciclo de vida de la app.
- Apps modularizadas y escalables.
- Clean Architecture + patrones (MVVM / MVI).
- Jetpack Compose **y** Views tradicionales (XML).
- Concurrencia: Coroutines + Flow.
- DI: Hilt (o Dagger 2 / Koin).
- REST: Retrofit + OkHttp; serialización Gson/Moshi/Kotlin Serialization.
- Testing: JUnit + Mockk (unit), Espresso + Compose Tests (UI).

**Soft / proceso**
- Git, trabajo en equipo, definición de tareas, escalabilidad/flexibilidad.
- Integración con servicios internos/externos.

## SDET / QA Automation Mobile (nivel JR/SSR/Senior)
**Hard skills**
- Testing mobile en emuladores y dispositivos físicos (BrowserStack o similares).
- Appium + Python (librería BrowserStack) y/o Playwright.
- Conceptos: pruebas funcionales, integración, regresión.
- Pruebas automatizadas E2E, reportes, CI/CD.
- (Senior) arquitectura POM, framework propio, TypeScript/Java.

**Valorado**
- Experiencia en banca / fintech / inversiones.
- Equipos ágiles, CI/CD, buenas prácticas de automatización.

## Comparación con tu perfil actual
| Skill pedida | Tu evidencia actual | Gap |
|---|---|---|
| Kotlin sólido | ✅ Apps Android 2018‑2021 | — |
| Android SDK / ciclo de vida | ✅ | — |
| MVVM | ✅ | — |
| Clean Architecture | ⚠️ No documentado | Medio |
| Jetpack Compose | ❌ No hay evidencia | Alto |
| Coroutines / Flow | ✅ CV | — |
| Hilt | ❌ (usás Koin) | Medio (Koin válido, sumar Hilt) |
| Retrofit/OkHttp/serialización | ✅ Apps | — |
| Room/SQLite | ✅ | — |
| Unit/UI testing (JUnit/Mockk/Espresso/Compose) | ❌ Sin tests en repos | Alto |
| Modularización | ❌ | Alto |
| Appium | ✅ respuestasRapidasAppium | — |
| WebDriverIO / TypeScript strict | ✅ | — |
| POM + SDD | ✅ | — |
| Playwright | ❌ | Alto (pedido en jobs) |
| Python | ❌ | Alto (pedido en jobs) |
| BrowserStack | ❌ | Medio |
| CI/CD (GitHub Actions) | ❌ | Alto |
| Spring Boot backend | ✅ nickyapi | — |
| Docker / Linux | ✅ CV | — |
| Banca/fintech | ❌ | Opcional |

## Acciones prioritarias
1. Agregar Jetpack Compose + Hilt a una app Android existente (MyMovieApp o NickyApp).
2. Agregar tests (JUnit/Mockk + Espresso/Compose) y CI (GitHub Actions) a al menos 1 app.
3. Crear un repo Playwright (web E2E) y/o agregar Python+Appium a respuestasRapidasAppium.
4. Integrar BrowserStack en la suite mobile.
5. Documentar arquitectura (Clean Arch) en READMEs.