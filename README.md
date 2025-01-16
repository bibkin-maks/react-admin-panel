# Project Overview
This is a React-based admin panel that provides you with the ability to:

- Easily edit your products
- View your orders
- Edit categories with ease
- View the users' database in a clear, organized way

This project relies on a backend server implemented with **Node.js** to handle file uploads and save changes. Without starting the server using the following command, the project will not function correctly as it depends on the API endpoints to process requests and store data (e.g., saving uploaded files).

## Requirements

- **Node.js**: Ensure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).

## Getting Started

1. Clone the repository:
    ```bash
    cd where you want the project to be at
    git clone https://github.com/bibkin-maks/react-admin-panel.git
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    node server.js
```
4. Run the panel:
    ```bash
    npm start
    ```

## How It Works
It will run the admin panel with a basic, functional interface.  
To view it, open `/products`.

You can edit products, save changes, and potentially integrate a database such as MySQL or others for storing data.

The project includes API endpoints to:

- Handle file uploads.
- Save changes to the data.

Without the server running, these endpoints will not be accessible, and the application will not be able to process requests properly.

## License

Include your project's license here.
