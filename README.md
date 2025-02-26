# DatingApp

DatingApp is a modern web application built with Angular and ASP.NET Core, designed to connect users through a seamless and interactive dating experience. The platform allows users to create profiles, upload photos, and interact with potential matches.

## Features

- **User Authentication**: Secure login and registration with JWT-based authentication.  
- **Profile Management**: Users can create and update their profiles with personal details and photos.  
- **Matchmaking System**: The app suggests potential matches based on user preferences.  
- **Real-time Messaging**: Integrated chat functionality allows users to communicate instantly.  
- **Photo Upload & Moderation**: Users can upload images, with an admin panel for content moderation.  
- **Advanced Search & Filtering**: Users can filter potential matches based on location, age, and other criteria.  
- **Responsive Design**: A mobile-friendly interface ensures a smooth experience across devices.  

## Technologies Used

- **Frontend**: Angular, TypeScript, Bootstrap
- **Backend**: ASP.NET Core, C#
- **Database**: SQL Server
- **Authentication**: JWT (JSON Web Token)

## Getting Started

### Prerequisites
- Node.js and npm installed
- .NET SDK installed
- SQL Server running

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/94mohabd/DatingApp.git
   ```
2. Navigate to the project directory:
   ```sh
   cd DatingApp
   ```
3. Install frontend dependencies:
   ```sh
   cd ClientApp
   npm install
   ```
4. Set up the backend:
   - Configure database connection in `appsettings.json`
   - Apply migrations and update the database:
     ```sh
     dotnet ef database update
     ```
5. Run the backend:
   ```sh
   dotnet run
   ```
6. Run the frontend:
   ```sh
   cd ClientApp
   ng serve
   ```
7. Open the app in your browser at `http://localhost:4200/`
