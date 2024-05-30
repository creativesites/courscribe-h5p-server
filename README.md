# Courscribe H5P Server

## Overview

Courscribe H5P Server is a powerful backend solution designed to facilitate the creation, storage, and management of interactive H5P content. This server component enables seamless integration with various front-end platforms, providing a robust environment for educators and content creators to enhance learning experiences with interactive media.

## Features

- **Interactive Content Management**: Easily manage H5P content types and instances.
- **API Integration**: RESTful API endpoints for seamless integration with front-end applications.
- **Scalable Architecture**: Built to handle high volumes of content and user interactions.
- **User Authentication**: Secure access control and user management.
- **Data Storage**: Efficient storage solutions for H5P content, supporting various database systems.

## Technology Stack

- **Backend**: Node.js, Express
- **Database**: MongoDB (or any compatible database)
- **Authentication**: JSON Web Tokens (JWT)
- **API Documentation**: Swagger
- **Scripting**: Bash for setup and maintenance scripts

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

- Node.js (v14.x or higher)
- npm (v6.x or higher) or Yarn (v1.x or higher)
- MongoDB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/creativesites/courscribe-h5p-server.git
    cd courscribe-h5p-server
    ```

2. Install dependencies:

    Using npm:
    ```bash
    npm install
    ```

    Using Yarn:
    ```bash
    yarn install
    ```

3. Set up environment variables:

    Create a `.env` file in the root directory and add the following variables:
    ```env
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Run the development server:

    Using npm:
    ```bash
    npm run dev
    ```

    Using Yarn:
    ```bash
    yarn dev
    ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to access the server.

## Building for Production

To create an optimized production build, run:

Using npm:
```bash
npm run build
```

Using Yarn:
```bash
yarn build
```

## Starting the Production Server

After building the project, you can start the production server with:

Using npm:
```bash
npm start
```

Using Yarn:
```bash
yarn start
```

## API Documentation

The API endpoints are documented using Swagger. After running the development server, you can access the documentation at [http://localhost:3000/api-docs](http://localhost:3000/api-docs).

## Contributing

We welcome contributions from the community. If you have any ideas, suggestions, or bug reports, please create an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
