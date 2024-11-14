# Barakah Home Services : a mobile app to connect home service providers and homeowners. 
## Software Planning and Technical Documentation
## Define the scope and features
- User Profiles: Separate profiles- services providers (workers) and customers (homeowners).
- Service Listings: Categories for various services (cleaning, plumbing, electrical, HVAC, landscaping, pest control, home security system, roofing services, etc.).
- Search & Filters: Customers can search for services and filters the service provider by price, ratings, etc.).
- Reservation Systems: Customers can reserve services with ease. 
- Payment Gateway: Customers can select from available secure online payment integration (credit/debit cards, online banking, Tngo, shopee pay, etc.).
- Ratings & Reviews: Customers can leave review and rate the service providers. 
- Chat/Communications: In-app messaging or calling feature for service providers and customers.
- Notifications: Alerts for reservation confirmation, reminders, promotions, etc.
- GPS & Location Services: Real-time location tracking of service providers.
- Admin Panel: For managing users, services, payments and overall app monitoring. 
- Scheduling for Service Provider availability : Allow service providers to set their working hours, mark themselves available/ unavailable on certain days or whenever they want . 
## business requirement document 
## tech-stack suggestions
## Project-Root: top level folder contains all the source file for a project
## process flowchart 
![image.png] (home services process flowchart.png)
## process flow
![image.png] (home services process flow.png)
## Folder Structure
```bash
/Barakah cleaning services
│
├── /backend
│   ├── /controllers
│   ├──  └── translateController.js
│   ├── /models
│   │    └── (add your mongoose models here)
│   │   /routes
│   │    └──  translateRoutes.js
│   ├── /utils
│   │   ├── errorHandler.js (function to handle and display error message gracefully)
│   │   ├── logger.js
│   │   ├── translateRoutes.js
│   │   ├── validators.js
│   ├── .env
│   ├── server.js
│   ├── package.json
│   ├── READ.md
│
├── /frontend
│   ├── /assets
│   │    └── (images, fonts, icons etc.)
│   ├── /components
│        └── reusable UI components (buttons, input fields, modals)
│   ├── /navigation
│   │    └── (React Navigation setup)
│   ├── /screens
│   │    └── translateScreen.js (UI to input text, selecting languages, translate output)
│   ├── /services
│   │    └── api.js
│   │    └── translateServices.js
│   ├── /utils
│   │    └── errorHandler.js (function to handle and display error message gracefully)
│   ├── /App.js
│   ├── package.json
│   ├── babel.config.js (dependacies, metadata, scripts: axios, react)
│   ├── READ.md
│
├── .gitignore
├── READ.md
└── LICENSE (if required)
```

## Details of each directory

### Backend
- `/controllers`: Contains your controller files, which handle incoming HTTP requests and business logic.   
- `/models`: Contains Moongoose models if you using MongoDB or any other Object role modelling models. 
- `/routes`: Contains route definitions that map URL paths to controller actions. 
- `/utils`: Utility functions (error handling, logging, translation service).
- `/.env`: Environment variables for your backend, (API keys, database connection strings, etc.).
- `server.js`: Entry point of your node.js application.
- `/package.json`: Lists backened dependacies and scripts.

### Frontend
- `/assets`: Contains static assets (images, fonts).
- `/components`: Reusable UI components to be used across multiple screen.
- `/navigations`: Navigation configuration using React Navigation.
- `/screens`: Individual screen components, each representing a different part of UI.
- `/services`: Contains services for making API interaction, interacting with the backend.
- `/utils`: Utility functions managing error handling, logginand translation service.
- `App.js`: Entry point of the React Native app.
- `babel.config.js`: Babel configuration for React Native.
- `package.json`: Lists frontend dependencies and scripts.


# release plan.md
# architecture.md

# api docs.md
# README.md  # Project overview, instructions, and key links
# src  
# Your source code
