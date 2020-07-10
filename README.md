# ml_model_docker
Containerised a ml application using docker
1. Install docker
2. Clone this repo through git
3. Go to the folder
4. Execute the following commands in cmd:
5. docker build -t mlmodel:1.0 .
6. docker run --p 5000:5000 --name task1 mlmodel:1.0
7. go to 127.0.0.1/5000 in your browser to see the running containerised application
