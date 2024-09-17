## Kotlin Multiplatform (KMP): An Introduction
Slide link: https://ravikrs.github.io/kmp-demo/

![slides.png](img/slides.png)

GH repo link: https://github.com/ravikrs/KMPDemo

![ghrepo.png](img/ghrepo.png)

---

### What is Kotlin Multiplatform?
- Enabled development of cross platform project
- Allows sharing common code between different platforms.
![kotlin-multiplatform.svg](img/kmp.png)

---
## Supported Platforms
- **Mobile**: Android, iOS.
- **Web** (alpha): Kotlin/JS/WebAssembly.
- **Desktop**: macOS, Linux, Windows.
- **Server**: Kotlin/JVM/Ktor for server development.

---
### Why Use KMP?
- Separate codebases for Android, iOS, and other platforms.
- Duplicate effort for business logic and other core functionality.
- "Duplication my be the root of all evil in software" - Robert C. Martin

---
## Multiplatform Advantages:
- Code reusability.
- Reduced development effort.

---
## Code Sharing
![multiplatform-compose.svg](img/multiplatform-compose.svg)


### Shared Code:
- Business logic.
- Networking.
- Data persistence.


### Platform-Specific Code:
- UI interactions.
- Native platform APIs (camera, GPS, etc.).


### No Code sharing
![no-sharing.png](img/no-sharing.png)


### Sharing Domain
![domain-sharing.png](img/domain-sharing.png)


### Sharing Domain and Data
![domain-data-sharing.png](img/domain-data-sharing.png)


### Sharing Domain, Data and Presentation
![domain-data-presentation-sharing.png](img/domain-data-presentation-sharing.png)


### Expect/Actual Mechanism:
- `expect` keyword declares platform-agnostic APIs.
- `actual` keyword provides platform-specific implementations.
  ![expect-actual.png](img/expect-actual.png)

---

### KMP Libraries:
- Rich set of KMP libs: [KMP Awesome](https://github.com/terrakok/kmp-awesome) lists all KMP libs
- e.g. **Ktor** for networking., **SQLDelight** for cross-platform database access, etc

---

## Usage in the industry
- Netflix, 9GAG, Meetup, etc
- [Few companies using KMP](https://www.jetbrains.com/help/kotlin-multiplatform-dev/case-studies.html)
---

### Summary:
- Kotlin Multiplatform provides a flexible approach to cross-platform development
- Focus is on business logic sharing.

---
## Workshop
### Built a hello world KMP app for iOS, Android, Desktop and Web
![demo-hello-world-with-vw-logo.png](img/demo-hello-world-with-vw-logo.png)


### Sharing resources across multiple platforms
![demo-hello-world-with-graphics.png](img/demo-hello-world-with-graphics.png)


### Using KMP lib to develop shared logic/UI
![demo-kotlinx-datetime-lib.png](img/demo-kotlinx-datetime-lib.png)


### Shared domain/data/presentation/ui
![demo-weather-api.png](img/demo-weather-api.png)

---
## Thank you
### Links
- [Slides](https://ravikrs.github.io/kmp-demo/)
- [Demo App](https://github.com/ravikrs/KMPDemo)
- [KMP Wizard](https://kmp.jetbrains.com/)
- [KMP Awesome](https://github.com/terrakok/kmp-awesome)
- [Youtube KMP tutorial](https://www.youtube.com/watch?v=RSBO1C_Du2U&list=PLQkwcJG4YTCS55alEYv3J8CD4BXhqLUuk)
- [App With shared logic and UI](https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-multiplatform-create-first-app.html)
- [App With shared logic but native UI](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-create-first-app.html)
- [John O'Reilly Github Repositories](https://github.com/joreilly?tab=repositories)
- [KMP Docs](https://kotlinlang.org/docs/multiplatform.html)
