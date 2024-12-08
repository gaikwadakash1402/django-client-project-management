# django-client-project-management

# Django Client & Project Management System

This repository contains a Django-based system designed to manage users, clients, and projects with robust REST APIs. It utilizes MySQL as the database and adheres to the following relationships:
- Many Users
- Many Clients
- A Client can have multiple Projects
- A Project can be assigned to multiple Users

## Features

1. **User Management**
   - Register users using Django's default admin template or REST APIs.

2. **Client Management**
   - Register new clients.
   - Retrieve a list of all clients.
   - Fetch client details along with associated projects and assigned users.
   - Update/Delete client information.

3. **Project Management**
   - Add new projects under a specific client.
   - Assign existing users to projects.
   - Retrieve all projects assigned to the logged-in user.
