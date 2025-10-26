# AI Course Generator

AI Course Generator is a web app I built that lets anyone create complete educational courses using **artificial intelligence**. By entering simple details like course name, duration, number of chapters, and video preferences, the app automatically generates a full course structure and attaches relevant YouTube videos for each topic.

---

## Features

* **User Accounts** – Secure sign-up and sign-in system.
* **AI-Powered Course Builder** – Instantly generates course outlines based on user input.
* **YouTube Integration** – Pulls in matching YouTube videos for each chapter automatically.
* **Image Uploads** – Stores all course images in Firebase.
* **Modern UI** – Designed with **Shadcn UI** for a clean, responsive interface.

---

## Tech Stack

* **Next.js** – Frontend and server logic
* **PostgreSQL** – Database
* **Drizzle ORM** – For managing schema and queries
* **Firebase** – Image and media storage
* **Shadcn UI Library** – Modern UI components

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Meghanath1435/ai-course-generator.git
   cd ai-course-generator
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add:

   ```bash
   NEXT_PUBLIC_HOST_URL="http://localhost:3000"
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-key"
   CLERK_SECRET_KEY="your-key"
   NEXT_PUBLIC_GOOGLE_GEMINI_API_KEY="your-key"
   NEXT_PUBLIC_DRIZZLE_DATABASE_URL="your-database-url"
   NEXT_PUBLIC_FIREBASE_API_KEY="your-key"
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN="your-auth-domain"
   NEXT_PUBLIC_FIREBASE_PROJECT_ID="project-id"
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET="your-storage-bucket"
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID="your-sender-id"
   NEXT_PUBLIC_FIREBASE_APP_ID="your-app-id"
   NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID="your-measurement-id"
   NEXT_PUBLIC_YOUTUBE_API_KEY="your-youtube-api-key"
   ```

4. Run the development server**

   ```bash
   npm run dev
   ```

   Then open [http://localhost:3000](http://localhost:3000).

---

## Future Improvements

* Add AI-based quiz generation
* Enable course sharing and export
* Build an admin dashboard for analytics

---

## Contributing

I welcome improvements or suggestions!

1. Fork this repo
2. Create a new branch (`feature/your-feature`)
3. Commit and push your changes
4. Open a pull request

---

**Created and maintained by [Meghanath Tattari](https://github.com/Meghanath1435)**

---

Would you like me to also make it sound more “portfolio-ready” (so it highlights your personal role, skills, and project purpose for recruiters)?
