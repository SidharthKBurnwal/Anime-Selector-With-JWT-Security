Verify a user with proper JWT Token.

Post : http://localhost:8080/authenticate

Body : 

{
	"uesrname" : "foo",
	"password" : "foo1"
}

Header :

Content-Type application/json



GET :  http://localhost:8080/hello

Header : 
Authorization 
Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJmb28iLCJleHAiOjE1NzM1MzY5NDAsImlhdCI6MTU3MzUwMDk0MH0.jWuA2Vh8Ex5WIe25V0ganyfvxc_9LLozWhHrgSBFPj0
