# Python Web Application

This is a simple containerized Python web application using Flask that performs basic arithmetic operations. The application is packaged with Docker to ensure consistent and portable deployment.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Docker](https://www.docker.com/products/docker-desktop)
- [Python 3](https://www.python.org/downloads/)


## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Step 1: Clone the Repository

```bash
git clone git@github.com:RuchiLamichhane/Python_Deploy.git
cd Python_Deploy

docker build -t pycal .
docker run -p 5000:5000 pycal:latest



