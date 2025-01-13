# TikFok App

A minimal setup for a short-video sharing app with:
- **Node.js/Express** backend (server folder)
- **React Native** client (client folder)

## Folder Structure
my-short-video-app/ ├── client/ │ ├── App.js │ └── package.json ├── server/ │ ├── index.js │ └── package.json ├── .gitignore └── README.md


### Getting Started

1. **Install Dependencies**  
   - In `server/`, run `npm install`
   - In `client/`, run `npm install`
2. **Run Server**  
   - `cd server && npm start`
3. **Run Client**  
   - `cd client && npm run android` (or `npm run ios`)

Adjust IP addresses in `App.js` to match your server’s URL or localhost if needed.
