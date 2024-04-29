Reporting Engine Test Reports
================
Open System Pharmacology
2024-04-29

<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- 
Run testthat and get list of test results 
Note that "test_local" runs the scripts in ./R and then performs the tests
testResults includes a list per test script, which contains the following results
file, context, test, nb, failed, skipped, error, warning, user, system, real, passed, result
&#10;Turning the list to data.frame and extracting the relevant data will give a great overview of the test results
-->

| 📔 Total Reports | 🕵 Total Tests | 📊 Global Success Rate            |
|------------------|---------------|-----------------------------------|
| 6                | 90            | ![](https://geps.dev/progress/73) |

## Using Reports and Scripts as template

Users can find the reports and their description in the
[/Reports](./Reports) folder as well as the corresponding R code in the
[/R](./R) folder.

Models, Observed and Simulated Data are respectively available in the
[Models](./Models) and [Data](./Data) folders.

Here is the summary of the reports, their scripts and their run time
currently available in this repository:

| Report                                                                   | Script                                                                     | Run Time |
|:-------------------------------------------------------------------------|:---------------------------------------------------------------------------|:---------|
| [Aciclovir-Mean](./Reports/Aciclovir-Mean/Report.md)                     | [report-aciclovir-mean-svg.R](./R/report-aciclovir-mean-svg.R)             | 0.6 min  |
| [Aciclovir-Mean-SVG](./Reports/Aciclovir-Mean-SVG/Report.md)             | [report-aciclovir-mean-svg.R](./R/report-aciclovir-mean-svg.R)             | 0.7 min  |
| [Aciclovir-Population](./Reports/Aciclovir-Population/Report.md)         | [report-aciclovir-population.R](./R/report-aciclovir-population.R)         | 9 min    |
| [Raltegravir-Absorption](./Reports/Raltegravir-Absorption/Report.md)     | [report-raltegravir-absorption.R](./R/report-raltegravir-absorption.R)     | 1 min    |
| [Raltegravir-Mass-Balance](./Reports/Raltegravir-Mass-Balance/Report.md) | [report-raltegravir-mass-balance.R](./R/report-raltegravir-mass-balance.R) | 0.6 min  |
| [Test-NO7](./Reports/Test-NO7/Report.md)                                 | [report-NO7.R](./R/report-NO7.R)                                           | 0.3 min  |

## Test Results

| Report                                                               | Test                          | Status                                                             |   N | Success \[%\]                      | Warning \[%\] | Failed \[%\] |
|:---------------------------------------------------------------------|:------------------------------|:-------------------------------------------------------------------|----:|:-----------------------------------|:--------------|:-------------|
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected Files                | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Content of Report             | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected Plots                | ![](https://img.shields.io/badge/%E2%9A%A0-Failed%20tests-red)     |   4 | ![](https://geps.dev/progress/0)   | 0%            | 100%         |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected Simulation Results   | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected PK Analysis Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected Sensitivity Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected Goodness of Fit      | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean](./tests/Reports/Aciclovir-Mean)                     | Expected PK Parameter Tables  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected Files                | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Content of Report             | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected Plots                | ![](https://img.shields.io/badge/%E2%9A%A0-Failed%20tests-red)     |   4 | ![](https://geps.dev/progress/0)   | 0%            | 100%         |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected Simulation Results   | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected PK Analysis Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected Sensitivity Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected Goodness of Fit      | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Mean-SVG](./tests/Reports/Aciclovir-Mean-SVG)             | Expected PK Parameter Tables  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected Files                | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Content of Report             | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected Plots                | ![](https://img.shields.io/badge/%E2%9A%A0-Failed%20tests-red)     |  16 | ![](https://geps.dev/progress/0)   | 0%            | 100%         |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected Simulation Results   | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   2 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected PK Analysis Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   2 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected Sensitivity Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |  21 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected Goodness of Fit      | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   2 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Aciclovir-Population](./tests/Reports/Aciclovir-Population)         | Expected PK Parameter Tables  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   8 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Raltegravir-Absorption](./tests/Reports/Raltegravir-Absorption)     | Expected Files                | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Raltegravir-Absorption](./tests/Reports/Raltegravir-Absorption)     | Content of Report             | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Raltegravir-Absorption](./tests/Reports/Raltegravir-Absorption)     | Expected Absorption Results   | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   2 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Raltegravir-Mass-Balance](./tests/Reports/Raltegravir-Mass-Balance) | Expected Files                | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Raltegravir-Mass-Balance](./tests/Reports/Raltegravir-Mass-Balance) | Content of Report             | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Raltegravir-Mass-Balance](./tests/Reports/Raltegravir-Mass-Balance) | Expected Mass Balance Results | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   2 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Test-NO7](./tests/Reports/Test-NO7)                                 | Expected Files                | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Test-NO7](./tests/Reports/Test-NO7)                                 | Content of Report             | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Test-NO7](./tests/Reports/Test-NO7)                                 | Expected Simulation Results   | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Test-NO7](./tests/Reports/Test-NO7)                                 | Expected PK Analysis Results  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Test-NO7](./tests/Reports/Test-NO7)                                 | Expected Goodness of Fit      | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   2 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
| [Test-NO7](./tests/Reports/Test-NO7)                                 | Expected PK Parameter Tables  | ![](https://img.shields.io/badge/%E2%9C%93-Passed%20tests-success) |   1 | ![](https://geps.dev/progress/100) | 0%            | 0%           |
