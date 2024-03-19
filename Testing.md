# SonarQube

## What is Software Testing?

Software Testing is a part of software development lifecycle, it’s aim is to ensure that the code deployed is of high quality with no bugs and no logical errors.

## Testing type:

### Manual Testing:

The tester will manually complete all the test cases.

### Automatic Testing:

The tester will write scripts to test the application.

## Testing Approaches:

### Black box testing:

Here tester doesn’t know what the internal structure of application is.

### White box testing:

Here tester knows the internal structure of application.

### Gray box testing:

Here tester knows bits and pieces of internal structure.

## Testing Levels:

### Unit Testing:

Here each module is tested separately.

### Integration Testing:

Here group of modules are tested together.

### System Testing:

Where the whole system is tested.

### Acceptance Testing:

Here the whole system is tested for acceptability, whether it met the client requirements or not.

## Testing Methods:

### Dynamic Testing:

It happens during the execution of the code. It can help identify subtle defects or vulnerabilities because it also looks at the code’s integration with other databases, servers, services.

### Static Testing:

It’s a method of debugging by examining the source code before program is run i.e., test the code before it’s run. It does so by analyzing the code against a set of pre-defined rules. It can be done by IDE as well. But tools like SonarQube can give developers more comprehensive results.

## SonarQube:

It’s an open-source static testing analysis software. It is used by developers to manage source code quality and consistency.

### Features of SonarQube:

It works with 25languages.

- Detect Bugs.
- Code Smells.
- Security Vulnerabilities
- Activate Rules Needed
- Execution Path

## Setting up SonarQube in VM:

Install Java version 17 and install Sonarqube Community free edition.

SonarQube Installation: https://www.sonarsource.com/products/sonarqube/downloads/

After installation run it on http://localhost:9000
and login with default username and password admin:admin, which'll prompt to chnage password, change it and save somewhere carefully otherwise it'll be difficult to chnage password.

Install SonarQube Extension on Azure DevOps from MarketPlace and create a service connection with that server.

Build the YAML build pipeline between SonarQubePrepare@5 and SonarQubeAnalyze@5 tasks.
