# Web Programming Project

A comprehensive room booking and management system with user authentication, admin and manager roles, and detailed feedback capabilities.

## Overview

This project is a web-based application built with PHP that allows users to book rooms, manage bookings, and provides administrative functions for user and room management. The system includes role-based access control, activity logging, and a detailed feedback system.

## Features

#### Authentication & User Management
- User login and verification system (`login.php`, `loginverify.php`)
- User profile management (`user-profile.php`, `update_profile.php`)
- Admin functions to add, delete, and search users
- Database configuration (`config.php`)

#### Room & Booking Management
- View available rooms (`availableRoom.php`)
- Create and manage bookings (`booking.php`, `submit_booking.php`)
- Modify existing bookings (`modifyBooking.php`)
- View user's booking history (`my_bookings.php`)
- Manager functions to add and delete rooms

#### Admin & Reporting
- Booking approval system (`approvals.php`)
- View booking reports and requests
- System activity logs tracking

#### Feedback System
- Detailed feedback functionality (`Feedback.html`)
- Comprehensive feedback system with data persistence


## Technology Stack

- **Backend**: PHP
- **Database**: MySQL/MariaDB
- **Frontend**: HTML, CSS, JavaScript
- **Version Control**: Git

## Getting Started

### Prerequisites

- PHP 7.4 or higher
- MySQL/MariaDB database
- Web server (Apache, Nginx, etc.)

### Installation

1. Clone the repository
```bash
git clone https://github.com/Chenxi0331/WebProgrammingProject.git
