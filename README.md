# lorislab-lib-parent

![License](https://img.shields.io/github/license/lorislab/lorislab-lib-parent)
![Maven Central](https://img.shields.io/maven-central/v/org.lorislab.lib/lorislab-lib-parent?label=maven%20central)
![GitHub Release](https://img.shields.io/github/v/release/lorislab/lorislab-lib-parent)


A parent POM that centralizes common configuration, dependency management, plugin configuration, and release settings for the lorislab set of libraries.

### Key points
- Centralized dependency management for lorislab modules
- Shared plugin and build configuration (compiler, formatter, test, release)
- Simplifies module POMs by inheriting common defaults

### Requirements
- Java 25+ (or your project's required Java version)
- Apache Maven 3.9+

### Usage
Add this project as the parent in your module's `pom.xml`:

```
<parent>
	<groupId>org.lorislab.lib</groupId>
	<artifactId>lorislab-lib-parent</artifactId>
	<version>VERSION</version>
</parent>
```

### License

This project is licensed under the terms in the `Apache 2.0` file. See the [LICENSE](LICENSE) at the repository root for details.

### Contributing

Contributions are welcome — please open issues or pull requests against the repository. Follow the existing code style and run tests locally before submitting a PR.

### Contact / Maintainers
See repository metadata or check the project website for contact information.
