## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Assets](#links)
7. 🚀 [More](#more)

---

## 🚨 Tutorial

## 🤖 Introduction

Build a full-stack Real Estate application with React Native, featuring Google authentication, dynamic property listings, and user profiles. Designed with modern tools like Expo SDK 52, Appwrite, Tailwind CSS, and TypeScript for a seamless and scalable experience.

---

## ⚙️ Tech Stack

- **Expo**
- **React Native**
- **TypeScript**
- **Nativewind**
- **Appwrite**
- **Tailwind CSS**

---

## 🔋 Features

✅ **Authentication with Google** - Secure and seamless user sign-ins using Google’s authentication service.

✅ **Home Page** - Displays the latest and recommended properties with powerful search and filter functionality.

✅ **Explore Page** - Allows users to browse all types of properties with a clean and intuitive interface.

✅ **Property Details Page** - Provides comprehensive information about individual properties, including images and key details.

✅ **Profile Page** - Customizable user settings and profile management.

✅ **Centralized Data Fetching** - Custom-built solution inspired by TanStack’s useQuery for efficient API calls.

...and many more, including code architecture and reusability.

---

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

```bash
git clone MyRepoLink
cd react_native-restate
```

### Installation

```bash
npm install
```

### Set Up Environment Variables

Create a `.env.local` file in the root directory and add the following:

```env
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
```

Replace the placeholders with your actual Appwrite credentials. Get these credentials by signing up and creating a project on [Appwrite](https://apwr.dev/JSM050).

### Start the App

```bash
npx expo start
```

You'll find options to open the app in:

- [Development Build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android Emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS Simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go) - a sandbox for testing Expo apps

Start developing by editing files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).
