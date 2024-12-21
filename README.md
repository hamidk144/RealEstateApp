# Real Estate Application Monorepo  

Welcome to the **Real Estate Application**, a modern, full-stack web application. This monorepo built with ReactJS, Zustand, Leaflet, Socket.io, ExpressJS, MongoDB, Prisma and JWT among other modern technologies.  

Key features include:  
- **Add Real Estate Listings**: Allow users to create new property listings with details like title, description, price, and location.  
- **View Real Estate Listings**: Display a list of all properties with filtering options and map integration for better exploration.  
- **Advanced Real Estate Search**: Search and explore real estate listings with integrated filtering and AMP support.  
- **Interactive Maps**: Visualize property locations on an interactive map using Leaflet and OpenStreetMap for detailed insights.  
- **Profile Management**: A dedicated profile page for users to manage their details and preferences.  
- **Chat and Notifications**: Real-time chat functionality and notification system to keep users informed and connected.  

---

## Features  

### Frontend (React)  
- **Dynamic and Responsive UI**: Built with React for seamless navigation.  
- **State Management**: Powered by Zustand for efficient and scalable state handling.  
- **Profile Page**: Manage user details and preferences.  
- **Real Estate Search**: Advanced filtering and AMP integration for optimal location visualization.  
- **Mapping**: Real estate locations displayed using Leaflet and OpenStreetMap.  
- **Notifications**: Integrated system for user alerts.  
- **Chat**: Real-time communication between users.  

### Backend (Express.js)  
- **API**: RESTful endpoints for listings, users, and transactions.  
- **Database**: MongoDB with Prisma as the ORM.  
- **Authentication**: Secured with JWT for user authorization.  
- **Sockets**: Real-time functionality enabled by Socket.io.  

---

## Tech Stack  

| Technology      | Purpose                       |  
|------------------|-------------------------------|  
| React           | Frontend UI framework         |  
| Zustand         | State management              |  
| Express.js      | Backend API framework         |  
| MongoDB         | Database                      |  
| Prisma          | ORM for database              |  
| JWT             | Authentication                |  
| Socket.io       | Real-time communication       |  
| Leaflet         | Interactive maps integration  |  
| OpenStreetMap   | Map data                      |  

---

## Installation  

### Prerequisites  
Ensure you have the following installed:  
- Node.js  
- npm or yarn  
- MongoDB  

### Setup  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/real-estate-app.git  
   cd real-estate-app  
2.	Install dependencies
Navigate to the root directory and install the necessary dependencies:
npm install  
# or  
yarn install 

3.	Set up environment variables
Create a .env file in both the frontend and backend directories. Below is an example for the backend:
CLIENT_URL=""
JWT_SECRET_KEY=""
DATABASE_URL=""

4.	Start MongoDB
Ensure MongoDB is running locally or use a cloud provider like MongoDB Atlas.
5.	Start the backend
Navigate to the backend directory and start the Express.js server:
npm run start

6.	Start the frontend
Navigate to the client directory and start the React app:
npm run dev
