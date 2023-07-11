# Redux Store

## Description

The Redux Store is a web application that modifies an e-commerce platform to use Redux for state management in a large-scale React application. This will bring industry-standard state management capabilities to the app, improving its efficiency and scalability.

  ## Table of Contents
  * [Technology Stack](#technology-stack)
  * [User Story](#user-story)
  * [Acceptance Criteria](#acceptance-criteria)
  * [Installation](#installation)
  * [Heroku Deployment](#heroku-deployment)
  * [Screenshot](#screenshot)
  * [Deployed Page](#deployed-page)
  * [License](#license)
  * [Questions](#questions)


## Technology Stack

![javascript](https://img.shields.io/badge/-JavaScript-61DAFB?color=yellow&style=flat)
![node](https://img.shields.io/badge/-Node.js-61DAFB?color=green&style=flat)
![express](https://img.shields.io/badge/-Express.js-61DAFB?color=blue&style=flat)
![mongodb](https://img.shields.io/badge/-MongoDB-61DAFB?color=purple&style=flat)
![redux](https://img.shields.io/badge/-React-61DAFB?color=red&style=flat)
![graphql](https://img.shields.io/badge/-GraphQL-61DAFB?color=red&style=flat)
![Apollo](https://img.shields.io/badge/-Apollo-61DAFB?color=red&style=flat)

## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global  
state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the  
Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global  
state
THEN I find that the app passes reducers to a Redux store  
instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Installation
  * Ensure you are running Node.js v16.  
  * Clone the repository.
  ```
    git clone git@github.com:erin-m-keller/keller-redux.git
  ```
  * Install the dependencies.
  ```bash
    npm i 
  ```
  * Seed the application.
  ```bash
    npm run seed
  ```
  * Start the application.
  ```md
    npm run develop
  ```
  > Application is available at: http://localhost:3000/  
  > GraphQL is available at: http://localhost:3001/graphql  
  > To test Stripe payment, use the fake credit card number 4242 4242 4242 4242

## Heroku Deployment

// TODO: Add link

## Screenshot

![shopShopScreenshot](./client/src/assets/images/finished-product.png)

## License

[![MIT license](https://img.shields.io/badge/License-MIT-purple.svg)](https://lbesson.mit-license.org/)

## Questions

If you have any questions about this project, please contact me directly at [aestheticartist@gmail.com](aestheticartist@gmail.com).  
You can view more of my projects [here](https://github.com/erin-m-keller).