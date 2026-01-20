# 🚀 Lab 1: Web Interface with Tailwind CSS & ShadCN UI

![Next.js](https://img.shields.io/badge/Next.js-15.1.3-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-19.0.0-blue?style=for-the-badge&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![ShadCN UI](https://img.shields.io/badge/ShadCN_UI-Component_Library-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

## 📖 Project Overview

This project is a submission for **Lab 1 (FER202)**. The objective is to develop a modern, aesthetically pleasing, and responsive **Login Page** using **Next.js**, **Tailwind CSS**, and **ShadCN UI** components.

The design focuses on a "premium" user experience, featuring glassmorphism effects, smooth animations, and comprehensive form validations.

### 🌟 Key Features

*   **Modern UI/UX**: Implements a glassmorphism design with dynamic background gradients and blur effects.
*   **Responsive Layout**: Fully responsive design that looks great on mobile, tablet, and desktop devices.
*   **Form Validation**: Real-time validation for:
    *   **Full Name**: Required, minimum length check.
    *   **Email**: Format validation.
    *   **Password**: Required, minimum length check.
*   **Interactive Elements**:
    *   Password visibility toggle (Show/Hide).
    *   Loading states with spinners on submission.
    *   Hover effects and micro-animations.
*   **Component-Based**: Built using reusable ShadCN UI components (`Card`, `Input`, `Button`).

---

## 🛠️ Technologies Stack

This project leverages the latest web technologies for optimal performance and developer experience:

*   **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
*   **Language**: [TypeScript](https://www.typescriptlang.org/)
*   **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
*   **UI Components**: [ShadCN UI](https://ui.shadcn.com/) (based on Radix UI)
*   **Icons**: [Lucide React](https://lucide.dev/)
*   **Animation**: `tailwindcss-animate` & CSS transitions

---

## 📂 Project Structure

```bash
lab1-next/
├── app/
│   ├── globals.css      # Global styles & Tailwind directives
│   ├── layout.tsx       # Root layout
│   └── page.tsx         # Main entry point rendering the LoginForm
├── components/
│   ├── forms/
│   │   └── LoginForm.tsx  # Core Login Form component
│   └── ui/              # Reusable ShadCN components
│       ├── button.tsx
│       ├── card.tsx
│       └── input.tsx
├── public/              # Static assets
└── package.json         # Dependencies and scripts
```

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

*   **Node.js**: Version 18.17 or later.
*   **npm** (Node Package Manager).

### Installation

1.  **Clone the repository**:
    ```bash
    git clone <your-repo-url>
    cd lab1-next
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  **Run the development server**:
    ```bash
    npm run dev
    ```

4.  **Open the app**:
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

## 🎨 Design Decisions

*   **Glassmorphism**: Used to create a modern, depth-filled aesthetic.
    *   *Implementation*: `bg-white/80 backdrop-blur-xl border-white/20`
*   **Color Palette**:
    *   **Primary**: Indigo (`indigo-600`) for actions.
    *   **Background**: Soft gradient hues of Purple and Indigo.
    *   **Feedback**: Red for errors, muted grays for placeholders.
*   **Accessibility**:
    *   Proper `aria-labels` and semantic HTML.
    *   Focus states for keyboard navigation.

---

## 📦 Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

1.  Push your code to a GitHub repository.
2.  Import the project into Vercel.
3.  Deploy!

---

## 📝 Author

**[Your Name/Student ID]**
*   **Course**: FER202
*   **Lab**: 01
*   **University**: FPT University

---

*This README was generated to provide a professional overview of the Lab 1 project submission.*
