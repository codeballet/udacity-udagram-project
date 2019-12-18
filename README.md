# Udagram project submission
## Main building blocks
The project has four main building blocks:
* One frontend web interface
* A backend feed that serves images from a database
* The above referred to database
* A backend user service that deals with authentication and user account

## How to run the app
You may run the app locally with docker-compose, or in a kubernetes cluster in the cloud.

Run the app locally with docker-compose:
1. Clone the git repo.
2. Make sure you have all necessary environment variables defined
3. Run `docker-compose up`

Run the app in a kubernetes cluster:
1. Create a kubernetes cluster
2. `cd` into the `udacity-deployment` directory
3. Run `kubectl apply -f k8s`
