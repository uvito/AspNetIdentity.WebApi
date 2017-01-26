
http://bitoftech.net/2015/01/21/asp-net-identity-2-with-asp-net-web-api-2-accounts-management/

create DBs:
	- enable-migrations
	- add-migration InitialCreate
	- update-database
GET http://localhost:59822/api/accounts/users
	- remove authorization check from the controller


