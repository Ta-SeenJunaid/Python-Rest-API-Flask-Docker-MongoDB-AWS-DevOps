This is a learning project from following Udemy Course:

https://www.udemy.com/course/python-rest-apis-with-flask-docker-mongodb-and-aws-devops/

To run the applications, you've to run all commands according to the path of docker-compose file.

In this project a person will get some token during registration time and by using each token, that person can store a sentence or update a stored sentence or read that sentence.


To build the project:

```
sudo docker-compose build

```

To run the project:

```
sudo docker-compose up

```
To register new user with "localhost:5000/register" link, the post method JSON example is:

```
{
    "username": "Tas",
    "password": "123abc123"
}

```

To store new sentence with "localhost:5000/store" link, the post method JSON example is:

```
{
    "username": "Tas",
    "password": "123abc123",
    "sentence": "I like Computer Programming"
}

```

To get stored sentence with "localhost:5000/store" links, the post method JSON example is:

```
{
    "username": "Tas",
    "password": "123abc123"
}

```
