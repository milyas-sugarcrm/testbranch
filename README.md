Addoptify Customer Journey Plugin®
=============================

Copyright (C) Addoptify. All rights reserved.

# Architecture of the Source Code

- :open_file_folder: **src**
	- :open_file_folder: **custom**
		- :open_file_folder: **clients / base**
			- :open_file_folder: **fields**
				- :file_folder: **cj_fieldset_for_date_in_populate_fields**
				- :file_folder: **cj_momentum_bar**
				- :file_folder: **cj_populate_fields**
				- :file_folder: **cj_progress_bar**
				- :file_folder: **cj_select_to**
				- :file_folder: **cj_time**
				- :file_folder: **cj_widget_config_toggle_field**
			- :open_file_folder: **layouts**
				- :file_folder: **dri-workflows**
				- :file_folder: **dri-workflows-widget-configuration**
			- :open_file_folder: **views**
				- :file_folder: **cj-as-a-dashlet**
				- :file_folder: **cj-webhook-dashlet**
				- :file_folder: **dri-customer-journey-dashlet**
				- :file_folder: **dri-customer-journey-momentum-dashlet**
				- :file_folder: **dri-license-errors**
				- :file_folder: **dri-workflow**
				- :file_folder: **dri-workflows-header**
				- :file_folder: **dri-workflows-widget-configuration**
		- :open_file_folder: **data**
			- :file_folder: **acl**
		- :file_folder: **Extension**
		- :open_file_folder: **include**
			- :open_file_folder: **CustomerJourney**
				- :file_folder: **Css**
				- :open_file_folder: **Javascript**
					- :file_folder: **sugar7**
			- :open_file_folder: **SugarObjects / implements**
				- :open_file_folder: **customer_journey_parent**
					- :file_folder: **clients**
					- :file_folder: **Ext**
					- :file_folder: **language**
		- :open_file_folder: **src**
			- :open_file_folder: **CustomerJourney**
				- :open_file_folder: **Bean**
					- :file_folder: **Activity**
					- :file_folder: **ActivityTemplate**
					- :file_folder: **Journey**
					- :file_folder: **JourneyTemplate**
					- :file_folder: **RSA**
					- :file_folder: **Stage**
					- :file_folder: **StageTemplate**
					- :file_folder: **WebHook**
				- :file_folder: **Exception**
				- :file_folder: **Hooks**
				- :file_folder: **ImportExport**
				- :file_folder: **License**
				- :file_folder: **SharedData**
		- :file_folder: **themes**
	- :open_file_folder: **CustomerJourney**
		- :file_folder: **Command**
	- :open_file_folder: **modules**
		- :file_folder: **CJ_Forms**
		- :file_folder: **CJ_WebHooks**
		- :file_folder: **DRI_SubWorkflow_Templates**
		- :file_folder: **DRI_SubWorkflows**
		- :file_folder: **DRI_Workflow_Task_Templates**
		- :file_folder: **DRI_Workflow_Templates**
		- :file_folder: **DRI_Workflows**
- :file_folder: **tests**

# Developer Environment Standup

* Steps to Setup the Project:
    [CJ Plugin Project Setup](https://github.com/addoptify/customer-journey/blob/master/README.md#steps-to-setup-the-project)

# Project Coding Standards

Code guidelines are followed and JavaScript coding standards applied:
* [JavaScript Guidelines](https://developer.mozilla.org/en-US/docs/MDN/Guidelines/Code_guidelines/JavaScript)
* [PHP Standards Recommendation](https://www.php-fig.org/psr/)

# Project Testing Standards

Project functionalities are tested using the following frameworks:
* PHPUnit [Unit Testing](https://phpunit.de/)

# Deployment

Code is maintained on Git and is deployed on the servers.
