Setup Instructions

1. Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
2. Install dependencies
npm install
3. Start the development server
npm run dev

Git Origin Check / Change Origin:

-Check the current origin
git remote -v

-Set a new origin
git remote set-url origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

-Add origin if missing
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

-Push the project for the first time
git push -u origin main

Tech Stack Used:

-React.js — UI Component framework
-TypeScript — Type-safe JavaScript
-Vite — Fast build tooling
-Tailwind CSS — Utility-first styling
-Framer Motion — Smooth animations
-React Icons — Icon support

Key Features Implemented:
Multi-step Quiz Flow

-Next/previous buttons
-Submit button
-Custom progress bar

Animated UI:

-Page transition animations (Framer Motion)
-Animated paw illustration on question 1

Responsive Design:

-Looks clean on all screen sizes
-Gradient background
-Glassmorphism card UI

Result Page:

-Final percentage
-Restart button
-Clean, centered layout

Assumptions Made:

-The quiz always contains 5 questions.
-Each question has one correct answer.
-User must attempt all questions before seeing the results.
-The design should be matched as close as possible to the Figma provided.
-Uses client-side state only; no backend.

Time Spent on the Assignment:

Task                                       Time

Project setup (Vite + TS + Tailwind)	    50 min
Quiz logic (navigation, state mgmt)	      1 hr
UI + gradient + card layout	              2 hrs
Animations (Framer Motion)	              1 hr
Result page design	                      45 min
Bug fixes & polishing	                    35 min
Total Time Spent	                        ~6.5 hours

