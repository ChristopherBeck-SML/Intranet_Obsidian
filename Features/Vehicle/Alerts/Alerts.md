#contents
- Admin
		- Vehicle Expiration
			- [[Tax]]
			- [[MOT]]
			- [[Transport for London]]
			- [[Mileage and Servicing]]
			- [[Cambelt]]
			- [[Insurance]]
			- [[AA]]
			- [[Transport for London]]
		- Drivers
			- [[DBS Expiration]]
			- [[DVLA setup]]
			- [[ Incidents]]
			- [[AA]]
			- [[Fines]]

	- User
		- DVLA setup
		- AA details
		- PCN's/Fines
		- Expiration
			- DVLA
			- DBS 
			- License
			- MOT


If (Department = manager)
	Connect to database
	Check vehicle expiration dates against today()
	Calculate number of days until expiration 
	Move next
	Alert(these vehicles are going to expire in the next 60 days:
	ABC DEFG: 26 days
	HIJ KLMN: 52 days
	OPQ RSVW: 4 days)