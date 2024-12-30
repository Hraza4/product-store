# Product Store

**Product Store** is a CRUD web application for managing products. It allows users to create, read, update, and delete product entries while offering a light/dark theme toggle using Chakra UI. State management is handled with Zustand for a seamless experience.

---

## Features

- **CRUD Operations**:
  - Create a new product with relevant details.
  - View a list of all products.
  - Edit product details.
  - Delete products.

- **Theme Switching**:
  - Toggle between light mode and dark mode for a personalized user experience using Chakra UI.

- **State Management**:
  - Zustand is used for lightweight and flexible state management.

---

## Tech Stack

- **Frontend**:
  - React.js
  - Chakra UI for responsive and accessible UI components
- **State Management**:
  - Zustand for state management
- **Backend**:
  - Node.js
  - Express.js
- **Database**:
  - MongoDB (via Mongoose)
- **Version Control**:
  - Git and GitHub

---

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hraza4/product-store.git
   cd product-store
   ```

2. **Install dependencies**:

   - Install backend dependencies:
     ```bash
     npm install
     ```

   - Install frontend dependencies:
     ```bash
     cd ./frontend
     npm install
     ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. **Run the application**:

   - Start the backend server:
     ```bash
     npm run dev
     ```

   - Start the frontend development server:
     ```bash
     cd ./frontend
     npm run dev
     ```

---

## Usage

1. Navigate to the homepage to view the product list.
2. Use the "Add Product" button to create a new product.
3. Click the "Edit" button on any product to update its details.
4. Click the "Delete" button to remove a product.
5. Use the theme toggle button to switch between light and dark modes.

---

## Folder Structure

```
product-store/
├── backend/               # Node.js + Express API
│   ├── config/            # Project configurations
│   ├── models/            # Mongoose schemas
│   ├── routes/            # API routes
│   ├── controllers/       # Logic for handling requests
│   └── server.js          # Entry point for backend
├── frontend/              # React app
│   ├── public/            # Static assets
│   ├── src/               # React components, context, and services
│   │   ├── components/    # Reusable components (e.g., navbar, product cards)
│   │   ├── store/         # Zustand store for state management
│   │   ├── pages/         # Web pages (e.g, createpage, homepage)
│   │   ├── main.js/       # Entry point for frontend
│   │   └── App.js         # Main React component
├── .env                   # Environment variables (not included in Git)
└── README.md              # Project documentation
```

---

## Screenshots

| Light Mode                                | Dark Mode                                |
|-------------------------------------------|------------------------------------------|
| ![Light Mode Screenshot](https://github.com/Hraza4/product-store/blob/main/light_mode_screenshot.png?raw=true) | ![Dark Mode Screenshot](https://github.com/Hraza4/product-store/blob/main/dark_mode_screenshot.png?raw=true) |

---

## Inspiration

This project was created by following a [YouTube tutorial](https://www.youtube.com/watch?v=O3BUHwfHf84). Special thanks to the content creator for providing valuable guidance and inspiration.

---

## Future Enhancements

- User authentication for secure product management.
- Pagination for large product lists.
- Search and filter functionality.
- Image upload feature for product pictures.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`feature/your-feature`).
3. Commit your changes.
4. Push to the branch and submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Hraza4/product-store/blob/e5c8f93858b0a6da697e09a36e6f37a3654050da/LICENSE) file for details.

---

## Acknowledgments

- Thanks to the developers of MongoDB, Express, React, Chakra UI, and Zustand.
- Inspired by modern CRUD web applications.

