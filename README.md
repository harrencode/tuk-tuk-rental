# Tuk-Tuk Rental Application

## Description

The Tuk-Tuk Rental Application is a web-based platform that allows users to rent tuk-tuks for transportation. The application features a user-friendly interface built with React for the frontend and a robust backend developed using Ballerina. Users can view available tuk-tuks, make reservations, and manage their rentals seamlessly.

## Technologies Used

- **Frontend**: 
  - React
  - HTML
  - CSS

- **Backend**: 
  - Ballerina
  - MySQL

## Setup Instructions

### Prerequisites

- Node.js and npm (for React)
- Ballerina (for the backend)
- MySQL (for the database)

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/harrencode/tuk-tuk-rental.git
   cd tuk-tuk-rental/frontend

2. Install dependencies:
   ```bash
   npm install

3. Start the React application:
   ```bash
   npm start

### Backend Setup

1. Open a new terminal window and navigate to the backend directory:
   ```bash
   cd tuk-tuk-rental/backend

2. Pull the required dependencies:
   ```bash
   ballerina pull

3. Create the MySQL database and tables as defined in the project. You may need to run SQL scripts provided in the repository or create them manually.

4. Run the Ballerina application:
   ```bash
   ballerina run main.bal

# Tuk-Tuk Rental

## Usage
Open your browser and navigate to http://localhost:3000 for the frontend.
You can register or log in to access the tuk-tuk rental features.
Browse available tuk-tuks and make reservations as needed.

## API Endpoints
- **GET /api/tuktuks**: Retrieve a list of available tuk-tuks.
- **POST /api/rent**: Rent a tuk-tuk.
- **GET /api/users**: Retrieve user information.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
Thanks you all 😉