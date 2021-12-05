**A demo project created in java, using spring boot and h2 database. It is deployed on aws ec2 instance.**


GET - http://ec2-13-235-132-159.ap-south-1.compute.amazonaws.com:8080/api/users

POST - http://ec2-13-235-132-159.ap-south-1.compute.amazonaws.com:8080/api/users

    request - 
    {
        "firstName" : "test1",
        "lastName" : "test1",
        "email" : "abc@xyz.com"
    }

GET - http://ec2-13-235-132-159.ap-south-1.compute.amazonaws.com:8080/api/users/{id}

DELETE - http://ec2-13-235-132-159.ap-south-1.compute.amazonaws.com:8080/api/users/{id}

h2 console : 
http://ec2-13-235-132-159.ap-south-1.compute.amazonaws.com:8080/h2-console

JDBC url : jdbc:h2:mem:usersdb
