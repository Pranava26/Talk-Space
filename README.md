# Talk Space

**Talk Space** is a real-time chat application built using the MERN stack. It supports text and image-based communication, along with several user-centric features such as authentication, authorization, and customizable themes.

## 🚀 Live Demo
[Talk Space Live Website](https://talk-space-fuxp.onrender.com/login)

## 🌟 Features

- 🔥 **Real-time Communication:** Users can chat via text and share images.
- 🔒 **Authentication & Authorization:** Secure user login and registration.
- 🖼️ **User Profiles:** Update profile pictures and manage account settings.
- 📡 **Real-time Status:** Displays online/offline status of users.
- 🌙 **Theming:** Switch between light and dark modes.
- 📱 **Responsive Design:** Optimized for all screen sizes.

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS, DaisyUI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-time Communication:** Socket.IO
- **State Management:** Zustand
- **Image Hosting:** Cloudinary

## 📝 Installation

Follow these steps to set up the project locally:

### Prerequisites
- Node.js
- MongoDB

### Clone the Repository
```bash
$ git clone https://github.com/Pranava26/Talk-Space.git
$ cd Talk-Space
```

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   $ cd server
   ```
2. Install dependencies:
   ```bash
   $ npm install
   ```
3. Create a `.env` file in the backend directory and add the following environment variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```
4. Start the backend server:
   ```bash
   $ npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   $ cd ../client
   ```
2. Install dependencies:
   ```bash
   $ npm install
   ```
3. Start the development server:
   ```bash
   $ npm start
   ```

## 📂 Folder Structure

```
Talk-Space/
├── server/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── utils/
│   ├── server.js
│   └── .env
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── context/
│   │   └── App.js
└── README.md
```

## 🚢 Deployment

The app is deployed on [Render](https://render.com/). Follow the documentation for deploying both frontend and backend.

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   $ git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   $ git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   $ git push origin feature-name
   ```
5. Open a Pull Request.

## 📧 Contact

For questions or feedback, please contact:
- **Developer:** Pranava
- **GitHub:** [Pranava26](https://github.com/Pranava26)
