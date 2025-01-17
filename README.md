# InstaRent

InstaRent is a web platform that facilitates renting items, allowing users to both list items for rent and rent items from others. The platform enables users to create listings, manage their inventory, view available items for rent, add items to a wishlist, and more.

# Features

User Authentication: Users can create accounts, log in, and manage their profiles.
Listings: Easily create listings for items to be rented out, managing inventory and availability effortlessly.
Search and Filter: Search functionality allows users to find items by category, name, or other parameters.
Wishlist: Users can add items to their wishlist for future reference.
Inventory Management: Users can manage their listed items and update their availability.
Renting Process: Facilitates the process of renting items by connecting renters and owners.
User Reviews: Enable users to leave reviews and ratings for rented items or other users.

# Technologies Used
Frontend: HTML, CSS, JavaScript, React.js
Backend: Node.js, Flask, Django
Database: MongoDB, MySQL
APIs: Integration with Google Maps API for location-based services.
Other Tools: Axios for HTTP requests, JSON Web Tokens for authentication, etc.

# Getting Started
Clone the repository:

`git clone https://github.com/RameshBabuAsh/InstaRent.git`

Install dependencies for both frontend and backend:

`cd InstaRent/frontend`

`npm install`

`cd ../backend`

`npm install`

Run app.py too for search engine manipulation using LLM models

`python app.py`

Set up environment variables:

Create a .env file in the backend directory and add necessary environment variables (e.g., MongoDB connection string, API keys).
Start the development server:

Frontend: cd frontend && npm start
Backend: cd backend && npm start
Open your browser and access http://localhost:3000 to view the website.

Chat Backend
For running the separate backend for chat named "backend_chat" (Django), use the following commands:

`cd backend_chat`

`python manage.py runserver`

Contributing
Contributions are welcome! If you want to contribute to InstaRent, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Create a pull request.

Acknowledgements
Mention any resources or individuals whose code or ideas you used.
