# AI FitTrack API — AI-ML and GEN-AI Track Project Deliverables

## Project Overview
AI FitTrack API is a robust Generative AI-powered fitness tracking and recommendation backend REST API service built with Node.js, Express.js, MongoDB Atlas (Mongoose ODM), JWT Authentication, bcrypt, and the Google Gemini AI SDK (`@google/genai` v2.x). It enables users to securely authenticate, track and manage daily workouts across 6 distinct fitness categories, execute multi-criteria regex search queries by name, category, or date, and request personalized AI workout plans or fitness progress insights directly from Google Gemini AI.

---

## Project Team & Roles

| S.No | Team Member | Role | Core Contributions & Ideas |
|:---:|:---|:---|:---|
| 1 | **Madhanraj R K** | **Team Leader & Generative AI Architect** | End-to-end MVC backend architecture, Google Gemini 1.5 Flash SDK integration (`@google/genai`), prompt engineering for personalized workout plans (`generateWorkoutPlan`) and progress insights (`generateFitnessInsights`), sprint coordination and Naan Mudhalvan delivery oversight. |
| 2 | **Abishek M** | **Backend Engineer & Workout Engine Lead** | Workout CRUD management controller (`workoutController.js`), chronological date sorting, multi-criteria case-insensitive regex search engine (`GET /api/workouts/search?q=`), activity metric validation (duration, calories burned, category enum). |
| 3 | **Devanand R** | **Security Specialist & Auth Lead** | Cryptographic user authentication (`authController.js`), salted bcrypt password hashing (10 salt rounds), HMAC-SHA256 JWT access token issuance, centralized JWT Bearer authentication guard (`middleware/auth.js`), user data isolation. |
| 4 | **Kishore samuvel S** | **Database Engineer & Data Modeler** | MongoDB Atlas cloud cluster setup, Mongoose ODM schemas (`User.js` & `Workout.js`), relational foreign key referencing (`user: { type: ObjectId, ref: 'User' }`), database index optimization on `user` and `workoutDate`. |
| 5 | **Sunil kumar M** | **QA Automation, Performance & DevOps Lead** | Automated Postman collection test suite (`FitTrack.postman_collection.json`) covering all 10 endpoints with test scripts and token chaining, centralized error handling (`middleware/errorHandler.js`), Morgan request logging, load testing and latency benchmarking. |

---

## Deliverables Repository Structure

1. **1. Brainstorming & Ideation**
   - `Brainstorming & Idea Prioritization.pdf` (3 Marks)
   - `Define Problem Statements .pdf` (3 Marks)
   - `Empathy Map.pdf` (4 Marks)

2. **2. Requirement Analysis**
   - `Customer Journey Map.pdf` (2 Marks)
   - `Data Flow Diagram.pdf` (2 Marks)
   - `Solution Requirements.pdf` (4 Marks)
   - `Technology Stack.pdf` (2 Marks)

3. **3. Project Design Phase**
   - `Problem-Solution Fit.pdf` (5 Marks)
   - `Proposed Solution.pdf` (5 Marks)
   - `Solution Architecture.pdf` (5 Marks)

4. **4. Project Planning Phase**
   - `Project Planning.pdf` (5 Marks)

5. **5. Project Development Phase**
   - `Code-Layout, Readability and Reusability.pdf` (5 Marks)
   - `Coding & Solution.pdf` (5 Marks)
   - `No. of Functional Features Included in the Solution.pdf` (5 Marks)

6. **6.Project Testing**
   - `Performance Testing.pdf` (5 Marks)

7. **7.Project Documentation**
   - `Project Executable Files.pdf` (3 Marks)
   - `Sample Project Documentation.pdf` (Comprehensive 21-page report)

8. **8.Project Demonstration**
   - `Communication.pdf` (1 Mark)
   - `Demonstration of Proposed Features.pdf` (1 Mark)
   - `Project Demo Planning.pdf` (1 Mark)
   - `Scalability & Future Plan.pdf` (1 Mark)
   - `Team Involvement in Demonstration.pdf` (1 Mark)

All 22 project deliverables match the exact Naan Mudhalvan AI-ML & Gen AI Track template structure, with 100% verification.
