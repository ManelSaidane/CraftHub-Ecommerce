CraftHub
Overview
CraftHub is an innovative e-commerce platform tailored for artisans to sell unique handmade products (e.g., pottery, jewelry, textiles, woodworking) and offer creative workshops (online or in-person). It addresses the challenge faced by artisans struggling to digitize their businesses by providing a specialized marketplace with a subscription-based model for artisans. CraftHub integrates AI-driven features to enhance user experience, streamline content management, and boost sales efficiency.
Project Goal
This repository hosts the Minimum Viable Product (MVP) for CraftHub, developed solo within a one-month timeframe. The MVP focuses on core e-commerce functionalities and simplified AI modules to deliver a functional platform for customers, artisans, and administrators.
Key Features (MVP)

Customers: Browse products by category/region, purchase via secure payment (Stripe), manage accounts.
Artisans: Create shop profiles, add products/workshops, track sales/inventory.
Administrators: Manage subscriptions, moderate products.
AI Modules:
Content-based product recommendations (by category).
Basic image validation (resolution/clarity checks).



Tech Stack

Backend: Node.js + Express (REST API).
Frontend: React (Create React App).
Database: SQLite (Sequelize ORM).
Payment: Stripe API.
AI: JavaScript-based recommendations (cosine similarity), Sharp.js for image validation.
Deployment: Vercel (free, seamless hosting).

Getting Started

Clone the repo: git clone <repo-url>
Backend setup: cd server && npm install
Frontend setup: cd client && npm install
Configure environment variables (e.g., Stripe API key).
Run backend: npm start (port 3000).
Run frontend: cd client && npm start (port 3000).
Set up SQLite in server/models.

Project Timeline

Week 1: Project setup, user/product models, basic API (register/login).
Week 2: Product browsing, shop management, Stripe integration.
Week 3: AI modules (recommendations, image validation).
Week 4: UI polishing, testing, Vercel deployment.

Contributing
This is a solo project. Feedback is welcome—contact the maintainer for suggestions.
License
MIT License.
