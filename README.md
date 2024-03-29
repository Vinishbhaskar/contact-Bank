# Contact Bank

Contact Bank is a simple web application that allows users to manage their contacts. It provides basic CRUD (Create, Read, Update, Delete) functionality for contacts, allowing users to add, view, edit, and delete contacts in their contact list.

## Features

- Add new contacts with details such as name, phone number, email, etc.
- View a list of all contacts with their details.
- Edit existing contacts to update their information.
- Delete contacts from the contact list.
- Search for contacts by name, phone number, or email.
- Responsive design for optimal use on desktop and mobile devices.

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Deployment: Render

## Installation

To run Contact Bank locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Vinishbhaskar/contact-Bank.git
```

2. Install the dependencies for the server and client:
```
cd contact-Bank
npm install
cd client
npm install
```

3. Create a .env file in the root of the project and set the following environment variables:

```
MONGODB_URI=<your_mongodb_uri>
SESSION_SECRET=<your_session_secret>
```

4. Start the development server:
```
npm run dev
```

5. Open your web browser and go to http://localhost:3000 to view the Contact Bank application.

## Contributing

If you would like to contribute to Contact Bank, please fork the repository and submit a pull request with your changes. You can also report any issues or bugs by creating an issue in the repository.
