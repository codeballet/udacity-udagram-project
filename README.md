# Udagram project submission
## Main building blocks
The project has four main building blocks:
-One frontend web interface
-A backend feed that serves images from a database
-The above referred to database
-A backend user service that deals with authentication and user account

## How to run the app
You may run the app locally with docker-compose, or in a kubernetes cluster in the cloud.

In order to run the app locally with docker-compose:
-Clone the git repo.
-Make sure you have all necessary environment variables defined
-Run `docker-compose up`

To run the app in a kubernetes cluster:
-Create a kubernetes cluster
-`cd` into the `udacity-deployment` directory
-Run `kubectl apply -f k8s`
