# PrepUp

PrepUp is an AI-powered platform designed to help users prepare for job interviews through mock interviews and instant feedback. The platform leverages advanced AI models to simulate real-world interview scenarios, evaluate responses, and provide actionable insights for improvement.

## Features

- **Mock Interviews**: Practice interviews with AI for various roles and levels.
- **Real-Time Feedback**: Get instant feedback on communication, technical knowledge, problem-solving, and more.
- **Customizable Questions**: Generate interview questions tailored to specific roles, levels, and tech stacks.
- **User Authentication**: Secure sign-up and sign-in functionality.
- **Interview History**: View past interviews and feedback for continuous improvement.

## Tech Stack

- **Frontend**: React, Next.js, Tailwind CSS
- **Backend**: Firebase (Firestore, Authentication, Admin SDK)
- **AI Models**: OpenAI GPT-4, Google Gemini
- **Other Tools**: Vercel, Sonner for notifications, Radix UI components

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai_mock_interviews.git
   cd ai_mock_interviews-main
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the root directory and add your Firebase and OpenAI credentials:

   ```plaintext
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000` to see the app in action.

## Usage

- Sign up for an account or log in if you already have one.
- Choose the type of mock interview you want to practice.
- Answer the questions as if you were in a real interview.
- Receive instant feedback and review your interview history for improvement.

## Contributing

We welcome contributions to PrepUp! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your branch to your forked repository.
5. Submit a pull request detailing your changes and the problem they solve.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the need for effective and accessible interview preparation.
- Leveraging AI technology to provide a unique and valuable service.
