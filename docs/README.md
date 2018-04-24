# Heart Haven Outreach

## Background
Heart Haven Outreach (H2O)  is a ten-year old organization that serves the needs of the Valley View School District "at-risk" youth. They currently serve about 160 high school aged youth referred to us through the school district and the community. They have touched and changed the lives of over 1200 youth since we opened our doors. However, they do so on very limited funding and a limited number of staff.

See their [website](http://www.hearthavenoutreach.org) for more details.

 They are located in Bolingbrook and their IT is currently managed by the Village of Bolingbrook.  We've worked on two projects for them.  The first is an employee/volunteer evaluation form.  The second is a project to collect student data more effectively.  Once the projects are finished, we need to find a webhost for them so that the applications can be deployed. Both projects been implemented with a MySQL database and PHP.

## Survey Project

This project currently allows a user to take a pretest and a post test. The user is anoymous. In order for the user to take the post test, that user must first take the pretest if not done so. At the end of the pretest, a user id is generated and that user can use that id for the post test. There is a  database named database.sql and there are 4 tables. One for users, pretest, postest, and questions. After the tests are completed the data is stored in the database.

This application is also running on the Front Server.  You can access it [here]().  No credentials are required.

### Things to do
- Create a login page for pre-test and post-test survey.
- Validate login form using JavaScript and PHP. Missing fields must be highlighted.
- Create a pre-test and post-test survey.
- Identify missing answers on a page. Missing answers must be highlighted before going to the next page.
- Determine if there is a better way to authenticate.  Currently pre- and post-surveys are matched on user id.
- Add reporting.  There are currently CSV files, although it doesn't appear to work.  Actual reports should be added.
  - individual reports
  - composite reports
