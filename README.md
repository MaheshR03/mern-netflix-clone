
# MERN Netflix Clone

<p>
  <strong>A full-stack Netflix clone built with MongoDB, Express, React, Node.js, and styled using TailwindCSS.</strong>
</p>

---

## Demo

Live App: [Check it out](https://netflix-clone-lkqt.onrender.com)

---

## Screenshots

![Demo App](/frontend/public/screenshot-for-readme.png)

<img width="1897" height="905" alt="Home Screen" src="https://github.com/user-attachments/assets/55ba35aa-6df1-425f-a63a-650736d6b8c9" />

<img width="1896" height="886" alt="Browse Screen" src="https://github.com/user-attachments/assets/b9824e39-f09e-4f1a-9f76-6836969e7169" />

---

## Features

- User authentication (Sign Up, Login)
- Browse trending movies and TV shows
- Search functionality
- Responsive UI with TailwindCSS
- Watch page with video player
- User search history

---

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB database

### Setup `.env` file

Create a `.env` file in the `backend` directory with the following content:

```env
PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
```

### Installation

1. **Clone the repository:**

```shell
git clone https://github.com/MaheshR03/mern-netflix-clone.git
cd mern-netflix-clone
```

2. **Install dependencies:**

```shell
cd backend
npm install
cd ../frontend
npm install
```

### Build & Start

To build and start the app locally:

```shell
npm run build
npm run start
```

---

## Project Structure

```
mern-netflix-clone/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── store/
│   │   └── utils/
│   ├── index.html
│   ├── package.json
│   └── ...
├── LICENSE
├── README.md
└── package.json
```

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to your branch (`git push origin feature/your-feature`)
6. Open a Pull Request

Please make sure your code follows the project's coding conventions and passes all tests before submitting a PR.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
