# Katalon Studio Extent Reports Plugin

## Purpose
While Katalon Studio provides built-in test reports, this Extent Report plugin generates a JSON formatted report that can be used to merge individual reports into a single consolidated reports when running test suites in parallel.

## How to Integrate Extent Reports with Katalon Studio?
Integrating Extent Reports with Katalon Studio is straightforward and can be achieved in a few simple steps:

* Install the Extent Report plugin from Katalon Store. OR Alternatively, download this plugin offline from ChangeLog.

* That's it. The plugin will install its own test listener that will generate reports in an "Extent" subdirectory of the project directory.

* View Reports: You will find reports named ExtentReport.html and ExtentReport.json in the Extent directory.

## Notes:
* The plugin will generate reports exclusively for test suite and test suite collection executions. However, users retain the capability to execute individual test cases without encountering failures.
