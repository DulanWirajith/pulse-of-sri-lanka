# Pulse of Sri Lanka - FrontEnd

A modern, responsive social media platform, built with [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), and TypeScript. This project replicates the core user interface of X, focusing on clean design, smooth interactions, and a modular component structure.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Project Structure](#project-structure)

## Features

- Responsive design for mobile, tablet, and desktop
- Reusable React components for posts, navigation, and user profiles
- Styled with Tailwind CSS for a modern and sleek look
- Fast development and build process
- Mimics core X platform UI elements like timeline, sidebar, and modals

## Tech Stack

- **React**: JavaScript library for building user interfaces
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Next**: Next-generation frontend tooling for fast builds
- **JavaScript (ES6+)**: Modern JavaScript syntax with Babel support

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
    git clone https://github.com/DulanWirajith/pulse-of-sri-lanka.git
    cd pulse-of-sri-lanka/frontend
   ```
2. Checkout the completed branch:
    ```bash
    git checkout main
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

## Running the Project
1. Start the development server:
    ```bash
    npm run dev
   ```
2. Open your browser and navigate to http://localhost:3000
3. To build the project for production:
    ```bash
    npm run build
    ```

## Project Structure

    pulse-of-sri-lanka/
        frontend/
        ├── public/                  # Static assets
        │    ├── general/            # Images, icons, etc.
        │    ├── icons/              # Icons, etc.
        │    ├── svg/                # Images, icons, etc.
        ├── src
        │   ├── app                  # App Router for pages and layouts
        │   │   ├── (pages)/         # Grouped routes (e.g., home, profile)
        │   │   ├── layout.tsx       # Root layout for the app
        │   │   ├── page.tsx         # Root page (e.g., homepage)
        │   │   ├── globals.css      # Global styles
        │   ├── components/          # Reusable React components
        ├── package.json             # Project dependencies and scripts
        ├── next.config.js           # Next configuration
        └── README.md                # Project documentation
