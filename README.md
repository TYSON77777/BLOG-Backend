📝 𝔹𝕃𝕆𝔾-𝔹𝕒𝕔𝕜𝕖𝕟𝕕
Welcome to the backend of my personal blog platform! This project is designed to provide a robust and scalable backend service for a blogging platform, allowing users to create, read, update, and delete blog posts.

🚀 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀
🔐 User Authentication: Secure user login and registration.

✍️ CRUD Operations: Create, read, update, and delete blog posts.

🗂️ Category Management: Organize posts into categories.

💬 Comment System: Users can comment on blog posts.

🛠️ Admin Panel: Manage users and posts.

🛠️ 𝕋𝕖𝕔𝕙𝕟𝕠𝕝𝕠𝕘𝕚𝕖𝕤 𝕌𝕤𝕖𝕕
Node.js — JavaScript runtime for building scalable network applications.

Express.js — Web framework for Node.js.

MongoDB — NoSQL database.

Mongoose — ODM for MongoDB.

JWT (JSON Web Tokens) — For secure authentication.

📁 𝙿𝚛𝚘𝚓𝚎𝚌𝚝 𝚂𝚝𝚛𝚞𝚌𝚝𝚞𝚛𝚎


BLOG-Backend/
├── controllers/
├── models/
├── routes/
├── middleware/
├── utils/
├── tests/
├── .env.example
├── package.json
└── server.js

⚙️ 𝗜𝗻𝘀𝘁𝗮𝗹𝗹𝗮𝘁𝗶𝗼𝗻
git clone https://github.com/TYSON77777/BLOG-Backend.git
cd BLOG-Backend
npm install
cp .env.example .env
# update your .env with MongoDB URI and JWT secret
npm start
The server runs on http://localhost:5000 by default.

🧪 𝗧𝗲𝘀𝘁𝘀
Run tests with:

npm test


📄 𝗟𝗶𝗰𝗲𝗻𝘀𝗲
MIT License — see LICENSE.
