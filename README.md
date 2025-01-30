# COBOL Data Corruption Bug: Uninitialized Variables

This repository demonstrates a common yet often overlooked bug in COBOL programs: data corruption caused by improperly initialized variables.

## Description

The bug arises from inconsistent initialization of variables `WS-AREA-1` and `WS-AREA-2`.  Improper handling can lead to unpredictable program behavior, including data corruption and unexpected results.

## Bug Reproduction

The `bug.cob` file contains the erroneous COBOL code.  The program demonstrates incorrect initialization practices leading to unexpected values and potential data corruption.  Execute this code to observe the consequences of the bug.

## Solution

The `bugSolution.cob` file offers a corrected version that explicitly initializes `WS-AREA-1` and `WS-AREA-2` before their usage, eliminating the potential for unpredictable behavior.  This ensures data integrity throughout the program's execution.

## Lesson Learned

This example highlights the importance of meticulous variable initialization in COBOL programming.  Failing to initialize variables consistently can result in hard-to-debug errors.