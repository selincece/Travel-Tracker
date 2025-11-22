# Travel Tracker 🌍

A multi-user web application that allows family members to track and visualize countries they've visited. Built with Node.js, Express.js, EJS templating, and PostgreSQL database. Each family member has a unique profile color to display their travels on an interactive world map.

## Features

- **Multi-User Support**: Create and manage multiple family member profiles
- **Interactive World Map**: Visualize visited countries with color-coded user profiles
- **Country Search**: Add countries by name with intelligent search functionality
- **User Management**: 
  - Add new family members with custom colors
  - Switch between different user profiles
- **Persistent Storage**: PostgreSQL database for reliable data storage
- **Responsive Design**: Clean, modern interface that works across devices

## Technologies Used 

- Node.js with Express.js
- EJS templating engine
- PostgreSQL
- CSS


## Installation

1. Clone the repository:
```bash
git clone https://github.com/selincece/Travel-Tracker.git
cd Travel-Tracker
```

2. Install dependencies:
```bash
npm install
```


3. Start the application:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Usage

### Adding Countries
1. Select a user from the dropdown or create a new one
2. Type a country name in the input field
3. Click "Add" to mark the country as visited
4. The country will appear highlighted on the map in the user's color

### Managing Users
- **Switch Users**: Use the dropdown menu to switch between existing users
- **Add New User**: Click "Add Family Member" to create a new profile with a custom color

### Viewing Statistics
- See the total number of countries visited by the current user
- Visual representation on the world map with color-coding per user



