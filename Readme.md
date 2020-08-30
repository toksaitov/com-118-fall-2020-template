# COM-118, Fall 2020: Course Directory

Here all the lab sources, URI solutions, and projects should be stored and submitted by the student to his private course repository. The repository MUST be shared with the instructor and only with him. The student MUST commit and push to GitHub periodically after finishing work on every lab problem, URI solution, or part of a project. The repository will be periodically checked by the instructor or an automated script and graded. Ensure to keep the directory in good order. Ensure to precisely follow the naming convention for directories, files, and classes. Your grade will be lowered if the naming is not correct, and the autograder fails to test your work. Do not share your work and don't plagiarize other people's work. Your repository will be checked for plagiarism from time to time. In the case of an infraction, you will be reported to the registrar office and automatically fail the course.

## Checkpoint Grading

Your instructor will announce a periodic review of your work. You will be awarded up to the following number of points for such checks:

* __Labs__: 10 point
* __URI solutions__: 10 points
* __Project 1__: 4 points
* __Project 2__: 4 points

In total, all the checkpoints cost *28 points* of your final grade.

## Required Software

Install the following software on your machine and clone the remote repository.

* [Amazon Corretto JDK 8](https://aws.amazon.com/corretto)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download)
* [Git](https://git-scm.com)

## Processing Libraries

The directory contains libraries extracted from the Processing project which is distributed under the LGPL license.

## Naming Convention

### Commit Messages

Commit messages should briefly explain the nature of change. Project commits may contain detailed commit description on a separate line.

#### Examples

```
Finish Problem 1 in Lab 1
Finish URI 1001
Add UI to select levels
...
```

### Module Names

You MUST use the following names for project modules.

* `lab-01`
* `lab-02`
* `lab-03`
* `lab-04`
* `lab-05`
* `lab-06`
* `lab-07`
* `lab-08`
* `project-01`
* `project-02`
* `uri`

### Labs

`Problem<NN>.java` where NN is the problem number with the leading 0 in front if less than one digit is used.

#### Example

```bash
Problem01.java
Problem02.java
...
```

### URI Solutions

`URI<NNNN>.java` where NNNN is the URI problem ID. Note, that to submit your solution to URI, you have to rename the class name from URINNNN to Main. Don't forget to do that!

#### Example

```bash
URI1001.java
URI1002.java
...
```

### Projects

File naming for a project will be explained in the project requirements.
