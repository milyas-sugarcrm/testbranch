Addoptify Customer Journey Mobile Plugin®
=============================

Copyright (C) Addoptify ApS. All rights reserved.

# Architecture of the Source Code

- :file_folder: **config**
- :open_file_folder: **custom**
	- :open_file_folder: **views**
		- :file_folder: **base**
		- :open_file_folder: **customer-journey** (**journey** **.js** controllers and **.hbs** files)
			- :file_folder: **cj-detail-view** (**.hbs** files for the detail view)
			- :clipboard: cj-container.js
			- :clipboard: cj-detail-view.js
			- :clipboard: cj-drop-down.hbs
			- :clipboard: cj-drop-down.js
			- :clipboard: cj-list-item.hbs
			- :clipboard: cj-list-item.js
			- :clipboard: cj-list-view.js
			- :clipboard: cj-model.js
		- :open_file_folder: **detail-view**
			- :clipboard: detail-view.js
		- :open_file_folder: **edit-view**
			- :clipboard: activity-edit-view.js
			- :clipboard: edit-view.js
			- :clipboard: meeting-calls-edit-view.js
			- :clipboard: quotes-edit-view.js
			- :clipboard: revenue-line-items-edit-view.js
		- :open_file_folder: **main-menu**
			- :clipboard: cj-main-menu-view.js
		- :clipboard: CJAPIManager.js
		- :clipboard: userCache.js
- :open_file_folder: **tests**
	- :clipboard: CJ.js

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
