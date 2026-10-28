# 🎬 QuickShow — Movie Ticket Booking Platform

A full-stack movie ticket booking web application where users can explore movies, check showtimes, select seats, and book tickets online. QuickShow provides a smooth booking experience with a modern and responsive interface.

## 🌟 Live Demo

- **User Website:** https://quickshow-sigma-roan.vercel.app/
- **Admin Panel:** https://quickshow-sigma-roan.vercel.app/admin

## ✨ Features

- 🎥 Browse movies and explore movie details
- 🔍 Discover movies using movie data from TMDB
- 🕒 View available shows and showtimes
- 💺 Select seats and book movie tickets
- 💳 Online payment integration with Stripe
- 🔐 User authentication with Clerk
- 🛠️ Admin panel for managing movie shows
- ⚡ Background workflows and scheduled tasks using Inngest
- 📱 Responsive user interface
- 🗄️ MongoDB database integration

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend user interface |
| Vite | Development server and build tool |
| Node.js | Backend runtime |
| Express.js | Backend API |
| MongoDB | Database |
| Clerk | Authentication |
| Stripe | Payment processing |
| Inngest | Background workflows |
| TMDB API | Movie information |

## 📁 Project Structure

```text
QuickShow/
├── client/             # Frontend application
├── server/             # Backend application
├── README.md
└── package.json        # Root package file, if configured
```

*Note: The actual folder structure may differ depending on your project setup.*

## 🚀 Getting Started

Follow these steps to run QuickShow locally.

### 1. Clone the Repository

```bash
git clone https://github.com/anshu4503/QuickShow.git
cd QuickShow
```

### 2. Install Dependencies

Open a terminal in the project directory.

Install root dependencies if your project has a root `package.json`:

```bash
npm install
```

Install frontend dependencies:

```bash
cd client
npm install
```

Install backend dependencies:

```bash
cd ../server
npm install
```

### 3. Configure Environment Variables

Create the required `.env` files in the appropriate frontend and backend directories.

Example variables may include:

```env
# Frontend
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_BASE_URL=your_backend_url
```

```env
# Backend
MONGODB_URI=your_mongodb_connection_string
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
TMDB_API_KEY=your_tmdb_api_key
INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key
```

**Important:** These are example variable names. Check your existing code and `.env.example` files to confirm the exact names your application requires. Never upload real API keys, passwords, or secret tokens to GitHub.

### 4. Run the Application

Start the backend using the script defined in the server's `package.json`. For example, if the script is named `server`:

```bash
npm run server
```

Start the frontend in a separate terminal:

```bash
cd client
npm run dev
```

Use the local URL displayed by Vite in your terminal to open the application.

*Note: Commands may need adjustment to match the scripts defined in your project's `package.json` files.*

## 🔑 Required Services

To use all configured features, you may need accounts or API credentials for:

- **MongoDB** — Database hosting
- **Clerk** — User authentication
- **Stripe** — Payment integration
- **TMDB** — Movie data
- **Inngest** — Background workflows

## 🔒 Security

- Keep API keys and secret credentials private.
- Store sensitive values in environment variables.
- Do not commit `.env` files containing secrets.
- Add `.env` and other sensitive local files to `.gitignore`.
- Use test credentials when developing payment functionality.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

## 📄 License

Check the repository's existing `LICENSE` file for the applicable license and copyright notice.

If this project is based on an existing open-source repository, retain the original license and required attribution. Do not replace the original copyright notice unless you have the right to do so.

## 👩‍💻 Author

**Anshu Pandey**

- GitHub: [@anshu4503](https://github.com/anshu4503)
- Email: [anshupandey4503@gmail.com](mailto:anshupandey4503@gmail.com)

---

⭐ If you find this project useful, consider giving the repository a star!