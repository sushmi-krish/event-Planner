# Conference Expense Planner

A React + Redux Toolkit application that helps users price conference events easily by selecting rooms, add-ons, and meals with real-time cost updates.

-----
# Features
- Dynamic UI that updates instantly based on user selections
- Components for venue selection, add-ons, and meal options
- State management with Redux Toolkit and slices
- Display of selected items with quantities, unit costs, and total costs
- Subtotal and total cost calculations
- Responsive and user-friendly design
----
#Tech Stack
 - React
 - Redux Toolkit
 - Vite
 - GitHub Pages (for deployment)
-----
# Setup & Usage

1. Clone the Repository
   ```bash
   git clone https://github.com/sushmi-krish/event-Planner.git
   cd event-Planner
   ```
2. Install Dependencies
   ```bash
   npm install
   ```
3. Run Locally in Development Mode
   ```bash
   npm run dev
   ```
   Open http://localhost:3000 to view it in the browser.
---
# Build & Deploy to GitHub Pages
1. Install gh-pages
```bash
npm install --save-dev gh-pages
```
2. Add/Confirm these entries in your package.json
   ```bash
   {
  "homepage": "https://yourusername.github.io/your-repo-name",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist",
    // other scripts...
  }
}
```bash
3. Build and Deploy
```bash
npm run deploy
```

4. Access your live site at
   https://sushmi-krish.github.io/event-Planner/
----
# Learning Objectives
Create functional React components with composition
- Manage component and global state using React hooks and Redux Toolkit
- Dynamically render UI from data arrays
- Implement event handling and conditional rendering
- Calculate and display costs based on user selections
- Deploy a React application on GitHub Pages
