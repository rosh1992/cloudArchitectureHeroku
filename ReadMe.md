

##Kickstarter is the world’s largest crowdfunding platform. The application that we have created for this project allows the user to query from a dataset of more than 300,000 kickstarter projects. The cloud technology we have used to access the dataset for the back end was Apache Spark, while Angular 4 framework was used to create the web application at the front end.

##The back end application is hosted on AWS whihch runs a jar file and accepts requests from the client which is running on the heroku app.


###To send a request

url : http://localhost:8080/api/projects 
Body
{
	"subCategory":"Food",
	"category":"Food",
	"country":"US"
} 

Request Headers : Content-Type:"application/json" , Accept:"application/json"
