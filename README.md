# moodle-sql-test

## Description:
Given the pre-populated Moodle instance and database schema hosted at https://sql-test.learn.studio/, create a SQL statement which returns a result-set containing a list of all users that have been assigned the “Student” role in the “SQL Test” course. The result-set should also include the number of activities which have been completed per user within the highlighted section (“Topic 1”) of this course represented as a percentage.

## Notes:
* Moodle site administrator and read only database access will be forwarded via email
* Any SQL tools or web resources can be used
* The following fields must be present:
  * First Name
  * Last Name
  * Email Address
  * Course
  * Activities Completed (%) – calculated as (number of completed activities in the highlighted section / total number of activities in the highlighted section) * 100
* Once completed the SQL statement must be saved to a file named “[your-name].sql” and a pull request must be created on this GitHub repository.