# Reminiscia - A User-Friendly Social Media Platform

Welcome to Reminiscia, a user-friendly social media platform allowing users to share multimedia content, accompanied by captions and hashtags. This platform fosters engagement by enabling users to follow and contribute to trending topics across various domains. Notably, it also gives users the unique ability to edit their posts as often as possible, even after they have been published, ensuring a dynamic and interactive experience for the community.
## Tech Stack

- **Frontend**:
  - ReactJS for building the user interface.
  - Tailwind CSS for styling the application.
  - Vite for fast development and building.

- **Backend**:
  - ExpressJS as the server framework.
  - Node.js for server-side JavaScript.
  - MongoDB as the database for storing user data and posts.

## Features

- Share multimedia content with captions and hashtags.
- Follow and engage with trending topics across various domains.
- Edit posts multiple times even after they have been published.
- User authentication and registration.
- Store user-specific data in MongoDB.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sarthak-Seth/Reminiscia.git
2. Navigate to the project directory:
```
cd Reminiscia
```
4. Install dependencies for both the frontend and backend:
```
cd client && npm install
cd ../server && npm install
```
4. Set up your environment variables:
Create a .env file in the server directory and configure it with the following variables:
```
PORT=3001
MONGODB_URI=your-mongodb-connection-string
```
5. Start the development servers:
In the server directory:
```
npm run dev
```
6. Your application should now be running on http://localhost:3000.
   ## Usage

1. Register or log in to your account.
2. Share multimedia content with captions and hashtags.
3. Follow and engage with trending topics.
4. Edit your posts as many times as you like.
5. Explore a dynamic and interactive social media experience.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m "Add your feature description"`.
4. Push to your forked repository: `git push origin feature/your-feature-name`.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Special thanks to the contributors who have helped make Reminiscia better!
- UI styling was made more accessible with Tailwind CSS.

## Contact

If you have any questions or feedback, feel free to contact the project creator:

- GitHub: Sarthak-Seth
Enjoy using Reminiscia!
