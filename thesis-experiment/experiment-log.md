# AI-Assisted Software Maintainability Experiment

## Repository

Repository: redis-replicator

Original repository:
https://github.com/leonchen83/redis-replicator

## Baseline

Baseline commit:

433f268e04121a4c43dd565642d7bb7e536829af

The baseline was established before any AI-assisted code modification.

## Build Validation

Command:

mvn clean package -DskipTests -P CI

Result:

BUILD SUCCESS

## Test Environment

The repository requires Redis services for integration testing.

Local test environment:

- Redis 6 on port 6379
- Redis 6 on port 6380
- Password authentication configured for the second Redis instance
- Docker used to run Redis

The original CI used Redis 3.2.3 for one instance. This image caused compatibility problems on the Apple Silicon development machine, so Redis 6 was used consistently for the pilot experiment.

## Baseline Tests

Tests run: 188

Failures: 0

Errors: 0

Skipped: 3

Result:

BUILD SUCCESS

## Codebase Size

Production source analysed:

src/main/java

Results:

- Java files: 391
- Production Java LOC: 20,177
- Comment lines: 8,975
- Blank lines: 4,534

## Baseline Cleanup

A dump.rdb file generated during Redis testing was removed because it was not part of the original repository.

## Current Experimental Stage

The functional baseline has been established.

Next step:

Run maintainability analysis and establish M0.