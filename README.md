# Mavlana Stock Tracker

Mavlana Stock Tracker is a web application built with [Next.js](https://nextjs.org) that allows users to track stock prices, manage watchlists, and view detailed stock information. This project leverages modern web technologies and APIs to provide a seamless user experience.

## Features

- **Stock Search**: Quickly search for stock symbols and view their details.
- **Watchlist Management**: Add and manage your favorite stocks in a personalized watchlist.
- **Real-Time Data**: View real-time stock data using the TradingView widget.
- **Authentication**: Secure user authentication for personalized experiences.
- **Responsive Design**: Fully responsive design for desktop and mobile devices.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ariefmavlana/mavlana-stock_tracker.git
   ```

2. Navigate to the project directory:
   ```bash
   cd mavlana-stock_tracker
   ```

3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Development Server

Start the development server:
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Project Structure

- **`src/app`**: Contains the main application pages and layouts.
- **`src/components`**: Reusable UI components.
- **`src/database`**: Database connection and models.
- **`src/hooks`**: Custom React hooks.
- **`src/lib`**: Utility functions and constants.
- **`src/middleware`**: Middleware for handling requests.

## API Integration

This application integrates with the following APIs:
- **Finnhub API**: For fetching stock market data.
- **Inngest**: For handling background tasks and workflows.

## Deployment

The application can be deployed using [Vercel](https://vercel.com):

1. Connect your GitHub repository to Vercel.
2. Follow the deployment instructions provided by Vercel.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Built with Cosmos by [Arief Mavlana](https://github.com/ariefmavlana).
