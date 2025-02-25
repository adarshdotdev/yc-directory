# 🚀 Startup Pitch Platform

A dynamic platform where entrepreneurs can submit their startup ideas, participate in virtual pitch competitions, and gain valuable exposure to a wider audience.

---

![preview](/preview.png)

## ✨ Features

- **Live Content API** – Displays real-time startup ideas dynamically using **Sanity's Content API**.
- **GitHub Authentication** – Secure login via GitHub.
- **Pitch Submissions** – Users can add a title, description, category, and multimedia (images/videos).
- **Browse & Filter Pitches** – View startup ideas with category-based filtering.
- **Pitch Details Page** – View complete pitch details, including multimedia.
- **User Profile** – See all pitches submitted by a user.
- **Editor Picks** – Admins can highlight top startup ideas via **Sanity Studio**.
- **View Counter** – Tracks pitch views instead of an upvote system.
- **Search Functionality** – Quickly find pitches with optimized search.
- **Minimalistic UI** – Clean, modern design focused on usability.

---

## ⚙️ Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript, Tailwind CSS, ShadCN
- **Backend & CMS**: Sanity (Headless CMS)

---

## 🚀 Installation

### 1️⃣ Install Dependencies

Run the following command to install the required dependencies:

```bash
npm install
```

### 2️⃣ Set Up Environment Variables

Create a `.env.local` file in the root directory and add the following variables:

```bash
NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=your_dataset
NEXT_PUBLIC_SANITY_API_VERSION='vX'
SANITY_TOKEN=your_sanity_token

AUTH_SECRET=your_auth_secret
AUTH_GITHUB_ID=your_github_id
AUTH_GITHUB_SECRET=your_github_secret
```

Replace the placeholder values with your actual Sanity and GitHub Auth credentials. You can obtain these by signing up and creating a new project on the [Sanity website](https://www.sanity.io/) and configuring GitHub authentication.

### 3️⃣ Run the Project

Start the development server with:

```bash
npm run dev
```

The project should now be running on `http://localhost:3000/`. 🚀
