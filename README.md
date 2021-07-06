# Simple React JS Project for Read Json File

## What is the use of this Repo

This Project is a Simple ReactJS Project which demonstrates the following
1. Creating a Component in React
2. Making HTTP calls
4. Using Bootstrap along with React
5. Using Basic Routing in React



## Live Application URL

### https://github.com/devstarkedge/read-json-file.git
This URL has the application deployed in

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**


## Application design

#### Components

1. **Customers** Component : This Component displays a list of customers. This Component gets the data from a json file in assets folder

2. **CustomerDetails** Component : This Component Displays the details of the selected customer. This Component gets its data from a json file in assets folder as well. This Component is the Child Component of *Customers* Component

#### HTTP client

**axios** library is used to make HTTP Calls

#### URL

The application has just one url /customerlist which ties to *Customers* Component
