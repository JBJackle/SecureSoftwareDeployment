# SecureSoftwareDeployment

This project is for an assignment showing that we know how to check in an ASP.NET projects without revealing the data used to seed the database or any keys used.

This project requires a secrets.json file formattes as below:
{
	"ConnectionStrings": {
		"DefaultConnection": "Your_DB_String"
	},
	"Secrets": {
		"AdminPwd": "APassword",
		"MemberPwd": "AnotherPassword",
		"AdminEmail": "Some_Email",
		"MemberEmail": "Some_Other_Email"
	}
}
