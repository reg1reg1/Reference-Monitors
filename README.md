# Security Reference Monitor
## Overview
In operating systems architecture a reference monitor concept defines a set of design requirements on a reference validation mechanism, which enforces an access control policy over subjects' (e.g., processes and users) ability to perform operations (e.g., read and write) on objects (e.g., files and sockets) on a system. The properties of a reference monitor are captured by the acronym NEAT, which means:

The reference validation mechanism must be Non-bypassable, so that an attacker cannot bypass the mechanism and violate the security policy.
The reference validation mechanism must be Evaluable, i.e., amenable to analysis and tests, the completeness of which can be assured (verifiable). Without this property, the mechanism might be flawed in such a way that the security policy is not enforced.
The reference validation mechanism must be Always invoked. Without this property, it is possible for the mechanism to not perform when intended, allowing an attacker to violate the security policy.
The reference validation mechanism must be Tamper-proof. Without this property, an attacker can undermine the mechanism itself and thence violate the security policy.

## Objective
In the class of Computer security, we were presented with a 3 part assignment on implementing, breaking, and protecting reference monitors.

## Build a Reference Monitor
* Goal: Better understand security mechanisms
* Task: Write a reference monitor for the Seattle VM (version 2.0)
* Get a basic understanding about reference monitors
* You will have to build reference monitor in Repy V2(Restricted Python for Seattle) using instructions.
* Go to the following link:
https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartOne.md
* Use instructions on the page above to download Repy V2. Go to next slide to know what your reference monitor should do.

## Attack Reference Monitors
* Goal: Better understand security mechanisms
* Task: Attack other reference monitors
* Go to the following link:
https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartTwo.md

## Fix your reference monitor
* Examine the test cases that break your solutio
* For reference and instructions, use the link below:
https://github.com/SeattleTestbed/docs/blob/master/EducationalAssignments/ABStoragePartThree.md