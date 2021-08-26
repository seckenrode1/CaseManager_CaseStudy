# CaseManager_CaseStudy
This webapp is to provide a tool for workers’ compensation law firms to keep track of client
 and case information. It stores client information, client addresses, where clients can have 
 more than one address, and cases, where contacts can have more than one case. 

The app uses Springboot, MariaDB, Thymeaf, and Bootstrap, and Spring Security. 
Built in login information:
Username = admin
Password = password 

The search bar capabilities of the nav bar are not yet working. The unit tests are not
done yet. There is still a lot of styling to get done. There is a schema.sql file that inserts
100 contacts, but it does not insert automatically. 





User Stories: 
As A	I want to	So that I can
Staff member (any user)	login	keep client information confidiental 
Staff member (any user)	Search for client by name and/or claim number	Access client information
Staff member (any user)	make notes in cases	keep everyone else up to date with case
Staff member (any user)	create/update/archive clients	maintain client information
Staff member (any user)	CRUD fields 	access current client information
