# SnapVerse

**Monorepo for Snapverse: React website, React Native app, Node.js/Express backend, MongoDB database, with authentication, dashboard, profiles, CRUD, and contact form.**

A monorepo containing:
- **Web**: React website
- **App**: React Native mobile app
- **Server**: Node.js/Express API
- **Database**: MongoDB

## Features

- Authentication (JWT)
- Dashboard & Profile
- CRUD for Tasks
- Contact Form
- API integration

## Setup Instructions

### Prerequisites
- Node.js (v14 or later)
- npm (v6 or later) or yarn
- MongoDB (local or Atlas)
- Expo CLI (for mobile app)

### Folder Structure
```
snapverse/
  README.md
  LICENSE
  web/
  app/
  server/
  shared/
```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/veerp0099/snapverse.git
   cd snapverse
   ```

2. Install dependencies for each part of the application:
   - For the **web** app:
     ```bash
     cd web
     npm install
     ```
   - For the **app**:
     ```bash
     cd app
     npm install
     ```
   - For the **server**:
     ```bash
     cd server
     npm install
     ```

3. Run the applications:
   - For the **web** app:
     ```bash
     cd web
     npm start
     ```
   - For the **app**:
     ```bash
     cd app
     expo start
     ```
   - For the **server**:
     ```bash
     cd server
     npm start
     ```

## License

MIT
