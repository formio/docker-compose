# Form.io Enterprise Local Docker Compose
This library shows how to run the Form.io Enterprise solution within your own Local environment.

## Installation
You must have Docker installed and running before you can use this library.

 - Download this repo and unzip the contents into a folder.
 - Within the folder, you will need to edit the ```.env``` file and change the following line.

```
LICENSE_KEY=YOURLICENSE
```

You will need to make sure you change this to be your license.

## Running
Once you have the correct parameters within the ```.env``` file, you can run this library using the following command.

```
docker-compose up --detach
```

This will start the Form.io platform, where you can then go to the following URL's in your browser:

 - Form.io Enterprise Server - http://lvh.me
 - Form.io PDF Server - http://lvh.me/pdf

The default admin login is as follows.
 - admin@example.com
 - CHANGEME

## Configuring
Once you have a project, you can configure the PDF server by navigating to the Project Settings, and then change the PDF Server URL configuration to the following.

```
http://lvh.me/pdf
```

Enjoy!


