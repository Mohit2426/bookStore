# bookStore

A mobile book catalog app built with Expo and React Native. Browse a list of books, add new entries, edit book details, and delete entries.

## Features

- View books with their title, author, cover image, and price
- Add, edit, and delete books
- Load and save book data through a REST API
- Run the app on iOS, Android, and web

## Tech stack

- [Expo](https://expo.dev/) and [React Native](https://reactnative.dev/)
- [Expo Router](https://docs.expo.dev/router/introduction/)
- TypeScript
- [Axios](https://axios-http.com/) for API requests

## Getting started

### Requirements

- Node.js and npm
- Expo Go or an iOS/Android simulator for mobile development

### Install and run

```bash
npm ci
npm start
```

Once Expo starts, follow the terminal instructions to open the app on a device or simulator. You can also use these commands to start a platform directly:

```bash
npm run android
npm run ios
npm run web
```

## Project structure

```text
app/                 Expo Router entry point
src/
  api/               Book API requests
  components/        Reusable UI components
  screens/           Home and add/edit book screens
assets/              App icons and images
```

## Book data

The app currently uses a MockAPI endpoint configured in `src/api/http.ts`. The endpoint is shared by this project, so changes made through the app affect that API's data. To use your own backend, update the endpoint in that file.

## Available scripts

| Command | Description |
| --- | --- |
| `npm start` | Start the Expo development server |
| `npm run android` | Start the app for Android |
| `npm run ios` | Start the app for iOS |
| `npm run web` | Start the app for web |
| `npm run lint` | Run Expo lint checks |
