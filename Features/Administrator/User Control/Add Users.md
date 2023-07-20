#feature 
#done

### Summary
Ability to add intranet users from the Admin dashboard - Creates a new user record in the security database. The new users username, full name, access level, division and job role will be recorded and added.

#### To implement

- [x] Click button
- [x] Ask user for required details
	- First Name
	- Last Name
	- Username (concatenate FirstName.LastName)
	- DOB ( to create password -> John Smith 01/05 = JSmi0105)
	- Email Address (same as username + division domain)
	- Divisions
		- Subs Mon
		- SML Surveys
		- SML Group
		- Ratcliff
		- Landmark
		- Geo Info
		- Geo Cad
	- Access level (department)
		- User
		- Manager
		- Administrator
		- Other/Custom
	- Jo
- [x] Pass details into Access database and create new record
	- username (Username)
	- fullname (First Name + Last Name)
	- alias (First Name)
	- locked (no)
	- reset_password (no)
	- company (SMLG)
	- division (Division)
	- department (Access Level)
	- jobtitle (Job Role)
	- disptt (yes)
- *Create user in Active Directory
	- *First Name (First Name)
	- *Last Name (Last Name)
	- *User logon name (Username)
	- *Password
	- *Password confirm
- *Create email address in O365
	- *First Name (First Name)
	- *Last Name (Last Name)
	- *Username (Username)
	- *Password
	- *Standard License
	- *Custom Attribute 1 (user)