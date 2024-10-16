<!DOCTYPE html>
<html>
<head>
  <title>ProXcure - E-Procurement System</title>
</head>
<body>

<h1 align="center">🚀 ProXcure (E-Procurement System) - Backend  🚀</h1>

<p align="center">
  <strong>Streamlining Procurement for Enhanced Transparency & Collaboration</strong>
</p>

---

<h2>📖 Overview</h2>

<p>
ProXcure is an innovative software solution designed to streamline the procurement process between companies (buyers) and service providers/sellers. It utilizes modern technology to create a competitive and transparent platform for procuring goods and services. This repository contains the backend of the ProXcure system, developed using Node.js, Express, PostgreSQL, and TypeScript, with integrations for AWS S3 and Blob storage for efficient data management.
</p>

---

<h2>⚙️ Key Features</h2>

<ul>
  <li>📜 <strong>Transparent Procurement:</strong> Ensures transparency in all procurement stages between buyers and sellers.</li>
  <li>🤝 <strong>Enhanced Collaboration:</strong> Facilitates seamless communication and bidding between companies and service providers.</li>
  <li>🔐 <strong>Data Security:</strong> Secure handling of procurement data using AWS S3 and Blob storage.</li>
  <li>⚡ <strong>Efficient Backend System:</strong> Built with Node.js, Express, and PostgreSQL for high performance and scalability.</li>
  <li>🛠 <strong>TypeORM Integration:</strong> Simplifies database interactions and migrations with TypeORM.</li>
</ul>

---

<h2>💻 Tech Stack</h2>

<ul>
  <li><strong>Node.js:</strong> Backend framework for building efficient and scalable server-side applications.</li>
  <li><strong>Express:</strong> Lightweight web framework for handling API requests.</li>
  <li><strong>TypeScript:</strong> Typed superset of JavaScript ensuring better code quality and maintainability.</li>
  <li><strong>PostgreSQL:</strong> Relational database used for storing procurement data.</li>
  <li><strong>TypeORM:</strong> ORM framework for working with PostgreSQL.</li>
  <li><strong>AWS S3 & Blob Storage:</strong> Used for securely storing and managing procurement documents and files.</li>
</ul>

---

<h2>📂 Project Structure</h2>

<pre>
ProXcure_Backend/
├── src/
│   ├── controllers/
│   ├── entities/
│   ├── routes/
│   ├── services/
│   └── config/
├── migrations/
├── .env.example
├── README.md
└── package.json
</pre>

---

<h2>🚀 Getting Started</h2>

<h3>1. Clone the Repository</h3>

<pre>
git clone https://github.com/your-username/proxcure-backend.git
cd proxcure-backend
</pre>

<h3>2. Install Dependencies</h3>

<pre>
yarn install
</pre>

<h3>3. Setup Environment Variables</h3>

<p>Create a <code>.env</code> file in the root directory based on the <code>.env.example</code> file, and configure your database credentials and AWS S3 settings.</p>

<h3>4. Run Migrations</h3>

<pre>
yarn typeorm migration:run
</pre>

<h3>5. Start the Server</h3>

<pre>
yarn dev
</pre>

<p>Your server will be running on <code>http://localhost:8000</code></p>

---

<h2>🛠 API Documentation</h2>

<p>For detailed API documentation, refer to the <strong>Swagger</strong> documentation available at <code>/api-docs</code> once the server is running.</p>

---

<h2>🙌 Contributions</h2>

<p>We welcome contributions! Feel free to open issues or submit pull requests to improve the project.</p>

<p align="center">Made with ❤️ by the ProXcure Team</p>

</body>
</html>
