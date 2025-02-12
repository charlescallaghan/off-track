# 🌲🎵Off-Track App 🎵🌲

#### WE ARE THE FIRST COMBINING MUSIC, URBAN NATURE, EXERCISE & MEDITATION IN ONE. 
## (App is in the process of being deployed to the Play & App stores.)

<img src="https://github.com/matiasmateu/off-track/blob/master/src/images/offtrack1.png" width="400"></img>
<img src="https://github.com/matiasmateu/off-track/blob/master/src/images/offtrack2.png" width="400"></img>

## What this project is about

Off-Track is a group project I worked on to build a mobile application for an artist and composer who wanted to make her musical walks available to individuals. It is built using React-Native and Redux (with a simple landing web page in React)

## Table of contents:

- **[Intro](#intro)**
- **[Architecture](#create-react-app)**

## Intro

This app launches with a [React web app](https://reactjs.org/) and [React Native app](https://facebook.github.io/react-native/) sharing a single code base. It shares the 'business logic' (_i.e. actions, containers, reducers_) across the platforms, whilst allowing flexibility in View components to ensure your project looks and feels native in each platform.

- A shared React and React Native structure
- __Flux architecture__
    - [Redux]
- __Routing and navigation__
    - [React Native Router Flux] for native mobile
    - [React Router] for web
- __Data Caching / Offline__
    - [Redux Persist]
- __UI Toolkit/s__
    - [Native Base] for native mobile
    - [Bootstrap] for web
- __Simpler mobile app development
    - [Expo]
- __User authentication
    [Firebase]
- __API
    [Firebase]
---
# Usage


#### 1. Clone and Install


git clone https://github.com/charlescallaghan/off-track.git

#### 2. Install dependencies
```bash
npm install
```

#### 2.1. Run the _React Native_ App

```bash
# Start the React Native packager
expo start
```

Instructions are shown in the terminal. You can select to open it in:

- An emulator (either iOS or Android)
- Your mobile device with the [Expo app](https://expo.io/). It will reload if you save edits to your files and you will see build errors and logs in the terminal.

#### 2.2. Run the _Web_ App

```bash
# Starts are local live-reload server at:
# http://localhost:3001
npm run web
```

## Architecture

<img src="https://github.com/matiasmateu/off-track/blob/master/src/images/architecture.png" alt="arch" />
