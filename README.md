# YC Directory Crash Course (Next.js 15 Full Stack App)

This project was built by following the [Next.js 15 Crash Course](https://www.youtube.com/watch?v=5miHyP6dgW8) by [JS Mastery](https://github.com/adrianhajdin), and it helped me learn and apply modern full-stack development practices. The original source code is [available here](https://github.com/adrianhajdin/yc_directory). All credits go to the original creator **Adrian Hajdin - JS Mastery**.

This is a full-stack web application built with **Next.js 15**, **TypeScript**, **Tailwind CSS**, **NextAuth**, **Sanity**, and **Shadcn UI**. It allows users to submit their startup ideas for virtual pitch competitions, browse other pitches, and gain exposure through a clean minimalistic design for a smooth user experience.

## ✨ Features

- **Live Content API**: Displays the latest startup ideas dynamically on the homepage using Sanity's Content API.
- **GitHub Authentication**: Allows users to log in easily using their GitHub account.
- **Pitch Submission**: Users can submit startup ideas, including title, description, category, and multimedia links ( image or video).
- **View Pitches**: Browse through submitted ideas with filtering options by category.
- **Pitch Details Page**: Click on any pitch to view its details, with multimedia and description displayed.
- **Profile Page**: Users can view the list of pitches they've submitted.
- **Editor Picks**: Admins can highlight top startup ideas using the "Editor Picks" feature managed via Sanity Studio.
- **Views Counter**: Tracks the number of views for each pitch instead of an upvote system.
- **Search**: Search functionality to load and view pitches efficiently.
- **Minimalistic Design**: Fresh and simple UI with only the essential pages for ease of use and a clean aesthetic.

## 🛠️ Tech Stack

- React 19
- Next.js 15
- NextAuth
- Sanity
- TailwindCSS
- Shadcn UI
- TypeScript

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/petrabayu/yc-directory-crash-course.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Setup your `.env` file by create a new file named `.env.local` in the root of your project and add the following content:

   ```bash
   AUTH_SECRET=
   AUTH_GITHUB_ID=
   AUTH_GITHUB_SECRET=
   NEXT_PUBLIC_SANITY_PROJECT_ID=
   NEXT_PUBLIC_SANITY_DATASET=
   NEXT_PUBLIC_SANITY_API_VERSION="vX"
   SANITY_WRITE_TOKEN=
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

## 📚 Credits

- Original video course: **[JS Mastery – Next.js 15 Crash Course](https://www.youtube.com/watch?v=Zq5fmkH0T78)**
- Original source code: **[YC Directory](https://github.com/adrianhajdin/yc_directory)**
- Code and tutorial by: **[Adrian Hajdin](https://github.com/adrianhajdin)**
