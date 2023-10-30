# ModuloChat Frontend - React

This repo contains the React frontend implementation for ModuloChat.

## Overview

The React frontend provides a responsive web chat interface using React and Material UI.

Key features:

- Real-time messaging in chat rooms
- Synced read receipts
- React Hooks for state management
- User registration and authentication
- Interoperability with other ModuloChat frontends  

## Getting Started

Requirements:

- Node.js 14+
- npm / yarn

```
# Clone the repo
git clone https://github.com/modulochat/frontend-react

# Install dependencies
yarn install

# Start dev server
yarn start
```

The app will be running on http://localhost:3000

## Architecture

The app is built using: 

- Create React App
- React Router for routing
- React Query for data fetching
- Material UI for components
- Socket.io for real-time messaging


## Testing

Testing is done with Jest and React Testing Library. Run tests with:

```
yarn test
```
