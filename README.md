Addoptify Customer Journey Mobile Plugin®
=============================

Copyright (C) Addoptify. All rights reserved.

# Architecture of the Source Code

- :file_folder: **config**
- :open_file_folder: **custom / views**
	- :file_folder: **base**
	- :open_file_folder: **customer-journey** (**journey** **.js** controllers and **.hbs** files)
		- :file_folder: **cj-detail-view** (**.hbs** files for the detail view)
	- :file_folder: **detail-view**
	- :file_folder: **edit-view**
	- :file_folder: **main-menu**
- :file_folder: **tests**

# Developer Environment Standup

* To setup the Mobile project:
    [Mobile SDK Quick Start Guide](https://support.sugarcrm.com/Documentation/Mobile_Solutions/Mobile_SDK/Mobile_SDK_Quick_Start_Guide/)

# Project Coding Standards

Code guidelines are followed and JavaScript coding standards applied:
[JavaScript guidelines](https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/JavaScript)

# Project Testing Standards

Project functionalities are tested using the following frameworks:
* Selenium [WebDriver](https://www.selenium.dev/documentation/webdriver/)
* Mocha [mochajs](https://mochajs.org/)

# Deployment

Code is maintained on Git and is deployed on the servers.
