# itemkart_API
API with web token security

#Steps to run API

1)Download code from githun link as https://github.com/chavhanpunamchand/itemkart_API.git

2)install the all requirements.txt

3)create the database(itemkartdb) in mysql.

4)Run the maincontroller.py file

5)Open the postmen API collection link https://www.getpostman.com/collections/f9131ddb46d6eb0d560d

6)Test the API, API test procedure as follows
                i) Run Register_user API with user details as given in API body.
                ii) Run Login API with in Authentication--->select Basic Auth-->change username and password as you given for registration.
                                                                               output getting token--->copy token
                iii)Run Add item API with Authentication--->select Basic Auth-->change username and password as you given for registration,
                                                                                 important part{ in header add context-type  as application/json
                                                                                               x-access-token as copy token }
                                                                                 in body{
                                                                                 add feilds
                                                                                 }
                                                                                 
                 vise-versa run all API
7) This way API testing done properly with web-token security                 
                 
                 
                 
                 
                 
                                                                                               
                                                                                               
        



