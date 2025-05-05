
# ☁️ Cloud Media Gallery

### A Cloud-Based Full-Stack Web App with MERN & AWS S3

A robust and secure media gallery application built with the **MERN** stack and **Amazon S3**, allowing users to register, authenticate, and upload/manage media files (images and videos) in the cloud. Designed with a sleek dark-themed UI using **Tailwind CSS**.

---

## 🔥 Features

* ✅ **User Authentication** – Register/login with secure JWT-based authentication.
* 📤 **Media Upload** – Upload images and videos directly to AWS S3.
* 🖼️ **Media Gallery** – View uploaded media with image previews and video playback.
* 📅 **Filter Options** – Filter media by day, month, or year of upload.
* 🗑️ **Delete Media** – Delete individual or multiple files from S3 and MongoDB.
* 🔁 **Update Files** – Replace existing files with new versions.
* 📊 **Media Metadata** – View file size, upload time, and video duration.
* 🌙 **Dark Mode** – Fully responsive dark-themed UI.
* 🔔 **Toast Notifications** – User-friendly feedback using toast alerts.

---

## ⚙️ Tech Stack

### 🧠 Backend

* **Node.js** — Server runtime environment
* **Express.js** — RESTful API framework
* **MongoDB** — NoSQL database for user and media metadata
* **Mongoose** — MongoDB ORM
* **AWS S3** — Cloud storage for media files
* **JWT** — Token-based authentication
* **Multer** — Handle multipart form data for uploads
* **BcryptJS** — Secure password hashing
* **Dotenv** — Manage sensitive credentials
* **CORS** — Allow cross-origin communication
* **UUID** *(optional)* — Unique file name generation

### 💻 Frontend

* **React.js** — Component-based SPA framework
* **Tailwind CSS** — Utility-first CSS for responsive design
* **React Toastify** — Toast messages and notifications
* **React Icons** — Icon support for modern UI

---

## 🧩 Environment Variables

Rename `.env.example` to `.env` and add your configuration:

```env
# MongoDB
MONGO_URI=your_mongo_connection_string

# JWT
JWT_SECRET=your_jwt_secret

# AWS Credentials
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
AWS_BUCKET_NAME=your_s3_bucket
AWS_REGION=your_s3_region
```

---

## 📦 Backend Modules

| Module         | Purpose                               |
| -------------- | ------------------------------------- |
| `express`      | Create API endpoints                  |
| `mongoose`     | Interact with MongoDB database        |
| `jsonwebtoken` | Authenticate users via JWTs           |
| `bcryptjs`     | Securely hash passwords               |
| `cors`         | Enable cross-origin resource sharing  |
| `dotenv`       | Manage environment variables          |
| `multer`       | Handle file uploads                   |
| `aws-sdk`      | AWS S3 integration                    |
| `uuid`         | Generate unique file names (optional) |

---

## 🎨 Frontend Modules

| Module                     | Purpose                       |
| -------------------------- | ----------------------------- |
| `react`                    | Build SPA frontend            |
| `react-dom`                | Mount React to the DOM        |
| `react-toastify`           | Show toast notifications      |
| `react-icons`              | Use icons across the UI       |
| `tailwindcss`              | Style UI with utility classes |
| `postcss` + `autoprefixer` | Required for Tailwind build   |

---

## ✅ Future Enhancements

* 🔍 Add search functionality (by name, tags, type)
* 📁 Organize uploads into folders or albums
* 📊 Admin dashboard with usage statistics
* 🔐 Role-based user permissions
* 🌍 Multi-language support

---

## 🙌 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch and open a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.
Feel free to use and modify for personal or commercial use.

---

## 👨‍💻 Author
[Shrinidhi Upadhyaya](https://github.com/Shrinidhi972004).
[Sudhama Bhat](https://github.com/Sudhama-bhat).
[Shamanth Krishna V R](https://github.com/Shamanth-k).



