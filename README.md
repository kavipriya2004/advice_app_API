# Advice App Using API's
---
# React DummyJSON App

A simple React application that fetches and displays a list of products from the [DummyJSON API](https://dummyjson.com/products). This app demonstrates how to use React hooks to fetch data from an API and render it in a list.

## Features

- Fetches product data from an API
- Displays product names and prices in a list
- Handles API errors gracefully

## Technologies Used

- **React:** JavaScript library for building user interfaces.
- **JavaScript (ES6):** Modern JavaScript syntax and features.
- **HTML/CSS:** Basic structure and styling for the application.

## Installation

To set up and run the application locally, follow these steps:

### Set Up the Environment

Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed. Create a new React project if you don't have one already:

```bash
npx create-react-app my-app
cd my-app
```

### Replace Files

Replace the contents of `src/App.js` with the provided React code and `public/index.html` with the provided HTML code.

### Install Dependencies

Install the required dependencies (if not already present):

```bash
npm install
```

### Run the Application

Start the React application:

```bash
npm start
```

The application will be available at `http://localhost:3000/`. Open this URL in your web browser to view the product list.

## File Structure

- `src/App.js`: The main React component fetching and displaying product data.
- `public/index.html`: The HTML template for the React application.
- `public/favicon.ico`: The favicon for the application.

## How It Works

1. **Data Fetching:** The `useEffect` hook is used to fetch product data from the DummyJSON API when the component mounts.
2. **State Management:** The `useState` hook manages the state of the `products` array.
3. **Rendering:** The application renders a list of products, including their names and prices.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
