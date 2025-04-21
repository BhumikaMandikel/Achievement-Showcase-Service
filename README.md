# Achievement Story Posting Microservice

This microservice allows an administrator to post and manage achievement stories, which include both text and image content. It is designed for showcasing student achievements and alumni stories. The service is built using Python (Flask), and it supports both MongoDB  for flexible data storage. The application is containerized using Docker, making it easy to deploy and run locally or in production.

## Features
- **Admin Panel**: Only the administrator can post new achievements (text and image).
- **Public Display**: Achievement stories are publicly visible to users but cannot be modified by them.
- **Image and Text Support**: Achievements can include text and image content.
- **Database Support**: MongoDB can be used for data storage.
  
## Tech Stack
- **Backend**: Python, Flask
- **Database**: MongoDB 
- **Containerization**: Docker

## Getting Started

Follow the steps below to get your local development environment up and running.

### Prerequisites
- Docker and Docker Compose installed on your system.

### Execution
~
docker-compose build
~
~
docker-compose up
~

