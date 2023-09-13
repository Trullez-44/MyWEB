## ****¿Qué es un archivo readme?****

Los archivos readme (readme.md), suelen contener información importante sobre el proyecto o software al que se refieren. Para que los usuarios puedan encontrar fácilmente el archivo de un vistazo, se recomienda ubicarlo en el nivel superior del directorio.

El archivo *readme* cumple diferentes funciones según el tipo de usuario:

- **Para los usuarios finales**, estos archivos aclaran posibles dudas relacionadas con la instalación, actualización o uso de un *software*.
- Un *readme* ofrece múltiples ventajas en **tu proceso de desarrollo personal**. Por un lado, antes de comenzar con el desarrollo en sí, puede servir como guía para ejecutar el proyecto. Por otro lado, también ayuda a ponerse al día si un proyecto se queda en pausa durante un largo período.
- **Para otros desarrolladores**, los archivos *readme* explican el código y proporcionan información crucial sobre su desarrollo futuro o cómo utilizar sistemas, software o proyectos de código abierto.

# Conventional-Commits & Types-of-Commits

# Conventional Commits

---

The commit contains the following structural elements, to communicate intent to the consumers of your library:

1. **fix:** a commit of the *type* `fix` patches a bug in your codebase (this correlates with **`[PATCH](http://semver.org/#summary)`** in Semantic Versioning).
2. **feat:** a commit of the *type* `feat` introduces a new feature to the codebase (this correlates with **`[MINOR](http://semver.org/#summary)`** in Semantic Versioning).
3. **BREAKING CHANGE:** a commit that has a footer `BREAKING CHANGE:`, or appends a `!` after the type/scope, introduces a breaking API change (correlating with **`[MAJOR](http://semver.org/#summary)`** in Semantic Versioning). A BREAKING CHANGE can be part of commits of any *type*.
4. *types* other than `fix:` and `feat:` are allowed, for example **[@commitlint/config-conventional](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional)** (based on the **[Angular convention](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines)**) recommends `build:`, `chore:`, `ci:`, `docs:`, `style:`, `refactor:`, `perf:`, `test:`, and others.
5. *footers* other than `BREAKING CHANGE: <description>` may be provided and follow a convention similar to **[git trailer format](https://git-scm.com/docs/git-interpret-trailers)**.

---

# Type of Commits

Must be one of the following:

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **test**: Adding missing tests or correcting existing tests
- chore: **Changes to the build process or auxiliary tools and libraries such as documentation generation**.    