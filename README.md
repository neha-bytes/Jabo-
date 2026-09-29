# JABO – Online Bus Ticket Booking and Shuttle Service System

## Live Application
Live Demo: https://jabo.vercel.app/

## Note on Hosting and Initial Load Time

This application is hosted using the free-tier services of Render (backend) and Vercel (frontend).  
As a result, if the server has been inactive for a period of time, the first request may experience a short delay while the backend service wakes up. Subsequent requests will load normally once the server is active.


## Project Overview

JABO is a full-stack web-based bus ticket booking and shuttle service system designed to digitalize and simplify the traditional travel booking process. The platform allows users to search bus routes, select seats, track shuttles in real time, and request local shuttle services.

The system eliminates the need for physical ticket counters, phone-based confirmations, and manual seat availability checks by providing a centralized, reliable, and user-friendly solution.

This project was fully designed, developed, and implemented independently by the author.

## Objectives

- Digitalize the bus ticket booking process
- Enable real-time shuttle tracking
- Support local shuttle service requests
- Ensure scalability, security, and data integrity

## Target Users

- General users and passengers
- Drivers
- System administrators

## Functional Features

### User Features

- User registration and authentication 
- User dashboard and profile management
- Bus route search by date, origin, and destination
- Display of available buses with schedule, fare, and seat layout
- Interactive seat selection with real-time availability
- Booking confirmation and booking summary
- Fake payment simulaiton 
- Automatic email confirmation after successful payment
- Booking history for past and upcoming trips
- Real-time shuttle tracking
- Local shuttle service requests (car, bike, microbus)
- Automatic fare calculation based on distance
- PDF ticket generation and download
- Trip notifications and status updates
- Driver rating and trip feedback system

### Driver Features

- Driver dashboard
- View assigned trips and shuttle requests
- Accept or reject ride requests
- Update ride status (On the way, Arrived, Completed)

### Admin Features

- Administrative dashboard with system analytics
- Bus, route, and schedule management
- User and driver account approval and management
- Monitoring of bookings, payments, and system activity

## Technology Stack

- MongoDB – Data storage for users, bookings, payments, and rides
- Express.js – RESTful API and backend business logic
- React.js – Frontend user interface
- Node.js – Server-side runtime environment

## Installation and Setup

### Prerequisites
- Node.js
- MongoDB
- npm

### Steps

```bash
git clone https://github.com/yourusername/jabo.git
cd jabo
npm install
npm run server
npm start
```

## Future Enhancements

- Mobile application version
- Advanced analytics for administrators
- Multiple payment gateway integration
- Push notification support
- Multi-language support

## Author

Md. Imam Hasan  
CSE, BRAC University
