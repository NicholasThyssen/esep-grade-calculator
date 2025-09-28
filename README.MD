# ESEP Grade Calculator

This library is a simple utility to calculate your grades and converting them to the corresponding letter grade. Grades are calculated with different assignment, exam and essay weights.

##Technology used:
Golang 1.24+

The program is simply run by using the Golang programmning language. It contains 3 different important files, with each being described below:

Go.mod: First it makes a module with the same name as the repository name and then it states that it is utilizing go version 1.24.4.

Grade_calculator.go: This is where the code that explains what the functions are for the calculator.

Grade_calculator_test.go: Tests results for grades A, B and F. Could implement more test cases.

##Run unit tests:
To run the units tests, you can use the following code below in order to test if functionalites of the calculator are in place.

```
cd grade_calculator/
go test ./...
```

##Run unit tests with code coverage:
If you want to run the unit tests and check how much of the code is actually being used, you can run the command below.

```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
