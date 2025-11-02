# Firebase CRUD Todo App

This is a simple yet powerful Todo application built with Next.js, Firebase, and Tailwind CSS. It demonstrates the core concepts of a CRUD (Create, Read, Update, Delete) application using Firebase as the backend.

## ✨ Features

- **Create:** Add new todos to your list.
- **Read:** View all your todos in a clean and organized interface.
- **Update:** Edit existing todos.
- **Delete:** Remove todos you no longer need.
- **Toggle Completion:** Mark todos as complete or incomplete.
- **Real-time Updates:** Your todo list updates in real-time thanks to Firebase.
- **Responsive Design:** The app is designed to work on all screen sizes.

## 🚀 Technologies Used

- **[Next.js](https://nextjs.org/):** A popular React framework for building server-rendered applications.
- **[Firebase](https://firebase.google.com/):** A comprehensive platform for building web and mobile applications. We use Firestore for our database.
- **[Tailwind CSS](https://tailwindcss.com/):** A utility-first CSS framework for rapid UI development.
- **[TypeScript](https://www.typescriptlang.org/):** A typed superset of JavaScript that compiles to plain JavaScript.
- **[Lucide React](https://lucide.dev/):** A beautiful and consistent icon toolkit.

## 🏁 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have Node.js and npm (or yarn) installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kbimsara/firebase-Crud.git
   cd firebase-Crud
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up Firebase Environment Variables:**

   Create a `.env.local` file in the root of your project and add your Firebase configuration. You can get these details from your Firebase project settings.

   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=YOUR_API_KEY
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
   NEXT_PUBLIC_FIREBASE_APP_ID=YOUR_APP_ID
   NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=YOUR_MEASUREMENT_ID
   ```

4. **Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

##  live version

You can check out the live version of this app right here:
Vercel Host URL: https://firebase-crud-olive.vercel.app/

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/kbimsara/firebase-Crud/issues).
