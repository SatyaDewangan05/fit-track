# FitTrack

FitTrack is a comprehensive health and fitness tracking web application built with Next.js for the frontend and Express.js for the backend. It allows users to monitor their weight, activity levels, and nutritional intake, providing insightful visualizations and progress tracking.

## Features

- User authentication (signup, login, OTP verification)
- Dashboard with real-time health and fitness data visualization
- Weight progress tracking
- Activity monitoring (steps, calories burned)
- Nutritional breakdown
- Responsive design for mobile and desktop

## Tech Stack

- Frontend: Next.js, React, TypeScript
- Backend: Express.js, Node.js
- Styling: Tailwind CSS
- UI Components: shadcn/ui
- Charts: Recharts
- Authentication: JWT (to be implemented)

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or later)
- npm (v6 or later)
- Express Backend (https://github.com/SatyaDewangan05/auth_server_ts.git))

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/fittrack.git
   cd fittrack
   ```

2. Install dependencies for both frontend and backend:

   ```
   # Install dependencies
   npm install
   ```

## Configuration

   Create a `.env` file in the root directory:

   ```
   NEXT_PUBLIC_SERVER_IP=http://localhost:5000
   ```

## Running the Application

1. Start the Web server:

   ```
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
fittrack/
├── src/
│   ├── app/
│   │   ├── index.tsx
│   │   ├── signup.tsx
│   │   ├── login.tsx
│   │   └── dashboard.tsx
│   ├── components/
│   │   └── ui/
│   └── public/

Express Backend
backend/
├── index.js
├── routes/
├── controllers/
├── models/
└── middleware/
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Express.js](https://expressjs.com/)
- [Recharts](https://recharts.org/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com/)
