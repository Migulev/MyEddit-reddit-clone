# MyEddit - A Simple Reddit Clone

MyEddit is a basic Reddit clone project built using modern technologies, aiming to provide users with a platform to share and discuss content on various topics.

## Features

- **Google Sign-In Authentication**: Users can sign in securely using their Google accounts.

- **Create and Vote on Posts**: Signed-in users can create new posts, upvote, or downvote existing posts using NextJS for the frontend and TanStack Query for data management.

- **Commenting**: Users can add comments to posts to engage in discussions.

- **User Settings**: Users have the option to change their display name.

## Technologies Used

- **Front-end**: NextJS, TanStack Query, Tailwind CSS, TypeScript

- **Authentication**: NextAuth.js with Google sign-in

- **Back-end**: Prisma ORM, PlanetScale (for database hosting)

- **Deployment**: Vercel

## Installation

1. Clone the repository: `git clone https://github.com/Migulev/MyEddit.git`

2. Install the required dependencies: `cd MyEddit` and `npm install`

3. Set up the database using Prisma, and make sure you have the required database credentials from PlanetScale.

4. Configure Google Sign-In authentication with NextAuth.js. Refer to the NextAuth.js documentation for instructions.

5. Create an `.env` file based on the provided `.env.example` file. Replace the placeholder values with your actual configurations and credentials.

6. Run the application: `npm run dev`

7. Access the application in your web browser at `http://localhost:3000` or any other specified port.

## Usage

1. Sign in using your Google account.

2. Explore existing posts and comments.

3. Create new posts and participate in discussions.

4. Vote on posts to show your approval or disapproval.

5. Update your display name in the user settings.

## Contribution

Contributions to MyEddit are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, feel free to open issues or submit pull requests on the [GitHub repository](https://github.com/Migulev/MyEddit).

## Acknowledgments

This project is inspired by the functionality and design of Reddit. Special thanks to the Reddit team for their contributions to the online community.
