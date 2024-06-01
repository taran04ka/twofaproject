# Project Overview

This project consists of three nested submodules that together create a comprehensive system for account management with two-factor authentication (2FA). The project is divided into the following components:

## Submodules

### 1. Rails App (Account Management with 2FA)
https://github.com/taran04ka/twofaapp.git
This is a Ruby on Rails application that provides a full-featured web interface for managing user accounts. It includes functionalities for creating accounts, logging in, and enabling two-factor authentication (2FA). Users can secure their accounts using 2FA during the login process.

**Key Features:**
- Account creation
- User login
- Two-factor authentication (2FA) setup and verification
- Web interface for all user interactions

### 2. Rails API App
https://github.com/taran04ka/twofaapiapp.git
This submodule is a Ruby on Rails application that provides the same functionalities as the first submodule but through a RESTful API. It is designed to be used as a backend service with no user interface.

**Key Features:**
- Account creation via API
- User login via API
- Two-factor authentication (2FA) setup and verification via API
- RESTful endpoints for all functionalities

### 3. JavaScript App (Frontend for Rails API)
https://github.com/taran04ka/twofaapijs.git
This is a JavaScript-based frontend application that interacts with the Rails API App. It serves as the user interface for the API, allowing users to manage their accounts and perform all necessary actions through a web-based client.

**Key Features:**
- User-friendly interface for account management
- API integration for user actions (create account, login, enable 2FA)
- Seamless communication with the Rails API App

## Getting Started

### Prerequisites
- Ruby on Rails installed
- A web server to serve the JavaScript and HTML files (e.g., Apache, Nginx)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/taran04ka/twofaproject.git
   cd twofaproject

2. **Clone submodule repositories**
   ```bash
   git clone https://github.com/taran04ka/twofaapp.git twofaapp
   git clone https://github.com/taran04ka/twofaapiapp.git twofaapiapp
   git clone https://github.com/taran04ka/twofaapijs.git twofaapijs
3. **Check further actions in submodule repositories descriptions**
