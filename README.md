 🚀 Thumblify

 📌 Overview

Thumblify is a web application that helps users quickly generate eye-catching thumbnails using simple inputs. It is designed for content creators, developers, and marketers who want fast, customizable, and attractive thumbnails without using complex design tools.

---

❗ Problem Statement

Creating thumbnails manually using tools like Photoshop or Canva:

* Takes time ⏳
* Requires design skills 🎨
* Not efficient for quick content production ⚡

 💡 Solution

Thumblify solves this by:

* Automating thumbnail generation
* Providing easy customization options
* Reducing time and effort

---

 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript(TypeScript)
* React.js
* Tailwind CSS

 Backend

* Node.js
* Express.js

 Database

* MongoDB

 Other Tools

* Cloudinary (for image storage)
* Git & GitHub (version control)

---
 ✨ Features

* 🎯 Generate thumbnails instantly
* 🎨 Customize text, colors, and layout
* 🖼️ Upload images or use presets
* ⚡ Fast and responsive UI
* 🔐 User authentication (optional feature if implemented)

---

 ⚙️ Installation & Setup

 1️⃣ Clone the repository

```bash
git clone https://github.com/Man77Code/thumblify.git
cd thumblify
```

 2️⃣ Install dependencies

 Frontend

```bash
cd client
nodemon server.js
```

 Backend

```bash
cd server
npm run dev 
```

 3️⃣ Environment Variables

Create a `.env` file in the server folder and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4️⃣ Run the project

#### Start backend

```bash
cd server
npm start
```

#### Start frontend

```bash
cd client
npm start
```

---

## 🧠 How It Works

1. User inputs text and uploads/selects an image
2. Frontend sends request to backend
3. Backend processes data and stores images (Cloudinary)
4. Thumbnail is generated and returned to user
5. User can download or reuse the thumbnail

---

 📈 Future Improvements

* Drag & drop editor
* AI-based thumbnail suggestions
* Template marketplace
* Multi-language support

---

 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

 📬 Contact

If you have any questions or suggestions, feel free to reach out.
My Email : manishbhagat0517@gmail.com
---

 ⭐ Support

If you like this project, give it a ⭐ on GitHub!
