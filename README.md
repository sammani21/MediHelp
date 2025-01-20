# MediHelp

MediHelp is a comprehensive healthcare application designed to streamline medical services for patients, doctors, and administrators. The platform facilitates appointment scheduling, medical record management, and real-time communication between patients and healthcare providers.

## Features

- **User Authentication**: Secure login and registration for patients, doctors, and admins.
- **Appointment Management**: Easy scheduling and tracking of medical appointments.
- **Medical Records**: Centralized access to patients' medical histories.
- **Real-time Notifications**: Reminders for upcoming appointments and medication schedules.
- **Search Functionality**: Find doctors based on specialization, location, and availability.
- **Secure Communication**: Encrypted messaging between users and healthcare providers.

## Tech Stack

### Frontend:
- React.js
- Bootstrap
- CSS3

### Backend:
- Node.js
- Express.js

### Database:
- MongoDB

### Other Tools and Technologies:
- JWT for authentication
- Socket.IO for real-time communication
- Axios for API calls

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or above)
- [MongoDB](https://www.mongodb.com/)
- A code editor (e.g., VS Code)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sammani21/MediHelp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MediHelp
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Configure the environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     ```
5. Start the development server:
   ```bash
   npm start
   ```
6. Open your browser and navigate to `http://localhost:5000`.

## Usage

- **Patients**:
  - Register and log in to manage appointments.
  - Access medical records.
  - Communicate with healthcare providers.

- **Doctors**:
  - View and manage appointments.
  - Update patient records.
  - Communicate securely with patients.

- **Admins**:
  - Manage users and oversee platform activity.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add a new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please reach out to:
- **Author**: [Sammani21](https://github.com/sammani21)
- **Email**: [kavisamrajasooriya@gmail.com](mailto:kavisamrajasooriya@gmail.com)

---

Feel free to explore the repository, raise issues, or suggest improvements. Let's make healthcare accessible and efficient together!
