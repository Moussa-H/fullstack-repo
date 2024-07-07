# fullstack-repo

README File
Project Overview:

This project consists of three main repositories:

frontend-repo:

Contains files related to the frontend client.
Main file: client.py, which interacts with the configuration file in fullstack-repo.
backend-repo:

Contains files related to the backend server.
Main file: server.py, which interacts with the configuration file in fullstack-repo.
fullstack-repo:

Acts as a unified repository containing:
config.yaml: Configuration file with variables accessible by both frontend-repo and backend-repo.
Submodules (frontend/ and backend/): Mirrors of frontend-repo and backend-repo, allowing for automatic updates from their respective repositories.
Usage:

frontend-repo:

Run client.py to utilize client functionalities.
Reads variables from config.yaml located in fullstack-repo.
backend-repo:

Run server.py to manage server functionalities.
Accesses configuration variables from config.yaml in fullstack-repo.
Setup:

Clone frontend-repo, backend-repo, and fullstack-repo repositories.
Ensure submodules (frontend/ and backend/) in fullstack-repo are initialized and updated.
Modify client.py and server.py to read config.yaml for relevant variables.
Maintenance:

Regularly update submodules in fullstack-repo to reflect changes from frontend-repo and backend-repo.
Ensure synchronization of variables in config.yaml across all repositories for consistent functionality.
This setup allows for modular development of frontend and backend components while maintaining centralized configuration management in the fullstack-repo.
