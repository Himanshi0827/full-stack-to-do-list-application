## Backend (Node.js & Express.js)

### Features
- RESTful API for tasks (GET, POST, PUT, DELETE).
- User authentication using JWT tokens.
- Task persistence via MongoDB.
- Input validation for API requests.
- Basic security measures and error handling.

### Setup Instructions

1. Navigate to the backend directory:
   ```bash
   cd server
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root of the `server` directory and add the following:
   ```bash
   MONGODB_URI=your-mongodb-uri
   JWT_SECRET=your-secret-key
   ```

4. Run the backend server:
   ```bash
   node server.js
   ```

### Technologies
- **Node.js:** JavaScript runtime for building the backend.
- **Express.js:** Web framework for handling API requests and routing.
- **MongoDB:** NoSQL database for storing tasks.

---

## Deployment

1. **Frontend:** Deployed on netlify (https://himanshi-todoapp.netlify.app/).
2. **Backend:** Deployed on Render ([or Render, if needed](https://backend-todo-npkz.onrender.com)).

The application is publicly accessible via a single URL, which combines both frontend and backend.

---

## Combined Full-Stack Setup

To run both the frontend and backend locally:

1. Clone the repository:
 

2. **Frontend:**
   Navigate to the `client` directory:
   ```bash
   cd client
   npm install
   npm start
   ```

3. **Backend:**
   Navigate to the `server` directory in a separate terminal:
   ```bash
   cd server
   npm install
   npm run dev
   ```

Make sure MongoDB is running locally or that you've set up a remote connection using your `.env` file.

---

## Challenges & Decisions
- **Authentication:** JWT tokens were implemented for secure user authentication.
- **Database Integration:** MongoDB was chosen for its scalability and ease of use with Node.js.
- **UI/UX Design:** Tailwind CSS was used to quickly create a responsive and clean user interface.
  
### Bonus Features
- **User Authentication:** Each user can create an account and manage their personal to-do list.



## Conclusion
This project helped in understanding:
1. Connecting the frontend and backend using APIs.
2. Implementing JWT-based authentication.
3. Working with MongoDB for persistent data storage.
4. Handling CRUD operations in a full-stack environment.
