#feature
#done

### Summary
Ability to edit intranet users information from the Admin dashboard - Edits an existing user record in the security database. The users username, full name, access level, division and job role can be edited and committed to the database.

#### To Implement

- [x] Add edit users button
- [x] Create edit users popup
	- Dropdown to select user to edit
	- Load user data from database and parse into form input boxes
- [x] On update button click pass input values to XHR
- [x] SQL Update query to update user record
- [x] Return successful update message