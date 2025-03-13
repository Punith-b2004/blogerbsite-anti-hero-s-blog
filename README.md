# Blog Website

## Description
This project is a **Blog Website** built using **Node.js, Express.js, and MongoDB**. It allows users to create, edit, and delete blog posts. The website features an admin panel, templating using **EJS**, and session management.

## Features
- Create, edit, and delete blog posts.
- Admin panel for managing posts.
- User authentication (session-based).
- Responsive UI using **EJS layouts**.
- Data stored in **MongoDB**.

## Technologies Used
### Backend
- **Node.js**
- **Express.js**
- **MongoDB** with **Mongoose**
- **Express-session** (Session Management)
- **Method-override** (For PUT and DELETE requests)
- **EJS** (Templating Engine)
- **Connect-mongo** (Session storage)

### Frontend
- **HTML, CSS**
- **JavaScript**
- **EJS (Embedded JavaScript Templates)**

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps to Run
1. Clone the repository:
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
```
2. Install dependencies:
```sh
npm install
```
3. Create a **.env** file in the root folder and add your MongoDB connection string:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```
4. Start MongoDB (if not running already):
```sh
mongod
```
5. Run the server:
```sh
npm start
```
6. Open your browser and visit:
```
http://localhost:5000/
```

## Project Structure
```
📁 project-folder
│── 📁 public          # Static files (CSS, JS, Images)
│── 📁 server          # Server-side logic
│   ├── 📁 config      # Database connection
│   ├── 📁 helpers     # Helper functions
│   ├── 📁 models      # Mongoose models
│   ├── 📁 routes      # Express routes
│── 📁 views          # EJS templates
│   ├── 📁 layouts     # Layout templates
│   ├── 📁 partials    # Reusable components
│── .gitignore        # Git ignore file
│── app.js            # Main server file
│── package.json      # Node.js dependencies
```

## API Routes
| Route       | Method | Description |
|------------|--------|-------------|
| `/`        | GET    | Home page |
| `/admin`   | GET    | Admin dashboard |
| `/add-post`| GET    | Add a new blog post |
| `/edit-post/:id` | GET | Edit an existing post |
| `/delete-post/:id` | DELETE | Delete a blog post |

## Demo Video
To see the app in action, watch the demo video below:

[Watch the Demo Video](https://github.com/Punith-b2004/blogerbsite-anti-hero-s-blog/raw/main/public/blog.mp4)
[Youtube Link:](https://youtu.be/Ryik-Z5ve1Y?si=vej1BiKUmS7LMioW)

## Future Enhancements
- Add **user authentication** (Login & Signup).
- Implement **rich text editor** for blog posts.
- Enable **image uploads** for blog posts.
- Improve UI with **Bootstrap/TailwindCSS**.

## Author 
Punith B
[linkedin](https://www.linkedin.com/in/punith-b-aa264b282/)

## License
This project is open-source and available under the [MIT License](LICENSE).

