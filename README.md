# Softuni Retake Project

Design and impelemt a web application (Single Page Application) using React.js using a service liek Kinvey or Firebase for your
back-end or create your own with Node.js and MongoDB.

It can be a blog system, e-commerce sitye, online gaming site, social network, or any other web applicaiton.

## Application Structure

-   Public Part (Accessible without authentication)
-   Private Part (Available for Registered Users)

#### Public Part

Available without a login.

-   Start page
-   User Login
-   User Registration
-   Public data for the users (blog posts in a blog system, offers for a bid system etc.)

#### Private Part (User Area)

-   Profile management
-   User's offers in a bid system (bids in an offer system, posts in a blog system etc.)

## General Requirements

-   At least 3 different **dynamic pages**
-   Must have specific views:
    -   Catalog: list of all created records
    -   Details: information about a specific record
-   At least one collection different from user collection with CRUD operations

    -   Logged in users - create records and request to REST API, and interaction with the records.
    -   Logged in authors - can edit and delete their records.
    -   Guests have access to basic website information but not private information with functional abilitites

-   User ReactJS for client-side
-   Communicate with a remote service (REST)
-   Implement authentication
-   Implement client-side routing
-   Demonstrate use of programing concepts, specific to the React Library: stateless and state full components, bound forms, synthetic events, Component styling etc.
-   Use a source control system, like Github
-   Required to have commited in the last 3 days.

## Other Requirements

-   **Error handling** and **data validation** to avoid crashes when invalid data is entered.
-   Divide into components with separate CSS files
-   Brief ducmentation about the project and the project architecture in a .md file
-   Demonstrate use of programming concepts - React Hooks and Context API

## Public Project Defense

-   Demonstrate how the application works
-   Show the source code and explain how it works.
-   Answer questions

## Bonuses:

-   Use a state management solution (React Redux) instead of Context API
-   Write Unit Tests for your code
-   Good UI and UX
-   Use file storage cloud API Drop Box or Google Drive for storing files
-   Deploy the applicaiton in a cloud (Heroku, Firebase)

## Submission Deadline

13.12.2023
