# springBootSecurity3.0AndJwt -> jwtToken authorization type  is Bearer Token , user-email, password
#step1: PostApi for user registeration and give response  jwtToken :->localhost:8081/api/v1/auth/register
Body:
{
   "firstname":"abc12",
   "lastname":"abc12",
   "email":"abc123@gmail.com",
   "password":"1234"

}

#step2: PostApi for authenticate and give response jwtToken :->localhost:8081/api/v1/auth/authenticate
Body:
{
    "email":"abc@gmail.com",
   "password":"123"
}

step3:getApi for get data , using  Bearer Token for authorize and give response  -> localhost:8081/api/v1/demo-controller

