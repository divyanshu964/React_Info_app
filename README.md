# React JS Project

This Project is a Simple ReactJS Project which demonstrates the following
1. Creating a Component in React
2. Making HTTP calls
3. Communicating between parent and child component
4. Using Bootstrap along with React
5. Using Basic Routing in React

The project Template can be used to build bigger projects

## Application design

#### Components

1. **Customers** Component : This Component displays a list of customers. This Component gets the data from a json file in assets folder

2. **CustomerDetails** Component : This Component Displays the details of the selected customer. This Component gets its data from a json file in assets folder as well. This Component is the Child Component of *Customers* Component

#### HTTP client

**axios** library is used to make HTTP Calls

#### URL

The application has just one url /customerlist which ties to *Customers* Component

## Resources

**create-react-app** : The following link has all the commands that can be used with create-react-app
https://github.com/facebook/create-react-app

**ReactJS** : Refer to https://reactjs.org/ to understand the concepts of ReactJS

**React Bootstrap** : Refer to https://react-bootstrap.github.io/getting-started/introduction/ to understand how to use React Bootstrap
