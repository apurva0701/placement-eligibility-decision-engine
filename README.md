# Placement Eligibility Decision Engine

A Java-based OOP project that checks whether a candidate is eligible for a selected job based on the company's requirements.

## Features

- Runtime candidate input
- Runtime candidate skills
- Runtime job input
- Multiple jobs using arrays
- Runtime job selection
- Percentage eligibility
- Backlog eligibility
- Graduation year eligibility
- Required skill eligibility
- Final eligibility result

## OOP Concepts Used

- Encapsulation
- Abstraction
- Inheritance
- Method Overriding
- Polymorphism
- HAS-A Relationship

## Project Structure

- Main.java - Controls application flow
- Candidate.java - Stores candidate details and skills
- Job.java - Stores job requirements
- EligibilityRule.java - Abstract parent class for eligibility rules
- PercentageRule.java - Checks percentage
- BacklogRule.java - Checks backlogs
- GraduationYearRule.java - Checks graduation year
- SkillRule.java - Checks required skills
- EligibilityChecker.java - Executes all eligibility rules

## Compile

```bash
javac src/*.java
```

## Run

```bash
java -cp src Main
```
