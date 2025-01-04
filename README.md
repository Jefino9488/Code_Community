# Code Community Chatroom

Welcome to the **Code Community**, a real-time collaborative platform for developers to connect, share code snippets, and engage in discussions. This project is built using **React**, **Vite**, **Firebase**, and **Tailwind CSS**, providing a seamless and modern user experience.

## Features

- **Real-time Messaging**: Chat with other developers in real-time.
- **Room Creation**: Create and join chat rooms for specific topics or projects.
- **Password Protection**: Secure your chat rooms with a passkey.
- **Message Encryption**: Messages are encrypted using **AES-GCM** for enhanced security.
- **Edit & Delete Messages**: Users can edit or delete their messages within a 5-minute window.
- **Google Authentication**: Sign in with your Google account for easy access.
- **Responsive Design**: Fully responsive UI for both desktop and mobile devices.

## Technologies Used

- **Frontend**: React, Vite, Tailwind CSS
- **Backend**: Firebase (Authentication, Firestore)
- **Encryption**: AES-GCM
- **UI Components**: Shadcn UI, Radix UI, Lucide Icons

## Getting Started

### Prerequisites

- Node.js (v20 or higher)
- Firebase project with Firestore and Authentication enabled

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/chatroom.git
   cd chatroom

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up Firebase**:
    - Create a `.env` file in the root directory and add your Firebase configuration:
      ```env
      VITE_FIREBASE_API_KEY=your-api-key
      VITE_FIREBASE_AUTH_DOMAIN=your-auth-domain
      VITE_FIREBASE_PROJECT_ID=your-project-id
      VITE_FIREBASE_STORAGE_BUCKET=your-storage-bucket
      VITE_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
      VITE_FIREBASE_APP_ID=your-app-id
      VITE_FIREBASE_MEASUREMENT_ID=your-measurement-id
      VITE_ENCRYPTION_KEY=your-encryption-key
      ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```

5. **Open your browser** and navigate to `http://localhost:8080`.

### Deployment

The project is configured for deployment to **GitHub Pages**. To deploy:

1. Push your changes to the `master` branch.
2. The GitHub Actions workflow will automatically build and deploy the project to GitHub Pages.

## Project Structure

```
/chatroom
├── .github/workflows/deploy.yml       # GitHub Actions workflow for deployment
├── public/                            # Static assets
├── src/                               # Source code
│   ├── components/                    # React components
│   ├── lib/                           # Utility functions
│   ├── App.jsx                        # Main application component
│   ├── main.jsx                       # Entry point
│   └── index.css                      # Global styles
├── .eslintrc.cjs                      # ESLint configuration
├── tailwind.config.js                 # Tailwind CSS configuration
├── vite.config.js                     # Vite configuration
├── package.json                       # Project dependencies
└── README.md                          # Project documentation
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Vite](https://vitejs.dev/) for the fast development environment.
- [Firebase](https://firebase.google.com/) for backend services.
- [Tailwind CSS](https://tailwindcss.com/) for utility-first CSS.
- [Shadcn UI](https://ui.shadcn.com/) for beautiful UI components.
- 