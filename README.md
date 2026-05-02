## Assignment Workflow System

## Project Overview
Backend system to manage assignments, submissions, and deadlines.  
Supports assignment lifecycle (active/closed), submission tracking, and deadline validation using REST APIs

## Setup Instructions
npm install
npx nodemon server.js

## API Endpoints
POST /assignments
GET /assignments
GET /assignments/:id
POST /assignments/:id/submit
GET /assignments/:id/submissions
