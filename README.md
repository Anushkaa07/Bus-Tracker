#  Bus Tracker

A real-time bus tracking application that enables live location sharing and monitoring of buses using WebSockets and Leaflet maps.

## Features

 **Real-time Location Tracking**
- Live GPS location updates using WebSockets
- Multiple buses can share their locations simultaneously
- Instant location broadcasting to all connected users

 **Interactive Maps**
- Leaflet. js for map visualization
- Moving markers to display bus positions
- Real-time marker updates as buses move

 **Live Communication**
- Socket.IO for bidirectional real-time communication
- Instant notifications when buses connect/disconnect
- Location sharing confirmations

 **User-Friendly Interface**
- EJS templating for dynamic HTML rendering
- Responsive design for various devices
- Clean and intuitive UI

## Tech Stack

- **Backend**:  [Express.js](https://expressjs.com/)
- **Real-time Communication**: [Socket.IO](https://socket.io/)
- **Frontend**: HTML, CSS, JavaScript
- **Templating**: [EJS](https://ejs.co/)
- **Maps**: [Leaflet.js](https://leafletjs.com/) with [Leaflet Moving Marker](https://github.com/ewoutkout/leaflet-moving-marker)

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm (comes with Node.js)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anushkaa07/Bus-Tracker.git
   cd Bus-Tracker
