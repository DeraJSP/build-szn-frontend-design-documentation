# Learnable Kids: A Learning Management System.

## Introduction
Learnable Kids is a learning management system (LMS) tailored specifically for children aged 5 to 12. Traditional learning materials often fail to captivate young minds, leading to disengagement and lack of motivation. Learnable kids will unleash your child's curiosity with a world of games, quizzes, and challenges that make learning exciting fostering a love for learning among children while providing progress tracking tools to parents you stay involved.

## Profile pages
- Profile page for parents and teachers containing names, contact info, email, payment details and account setting for accessing and changing password and email, feedbacks and privacy policy by CRUD operations enabled by react component with backend API integration for real time data update.
  
## Dashboard
- dashboard for performance metric tracked by parents to monitor child progress's, assignment quizzes with data visualization library.
- dashboard for kids to access their assignment, quizzes games, tasks done with statemanagemet tools.

## Component tree diagram
![model](https://raw.githubusercontent.com/DeraJSP/build-szn-frontend-design-documentation/main/component-tree.png)

## Alternative design considerations

- animated storyboard used to tell stories while enabling learning
- voice activated navigations
- integrate Q&A widget or chatbots
- avater based learning adventure
- features for parents to engage in fun activities with kids to enable learning.
- [more alternative design decision will be influenced by user feedback]

## Technologies and Tools

- Visual Studio Code, Git, and npm will be used for development and version control.
- Reactjs will be used as the frontend framework for building reusable UI components
- React router wil be used to move and navigate around pages
- Use State for some local state management and use reducer for global state management
- Use Context API for sharing state between components.
- Tailwind will be used for responsive design across all screens and UI components styling

## Frontend Architecture

The frontend will be built as a single-page application (SPA) using React, with a modular architecture to facilitate easy maintenance and updates. The application will be divided into features, each with its own set of components, containers, and APIs.

## Test scenarios

- Testing the user interface across different browsers (Chrome, Firefox, Safari, etc.)
- Verifying respionsiveness on different screen sizes
- Evaluating load times and performance under different network conditions
- Testing user acceptability with a prospective user

## Risk and security considerations

### Security

- Authentication will be done using a username and password
- Authorization will be a Role-based access control, restricted access to certain features and data will be implemented.
- Data Encryption: All data transmitted between the frontend and backend will be encrypted using HTTPS.
- Input Validation: The frontend will validate user input to prevent attacks.

### Risk Considerations

- Data Loss: Regular backups will be performed to prevent data loss in case of system failure.
- User Data Privacy: The system will comply with relevant data protection regulations.

## Accurate estimate of work and level of parallelization

- Tasks should be divided into smaller subtasks, with completion times estimated for each.
- Finding dependencies between activities to identify potential for parallelization
- Team size and availability of team members will be considered when estimating work
- Use of Kanban boards to visualize the timeline and parallelization of tasks

## Operations

- Ensuring scalability for handling a high volume of concurrent users and optimizing frontend code for quick loading and seamless user experience.
- Incorporating essential APIs and server logic into React components for managing user authentication, course enrollment, and progress tracking.
- Using Git for version control and management tools to perform maintenance, regular updates, and bug fixes.
  
## Testing
  
 ### Unit Testing:
  
  - Using React components to ensure individual functionalities work.
  - Jest and React Testing Library for automation.
    
 ### Integration Testing:

  - To ensure smooth interaction between frontend components and also various scenarios covering user interactions.
  
 ### End-to-End Testing:
 This tests will simulate real user interactions with the platform, including navigation, form submissions, and data validation.
 
 ### Cross-Browser Testing:
  
  - To verify platform functionality across browsers.
  - Testing on Chrome, Firefox, Safari, and Edge.
    Regression Testing:
  - Ensures new updates don’t introduce issues.

## Click Interaction Structure/User flow
![model](https://raw.githubusercontent.com/DeraJSP/build-szn-frontend-design-documentation/main/click-interaction-user-flow.png)
