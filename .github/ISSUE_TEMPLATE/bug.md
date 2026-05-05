---
name: Bug
about: A defect or unexpected behaviour
title: "[BUG] "
labels: Bug
assignees: QedMaen

---

##

### Description

A detailed but concise summary of the bug and the circumstances of its occurrence. This includes:

* if the bug was caught by automation or manually
* which environment the bug was encountered on
* if there are possible workarounds that remediate the impact

### Scenario

**GIVEN** the setup elements with shortcuts for future reference
   **AND** _

**WHEN** the exact and detailed step(s) that led to the specific outcome
   **AND** _
**THEN** expected: concise description of the expected behaviour/state after steps were executed
   **AND**_
**THEN** actual: concise description differences in behaviour/state that was observed instead

### Variations

If multiple paths can lead to the bug, indicate them briefly here

### Prioritization

Rate the bug priority on the following scales from 1 to 4:
**Probability**: how often do steps lead to the bug: 1 -- once, 4 -- always
**Frequency:** how likely are steps to occur during intended usage: 1 -- exotic edge case, 4 -- documented happy path
**Severity:** how much is the functionality disrupted: 1 -- cosmetic issue, 4 -- platform-wide denial

### Notes
