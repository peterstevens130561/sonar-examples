This example demonstrates how to analyze a PHP project with the SonarQube Runner.
It reuses existing unit test execution and code coverage reports from PHPUnit.

Prerequisites
=============
* [SonarQube](http://www.sonarsource.org/downloads/) 4.2 or higher
* [SonarQube Runner](http://docs.codehaus.org/x/N4KxDQ) 2.3 or higher
* [SonarQube PHP Plugin](http://docs.codehaus.org/x/9IA9Dg) 2.0 or higher

Usage
=====
* In "reports/phpunit.coverage.xml", change the path "C:\git\sonar-examples-old\projects\languages\php\php-sonar-runner-unit-tests\reports/src/Math.php" to the location of this file on your machine.
* Analyze the project with SonarQube using the SonarQube Runner:

        sonar-runner
