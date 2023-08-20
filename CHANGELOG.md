<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# Virtus Changelog

## [Unreleased]

## [1.4.0] - 2023-08-20

### Changed
- IntelliJ Platform versions - upgrade `231.*` to `232.*`
- Dependencies - upgrade `org.jetbrains.intellij` to `1.15.0`

## [1.3.0] - 2023-04-18

### Added
- Temporary workaround for Kotlin Compiler `OutOfMemoryError` -> https://jb.gg/intellij-platform-kotlin-oom
- Gradle version catalog integration
- Gradle Kotlin DSL Lazy Property Assignment
- Enable Gradle Build Cache

### Changed
- Dependencies - upgrade `org.jetbrains.intellij` to `1.13.3`
- Dependencies - upgrade `org.jetbrains.kotlin.jvm` to `1.8.20`
- Upgrade Gradle Wrapper to `8.1`
- Remove `UnusedProperty` suppression in `gradle.properties` file
- Rename `org.gradle.unsafe.configuration-cache` to `org.gradle.configuration-cache` in `gradle.properties`

## [1.2.0] - 2023-02-13

### Added support for
- Java, Scala, C/C++, CMake, Kotlin, GraphQL, Groovy, Ini, MakeFile, Postcss, Proto, Regex, Rust and more

### Changed
- Completion match foreground to accent
- Documentation and Code Completion background to secondary

## [1.1.0] - 2023-02-07

### Added
- Support for HTML, SCSS, shell, Yaml, Toml, XML, Markdown, Dockerfile

## [1.0.0] - 2022-2-3

### Added
- Support for Python, R, Go, TypeScript, SQL, JavaScript, CSS

### Changed
- UI colors for better contrast

[Unreleased]: https://github.com/vineetver/Virtus/compare/v1.4.0...HEAD
[1.4.0]: https://github.com/vineetver/Virtus/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/vineetver/Virtus/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/vineetver/Virtus/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/vineetver/Virtus/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/vineetver/Virtus/commits/v1.0.0
