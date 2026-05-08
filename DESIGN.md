# Clinical Spanish Web Application Design

## Overview

The application aims to teach clinical Spanish to medical professionals, focusing on verbal proficiency for patient interactions within a medical imaging environment. The curriculum will progress from fundamental phonetics and basic sentence structure to radiology-specific terminology.

## Modules

### 1. Fundamental Phonetics

- Introduction to Spanish alphabet and pronunciation
- Basic phonetic exercises

### 2. Basic Sentence Structure

- Introduction to basic sentence structures (e.g., greetings, introductions)
- Practice exercises for building sentences

### 3. Radiology-Specific Terminology

- Patient intake terminology
- Standardized breathing instructions
- Positioning commands
- Basic skeletal anatomy

## Technology Stack

- Frontend: React or Angular for the user interface
- Backend: Node.js with Express for server-side logic
- Database: MongoDB for storing vocabulary and curriculum data

## File Hierarchy

- `frontend/`
  - `components/`
  - `containers/`
  - `assets/`
- `backend/`
  - `models/`
  - `controllers/`
  - `routes/`
- `database/`
  - `vocabulary/`
  - `curriculum/`
- `README.md`
- `DESIGN.md`

## Logic Flow

1. User interacts with the frontend interface
2. Frontend sends requests to the backend server
3. Backend server processes requests and retrieves data from the database
4. Database stores and manages vocabulary and curriculum data
5. Backend server sends responses back to the frontend
6. Frontend updates the user interface based on the responses
