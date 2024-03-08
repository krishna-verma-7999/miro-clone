## Getting Started

1. npx create-next-app@latest => initializing new project.
2. got to shadcn and install shadcn using => npx shadcn-ui@latest init
3. now "npm run dev"

# Database and backend setup

1. we are going to use convex for our database and backend setup.
2. install convex => npm install convex
3. setup convex => npx convex dev

# for authentication

- we are using clerk. go to clerk and create your account and create new application.
- npm install @clerk/nextjs
- create middleware file following clerk documentation
- create jwt template from clerk following convex docs
- copy issue link from clerk generative template and create auth.config.js file inside convex folder

# Sidebar

- go to the clerk website and go to jwt template and create two new keys first is organization_id and organization_role
- for dialog component we are going to install new component that is dialog and also install tooltip component.
- go to clerk and dashboard and then customize avatar logo.
