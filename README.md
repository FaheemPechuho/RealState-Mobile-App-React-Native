<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="expo" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">A Real Estate App</h3>

## <a name="introduction">🤖 Introduction</a>

Build a full-stack Real Estate application with React Native, featuring Google authentication, dynamic property listings, and user profiles. Designed with modern tools like Expo SDK 52, Appwrite, Tailwind CSS, and TypeScript for a seamless and scalable experience.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Expo
- React Native
- TypeScript
- Nativewind
- Appwrite
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Authentication with Google**: Secure and seamless user sign-ins using Google’s authentication service.

👉 **Home Page**: Displays the latest and recommended properties with powerful search and filter functionality.

👉 **Explore Page**: Allows users to browse all types of properties with a clean and intuitive interface.

👉 **Property Details Page**: Provides comprehensive information about individual properties, including images and key details.

👉 **Profile Page**: Customizable user settings and profile management

👉 **Centralized Data Fetching**: Custom-built solution inspired by TanStack’s useQuery for efficient API calls.

and many more, including code architecture and reusability

## <a name="screen">🔋 Screen</a>

## <a name="screen"> Login Screen</a>

![1](https://github.com/user-attachments/assets/43dd382a-c68c-466c-87de-4f9645ef36ee)

## <a name="screen"> Home Screen</a>

![2](https://github.com/user-attachments/assets/7eb7e3a6-dd69-47f3-a209-8447e325f344)
![3](https://github.com/user-attachments/assets/1b4af5bd-ab0e-4dbb-ac46-89b0bdc287a0)

## <a name="screen"> Search and Explore Screen </a>

![4](https://github.com/user-attachments/assets/556b4843-bdc7-45eb-9252-2d19d114dd7d)

## <a name="screen"> Property Description Screen </a>

![5](https://github.com/user-attachments/assets/49f2196b-6175-4ca6-91f0-919e9f8963eb)
![6](https://github.com/user-attachments/assets/2b8b3698-d7cf-4280-80b3-6c53312ecf82)

## <a name="screen"> User Profile Management Screen </a>

![7](https://github.com/user-attachments/assets/612bb156-6bfd-4913-a184-be28cbb2a303)
![8](https://github.com/user-attachments/assets/b21987d0-ff53-4e74-bc81-586769d1ff48)


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone 
cd react_native-restate
```

**Installation**

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=
```

Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up & creating a new project on the [Appwrite website](https://apwr.dev/JSM050).

**Start the app**

```bash
 npx expo start
```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).
