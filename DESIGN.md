# DESIGN.md

## Introduction

This web application is designed to teach clinical Spanish from a baseline of zero knowledge, with the terminal objective of achieving verbal proficiency for patient interactions within a medical imaging environment.

## Curriculum Outline

The application will follow a progressive curriculum, starting with fundamental phonetics, basic sentence structure, and greetings. It will then pivot into radiology-specific terminology, covering required modules such as:

- Patient intake
- Standardized breathing instructions
- Positioning commands
- Basic skeletal anatomy

## File Structure

The codebase will be organized into the following modular structure:

- frontend/: User interface logic
- backend/: Backend logic
- database/: Vocabulary database
- public/: Static assets

## Technology Stack

- Frontend: React.js
- Backend: Node.js with Express.js
- Database: MongoDB
- Deployment: Docker containers with Kubernetes

## Logic Flow

1. User authentication and authorization
2. Curriculum progression tracking
3. Vocabulary practice and assessment
4. Radiology-specific terminology training
5. Patient interaction simulation

## Required Files and Directories

- frontend/
  - components/
    - containers/
      - actions/
        - reducers/
- backend/
  - api/
  - models/
    - controllers/
    * database/
      - vocabulary.js
- public/
  - index.html
  - styles.css

## Conclusion

This DESIGN.md file outlines the comprehensive plan for the web application, including the curriculum outline, file structure, technology stack, logic flow, and required files and directories. This will serve as a guide for the development of the application.
