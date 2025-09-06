# Personalized Micro-Learning Engine
##  Problem Statement

Build a personalized, adaptive micro-learning platform for Python programming that improves learning outcomes with minimal learner fatigue.
## Solution

We have built a  personalized Python learning platform that uses Gemini 2.5 FLASH and Gemini 2.5 PRO to adaptively assess learner competence, generate a dynamic learning path, and deliver short, interactive micro-learning exercises with instant feedback.

## Target Users

Students (K–12, undergraduates, early learners)

Self-learners and professionals seeking quick skill upgrades

## Key Features

 Smart Topic Selection – Auto-chooses next module/topic based on current understanding of learner

 Micro-Learning Delivery – Bite-sized lessons optimized for quick understanding

 LLM-Powered Summarization – Uses Gemini 2.5 Flash for context-aware content delivery

 Adaptive Learning Path – Dynamically the course plan based on learner performance

 Quiz & Feedback Loop – Reinforces retention and tracks mastery

## Tech Stack

Backend: Python, FastAPI

AI/LLM: Gemini 2.5 Flash (Google GenAI SDK)

Frontend: HTML, CSS, JavaScript

Deployment: Vercel

## Business Model (B2C)

Freemium: Free access to basic modules of the course and premium subscription unlocks advanced modules

Premium Subscription: Unlocks unlimited access, progress analytics, and projects

Pay-per-course Model: One-time payment for a complete Python course with lifetime access

Add-ons: Certification modules and skill-assessment tests

## Pain Points Solved

Removes content overload

Reduces time wasted on irrelevant topics

Sustains learner motivation with bite-sized modules

Provides personalized adaptive learning instead of one-size-fits-all courses

## Installation & Usage

Clone this repo:

git clone https://github.com/harshmasalge/micro-learning-engine.git
cd micro-learning-engine


Create virtual environment & install dependencies:

python -m venv venv
source venv/bin/activate
pip install -r requirements.txt


Run backend server:

uvicorn backend.main:app --reload


Launch frontend:

cd frontend
npm install
npm start

📊 Future Scope

Support for multi-language content generation

Integration with voice-based learning assistants

Advanced AI-based learner analytics dashboards
