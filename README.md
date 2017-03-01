# jira-report-time-logged-by-user
This is quick solution to JIRA not having an out the box way of reporting time logged per user, instead of just a project. This can be a bit of a road block for project managers. This was never intended to be 100% polished, as it was made quickly and I don't intend on updating this repo unless there is genuine interest, you're welcome to do what you want with it.


#### Installation
1. Clone this GIT repository.
2. Run `composer install` to install PHP dependencies.
3. edit the `$cfg` variable inside `index.php` to match your own JIRA domain / user login.

#### Usage
1.  Enter a project key,  JIRA creates this when starting a new project.
2.  Click run report, if all went well and there are no errors you can proceed to export this as CSV format.

![screen shot 2017-03-01 at 14 51 27](https://cloud.githubusercontent.com/assets/2064944/23467579/57ae1512-fe96-11e6-893d-b08615e80811.png)

#### What it does
This tool uses the JIRA REST API, however it requires your user email and password for basic authentication, and this user would require permissions to view the project and obtain the data requested - so please be mindful of this fact.

#### Future updates
If you need a feature, feel free to request it (I can try find time to help you), or alternatively submit a pull request.

#### Disclaimer
Sorry, I can't be held liable for any problems this script may cause to your system, use at your own peril!