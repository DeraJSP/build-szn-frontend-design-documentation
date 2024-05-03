# Frontend Design Documentation for Learnable Kids, a learning management system.

## Abstract

## Dashboard Design

## Profile pages

## Component tree diagram of the feature

## Alternative design considerations

## Technologies and Tools

-Visual Studio Code, Git, and npm will be used for development and version control.
-Reactjs will be used as the frontend framework for building reusable UI components
-Use State for some local state management and use reducer for global state management
-Use Context API for sharing state between components.
-Tailwind will be used for responsive design across all screens and UI components styling

### Frontend Architecture

The frontend will be built as a single-page application (SPA) using React, with a modular architecture to facilitate easy maintenance and updates. The application will be divided into features, each with its own set of components, containers, and APIs.

## Test scenarios

- Testing the user interface across different browsers (Chrome, Firefox, Safari, etc.)
- Verifying respionsiveness on different screen sizes
- Evaluating load times and performance under different network conditions
- Testing user acceptability with a prospective user

## Risk and security considerations

### Security

-Authentication will be done using a username and password
-Authorization will be a Role-based access control, restricted access to certain features and data will be implemented.
-Data Encryption: All data transmitted between the frontend and backend will be encrypted using HTTPS.
-Input Validation: The frontend will validate user input to prevent attacks.

### Risk Considerations

-Data Loss: Regular backups will be performed to prevent data loss in case of system failure.
-User Data Privacy: The system will comply with relevant data protection regulations.

## Accurate estimate of work and level of parallelization

- Tasks should be divided into smaller subtasks, with completion times estimated for each.
- Finding dependencies between activities to identify potential for parallelization
- Team size and availability of team members will be considered when estimating work
- Use of Kanban boards to visualize the timeline and parallelization of tasks

  ## Operations

  ## Testing
