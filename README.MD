# ESEP Grade Calculator

This library is a simple utility to calculate weighted final grades from assignments, exams, and essays.

## Overview
The calculator computes the average for each category, calculates a weighted average, and converts the numerical grade to a letter grade.


## Runtime requirements
Golang 1.24+

## Installation

```
# Clone the repository
git clone https://github.com/audgster/esep-grade-calculator

# Navigate to the project directory
cd esep-grade-calculator/grade_calculator

# Download the installer for Go 1.24 
# from https://go.dev/dl/ and run it.
```

## Running Tests

### Run all tests:
```
cd grade_calculator/
go test ./...
```

### Run tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```