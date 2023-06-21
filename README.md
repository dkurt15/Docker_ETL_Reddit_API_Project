# Docker_ETL_Reddit_API_Project
Pulling Reddit data using APIs, setting up a Docker pipeline with an ETL job for data preprocessing, and performing sentiment analysis on the processed data.

# Technologies and Libraries

Python 3.6-slim
requests
pandas
logging
pymongo
SQLAlchemy<2.0.0
psycopg2-binary
vaderSentiment
datetime

# Setup

Docker simplifies the process of setting up and configuring software applications by packaging all the necessary dependencies, libraries, and configurations 
into a single container. 

After getting necessary API Key, API Secret from Reddit Developer Account, your are ready to create Docker Container. 

- First need to <cd> into the folder which contains docker-compose.yml file
- build all container images:
   docker-compose build
- build/create and start the entire pipeline in the background:
   docker-compose up -d
- show all running containers:
  docker-compose ps
- check services separately:
  docker-compose logs <service name>
- remove all stopped containers
  docker-compose rm

 
  

