# Experiment Environment

## Machine

- Machine: Apple Silicon Mac
- OS: macOS 26.5.2
- Architecture: aarch64
- Locale: en_AU
- Platform encoding: UTF-8

## Java

`java -version`


openjdk version "21.0.12" 2026-07-21
OpenJDK Runtime Environment Homebrew (build 21.0.12)
OpenJDK 64-Bit Server VM Homebrew (build 21.0.12, mixed mode, sharing)

mvn -version
Apache Maven 3.9.16 (2bdd9fddda4b155ebf8000e807eb73fd829a51d5)
Maven home: /opt/homebrew/Cellar/maven/3.9.16/libexec
Java version: 26.0.2.1, vendor: Homebrew
Runtime: /opt/homebrew/Cellar/openjdk/26.0.2.1/libexec/openjdk.jdk/Contents/Home

git version 2.50.1 (Apple Git-155)

Docker version 29.7.2, build a7dcaa6

Repository Baseline
- Repository: redis-replicator
- Baseline commit: 433f268e04121a4c43dd565642d7bb7e536829af

## M0 – Baseline Maintainability

### Source-Code Baseline

Original source baseline commit:

433f268e04121a4c43dd565642d7bb7e536829af

This is the repository state used as the original M0 source-code
baseline before any AI-assisted maintenance changes.

### Experiment Documentation

Experiment documentation commit:

648c096a6623790f1027f538aaa0723b2afca4ee

Tag:

baseline-m0

The documentation commit contains experiment records only and does
not represent a change to the production Java source code.

### SonarQube M0 Results

Maintainability rating: A

Maintainability issues / code smells: 714

Duplicated code: 7.8%

Lines of Code: approximately 21k

Security rating: D
Security issues: 2

Reliability rating: E
Reliability issues: 100

Coverage: 0.0%

### Coverage Note

The 0.0% coverage value is not being treated as the actual test
coverage of the repository because a JaCoCo coverage report was not
provided to SonarQube during this analysis.

The repository test suite was validated separately:

- Tests run: 188
- Failures: 0
- Errors: 0
- Skipped: 3