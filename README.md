# PeakTime

A modern cross-platform fitness application built with React Native, Expo, and TypeScript. PeakTime allows students to follow personalized workout and nutrition plans while giving instructors the tools to manage trainees, create training programs, and monitor progress.

## Disclaimer

This repository is part of my personal portfolio.

The project was originally developed as a university team project and is published here with the permission of my teammates.

This repository showcases my work and contributions to the project.

### My Contributions

- Developed frontend features using React Native and Expo
- Implemented responsive UI components
- Integrated REST APIs
- Improved user experience and fixed bugs

---

## Features

### Student

- Daily workout tracking
- Nutrition diary
- Weekly activity overview
- Progress monitoring
- Professor invitation system

### Professor

- Student management
- Weekly workout plan creation
- Invitation code generation
- Profile management

---

## Tech Stack

- React Native
- Expo SDK 56
- TypeScript
- Expo Router
- Tamagui
- React Native Reanimated
- Expo Secure Store

---

## Architecture

```
src/
├── app/
├── components/
├── hooks/
├── services/
├── constants/
├── types/
```

The application follows a modular architecture separating routing, reusable UI components, business logic, hooks, and API services.

---

## Screenshots

<p align="center">
  <img src="assets/login.jpeg" width="220"/>
  <img src="assets/dashboard.jpeg" width="220"/>
  <img src="assets/profile.jpeg" width="220"/>
  <img src="assets/refeicao.jpeg" width="220"/>
  <img src="assets/prediction.jpeg" width="220"/>
</p>

---

## Running the Project

Install dependencies

```bash
npm install
```

Start Expo

```bash
npx expo start
```

Available commands:

- **a** → Android
- **i** → iOS
- **w** → Web

---

## Project Structure

The application is divided into two user roles:

### Student

- Authentication
- Workout Management
- Nutrition Tracking
- Profile

### Professor

- Student Dashboard
- Workout Builder
- Invitation Management
- Profile

---

## Security

Authentication tokens are securely stored using **Expo Secure Store** on native platforms and **localStorage** on the web.

---

## License

This repository is intended for portfolio purposes.
