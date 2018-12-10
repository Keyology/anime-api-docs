# Authentication

 Welcome to Anime API this page documents how to authenticate user using our API endpoints.

to authenticate user you can either use fetch and send a form name=email && named name=password, or you can use postman and send the email and password over as json 

###  send a post request to this   url endpoint

``` http://localhost:4000/signup ```


### exaple of sending user data over in json using postman


``` 
{
	"email":"Enter email here",
	"password": "Enter password here "

	
}
```

Once a user signs up you will recieve a JWT that looks something like this:

```
"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI1YzBkYjlmZjdjNmMwYjFiOTQ3NTJmYmQiLCJpYXQiOjE1NDQ0MDM0NTUsImV4cCI6MTU0NDQxMDY1NX0.cNWvoTYGp6pQGjK1IOyR2iF0V98GexesSmjx5dY3K4o"

```

### To login user  you can send a post request to this  url endpoint: 

``` http://localhost:4000/login ```




### Example of sending login info in json format using postman:

```

{
    "email":"Enter email here",
	"password": "Enter password here "


}

```

