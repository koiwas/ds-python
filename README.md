# Docker Setup
This repository provides an environment to quickly spin up Jupyter Lab using Docker.
## Prerequisites
1. Make sure you have Docker installed on your machine. If not, download and install it from [Docker's official website](https://www.docker.com/).
2. Docker Compose should also be installed. It comes bundled with Docker Desktop for Windows and Mac. For Linux, you might need to install it separately.
## Getting Started
1. Clone the Repository
```
git clone {repository_url}
```
```
cd {directory_name}
```
2. Start Jupyter Lab
```
docker-compose up
```
You can access Jupyter Lab's interface by visiting http://localhost:8888 in your browser.
## Note
- Any changes made in the Jupyter Lab interface will be reflected in the mylab directory on your host machine due to the volume mount.
- To stop Jupyter Lab, press Ctrl+C in the terminal where it's running.
