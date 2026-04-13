# Modernized Angular-CRUD (v21)

A robust and modern CRUD (Create, Read, Update, Delete) system built with the **Angular** ecosystem and **Material Design**.

## Screenshots

<img src="https://user-images.githubusercontent.com/16153844/149670274-74a3222e-30cc-4aff-aca7-b287397baa53.jpg" width="600" height="400">
<img src="https://user-images.githubusercontent.com/16153844/149670276-a276bfff-1e38-4bce-bf2d-f5e8d1364917.jpg" width="600" height="400">
<img src="https://user-images.githubusercontent.com/16153844/149670277-0b221123-c41b-4316-9277-5fa06e65c5e1.jpg" width="600" height="400">

## 🚀 Technological Modernization

Originally developed in Angular 9, this project underwent a systematic infrastructure modernization process:

-   **Framework:** Upgraded from Angular 9.1 to **Angular 21.2**.
-   **TypeScript:** Updated to version **6.0.2**.
-   **Architecture:** Preservation of the **NgModule** structure (standalone: false) to ensure compatibility with legacy components without invasive refactoring.
-   **Environment:** Optimized for **Node.js v22.12.0**.

## 🏗️ Project Structure

-   **frontend/**: Angular application using Angular Material for a rich and responsive interface.
-   **backend/**: Fake API served by `json-server`, facilitating testing and rapid prototyping.

## 🛠️ Prerequisites

-   **Node.js**: v22.12.0 or higher.
-   **npm**: v10.x or higher.
-   **Angular CLI**: Installed locally via project dependencies.

## 🏃 How to Run

### 1. Prepare the Backend
Navigate to the backend folder and start the API server:
```bash
cd backend
npm install
npm start
```
The API will be available at `http://localhost:3001`.

### 2. Prepare the Frontend
In a new terminal, navigate to the frontend folder and start the application:
```bash
cd frontend
npm install
npm start
```
Access the application at `http://localhost:4200`.

## 🌳 Branch Management

For archiving and comparison purposes, the original state of the application (Angular 9) has been preserved in the following branch:
-   `angular-8-initial` (Original project baseline).

## 🧭 Improvement Roadmap
This project is under constant technical evolution, focusing on:
-   Strict typing correction and service refactoring.
-   Implementation of advanced form validations.
-   Addition of client-side filters and pagination.

---
*Developed with a focus on infrastructure modernization while maintaining 100% of the original visual identity.*
