# FinMaster

**FinMaster** is a financial data API service that provides users with access to real-time market data through a user-friendly interface. The API enforces rate limiting to ensure fair access to all users, offering both non-pro and pro user tiers.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [API Endpoints](#api-endpoints)
- [Rate Limiting](#rate-limiting)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Registration and Authentication**: Users can create accounts and authenticate using their credentials.
- **Rate Limiting**: Non-pro users can make a maximum of 6 requests per minute, while pro users enjoy unlimited access.
- **Data Proxying**: Retrieves financial data from Alpha Vantage and returns it to the user.
- **Secure API Keys**: Each user is assigned a unique API key for authentication.

## Technologies
- **Backend**: Go (Golang)
- **Database**: PostgreSQL
- **Web Framework**: Gorilla Mux
- **API Integration**: Alpha Vantage API

## Rate Limiting
- Non-pro users: 6 requests per minute.
- Pro users: Unlimited requests.

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/FinMaster.git
    cd FinMaster
    ```
2. Install the required dependencies.
3. Set up your PostgreSQL database.
4. Configure environment variables for API keys and database connection.

## Usage
To use the API, authenticate using your API key and make requests to the endpoints as documented.

## Contributing
We welcome contributions to FinMaster! For guidelines on how to contribute, please check the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

## License
This project is licensed under the MIT License.
