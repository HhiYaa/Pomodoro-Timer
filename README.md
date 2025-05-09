/**
 * Pomodoro Timer Web App – Detailed Description
 *
 * This full-stack application provides a productivity tool that helps users manage work and break intervals using the Pomodoro technique. It allows starting, pausing, and resetting a customizable timer, and logs each completed session with timestamps for tracking purposes.
 *
 * Key Features:
 * - Frontend (React):
 *   - Interactive timer with Start, Pause, and Reset buttons.
 *   - Visual session switch between Work and Break modes.
 *   - Real-time countdown display.
 *   - History page showing all past sessions with timestamps.
 *
 * - Backend (Node.js + Express):
 *   - REST API with endpoints to log sessions and retrieve history.
 *   - In-memory storage (can be upgraded to persistent DB like MongoDB).
 *
 * How to Run Locally:
 * 1️. Frontend:
 *    - cd to the React app folder
 *    - Run `npm install` and `npm start` (default: localhost:3000)
 *
 * 2️. Backend:
 *    - cd to server folder
 *    - Run `npm install` and `node index.js` (default: localhost:5000)
 *
 * 3.  Proxy Setup:
 *    - In frontend/package.json, add: "proxy": "http://localhost:5000"
 *
 * Deployment Ideas:
 * - Frontend: Deploy to Netlify, Vercel, or AWS Amplify.
 * - Backend: Deploy to Heroku, Railway, or AWS Lambda (via serverless framework).
 *
 * Future Enhancements:
 * - User authentication and personalized session tracking.
 * - Persistent database integration (MongoDB/DynamoDB).
 * - Statistics dashboard with charts and productivity insights.
 * - Audio notifications and customizable session lengths.
 */
