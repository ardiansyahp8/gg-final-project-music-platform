# Generasi Gigih Music Platform

This project is for Final Project Generasi Gigih Batch 2 in FrontEnd track [Generasi Gigih](https://www.anakbangsabisa.org/generasi-gigih/program). Using integration of Spotify API, it could be used to find your favorite musics, select them all, and don't worry, you could save them as your own playlist that is created right into your account.

## Features

- **Login** using your Spotify Developer account 🔊
- Take a look on all of your favorite musics by find on **Search music** feature 🔍
- **Create playlist** from your favorite music 🎧
- As a bonus, you can see the **Profile Picture** and **User Name** of your account 👤

## Build using

- [Create React App](https://create-react-app.dev/) to initialize the project.
- [Typescript](https://typescriptlang.org).
- [Jest](https://jestjs.io/), [react testing-library](https://testing-library.com/) for testing the UI and implementation.
- [Material UI](https://mui.com/) and [Emotion](https://emotion.sh/docs/introduction) to make the user interface.
- [React redux](https://react-redux.js.org/) for state management (store).
- Deploy using [Vercel](https://vercel.com/).

## Getting Started

This is the guide in case you want to run this project on your own

### Run The App

1. Clone this repository
```
git clone https://github.com/ardiansyahp8/gg-final-project-music-platform
```
2. Open the project directory folder from your command prompt or Git Bash
```bash
cd gg-final-project-music-platform
```
3. Installing the packages
```
npm install
```
4. Setup the [environment variable]() to run this project.
5. Start the server
```
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result

### Run Test

You can launch the test runner by using
### `npm run test`

## Environment Variable

You have to set the `.env` file to add environment variable to run this project
- Create the `.env` file.
- Update your `.env` 
```
REACT_APP_SPOTIFY_CLIENT_ID = Your client id retrieved from Spotify Developer account
```