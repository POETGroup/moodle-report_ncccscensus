This plugin was developed by Remote Learner for the North Carolina Community College System for the purposes of FTE reporting by their colleges. The report shows first attempts with related data for enrolled students on selected courses over a specified date range. It supports the activity types Assignment, Forum, Glossary and Quiz. It was be run on individual courses by teachers or on many courses by Site Administrators.

# Installation
- Obtain a copy of the plugin from https://github.com/cbmegahan/report_ncccscensus
- Place the “ncccscensus” folder into the “reports” folder within your Moodle wwwroot directory. 
- Log in as a Site Administrator and navigate to “Site administration / Notifications” to complete the installation steps.

# Settings
The settings for this plugin are located at “Site administration / Plugins /  Reports / Census Report”.

# Course Reporting
Within a course, the report can be selected from the Course Administration’s reports submenu. This can be accessed by users with the “report/ncccscensus:view” capability which are editingteachers and managers by default.

# Bulk Reporting
Site Administrators can run reports on multiple courses in a variety of ways. To do so navigate to “Site administration /  Reports /  Census Bulk Report”. After selecting an option, completing the forms and clicking “Generate Reports”, the request will be queued and processed by the cron. The “Past reports” page will list past reports and their status. After a report is completed processed by the cron the status will change from “Processing” to “Completed” and a download button will appear. Clicking this will download a zip file with a PDF report for each courses the report has been run on.
