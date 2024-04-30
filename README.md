# Hotel Booking Website

Welcome to the Hotel Booking Website repository! This project is a full-stack web application developed using MongoDB, ExpressJS, ReactJS, NodeJS, JWT, Cookies, Context API, Custom Hooks, React Calendar, Cloudinary, Material-UI, and Postman. The aim of this project is to provide a seamless experience for users to browse, search, and book hotels.

## Features

- **User Authentication**: Users can register and login securely using JWT tokens and Cookies.
- **Hotel Management**: Admins can create, update, and delete hotel details including images, room numbers, and other relevant information.
- **Room Management**: Admins can add and delete rooms for each hotel, ensuring accurate availability.
- **Availability Management**: Admins can mark certain dates as unavailable for booking in a hotel.
- **Search and Filter**: Users can search for hotels based on location and filter results based on booking date, number of adults, rooms, and children.
- **Booking System**: Once a room is booked, it becomes unavailable for the specified period, ensuring no double bookings.
- **Admin Dashboard**: Provides graphical representations and statistics regarding user, hotel, and room data.
- **Cloudinary Integration**: Images for hotels and users are uploaded to Cloudinary for efficient storage.

## Technologies Used

- **Frontend**: ReactJS, Context API, Custom Hooks, Material-UI, React Calendar
- **Backend**: NodeJS, ExpressJS
- **Database**: MongoDB
- **Authentication**: JWT, Cookies
- **Image Storage**: Cloudinary

## Installation

1. Clone the repository:

```bash
git clone https://github.com/amitesh197/Hotel_Booking_Website.git
```

2. Install dependencies:

```bash
npm install
npm init -y
```

3. Set up environment variables:

Create a `.env` file in the api directory and add the following:

```plaintext
MONGO = your_mongodb_uri
JWT = your_jwt_secret
```

4. Start the api server:

```bash
cd api
yarn
yarn start
```

5. Start the client server:

```bash
cd client
yarn
yarn start
```

6. Start the Admin Dashboard server:

```bash
cd admin
yarn
yarn start
```

## Usage

- Visit the website and register/login to access the available features.
- Explore hotels, search for specific locations, and use filters to narrow down options.
- Book a room by selecting the desired dates and number of guests.
- Admins can access the admin panel to manage users, hotels, and rooms.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.
