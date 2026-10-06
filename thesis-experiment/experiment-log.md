# AI-Assisted Software Maintainability Experiment

## 1. Pilot Repository

**Repository:** `redis-replicator`

**Original repository:**  
https://github.com/leonchen83/redis-replicator

**Experiment fork:**  
https://github.com/Rikita-Shil/redis-replicator

**Experiment branch:** `thesis-experiment`

The `redis-replicator` project was selected as the first pilot repository for the study. It is an open-source Java project with an established development history, automated tests, and a Maven-based build system.

The repository is sufficiently large to provide meaningful maintainability measurements while remaining manageable for an honours thesis experiment.

---

## 2. Purpose of the Pilot

The purpose of the pilot experiment is to verify that the complete experimental workflow can be executed successfully before expanding the study to additional repositories, task types, or coding agents.

The pilot aims to confirm that I can:

1. build the repository successfully;
2. run the existing test suite;
3. establish a clean and reproducible baseline;
4. measure baseline software maintainability;
5. apply an AI-assisted maintenance task;
6. verify the modified software using the existing tests; and
7. measure maintainability again after the modification.

The intended workflow is:

Baseline
   ↓
Maintainability Measurement (M0)
   ↓
AI-Assisted Maintenance Task
   ↓
Build and Test
   ↓
Maintainability Measurement (M1)
   ↓
Compare M0 and M1
   ↓
Repeat for later maintenance cycles


## M0 Maintainability Baseline

Date: 22 September 2026

The first SonarQube analysis of the untouched repository was
successfully completed.

Baseline commit:

433f268e04121a4c43dd565642d7bb7e536829af

The SonarQube analysis completed successfully.

Initial results:

- Quality Gate: Passed
- Maintainability Rating: A
- Maintainability Issues: 714
- Duplication: 7.8%
- Cognitive complexity :2331 
- Duplication :7.8% 
- Duplicated lines:2675 
- Lines of code:20,586 
 
## 2. Baseline Definition

The original source-code baseline for the experiment is:

`433f268e04121a4c43dd565642d7bb7e536829af`

This commit represents the production source state before any
AI-assisted maintenance modification.

Subsequent commits made only to files under `thesis-experiment/`
are treated as experiment documentation changes and do not alter
the production-code baseline.
Additional values for technical debt, complexity and cognitive
complexity will be recorded from the SonarQube Measures page.

This establishes M0, the maintainability state before any
AI-assisted modification.

Next step:

Define and execute Maintenance Task 1 to produce M1.

