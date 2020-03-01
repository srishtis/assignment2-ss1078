# assignment2-ss1078
This is for assignment 2 for ece 590


## What does the app do?
It counts the number of page visits on a given web page. The page when loaded looks like:

![demo app](https://github.com/srishtis/assignment2-ss1078/blob/master/assignment2-ss1078.PNG)


## How to run the app
The app is already packaged with a Dockerfile which sets and configures the environment. The docker-compose.yml file sets and configures the services for the flask app: both python and redis (as redis is being used for counting the page visits).

### Steps:

1. Clone the repository using: 

```
git clone https://github.com/srishtis/assignment2-ss1078.git
```

2. Then simply run:

```
docker-compose up
```

This will start and run your complete app. You can access the app at : http://0.0.0.0:5000/ 

3. If you run ```docker-compose up -d```, it builds and runs the docker image in the backend (detached mode)

4. You can stop the app with ```docker-compose stop```

5. You can also bring the services down and remove the containers using:

```docker-compose down --volumes ```


### Demo:

A demo video of how to use the app has been added to the repo [![here](https://img.youtube.com/vi/AiZT15TO7oE/0.jpg)](https://www.youtube.com/watch?v=AiZT15TO7oE)
