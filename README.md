# Meme generator

A dynamic, user-friendly, and engaging meme generator built with React. This project highlights the core principles of React, including state management, component-based architecture, and API integration. Users can generate random meme images from an external database, customize them with top and bottom text, and instantly see their creations update in real time. The app provides an intuitive and seamless experience, making meme creation effortless and fun.

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Available Scripts](#available-scripts)
5. [Dependencies](#dependencies)
6. [Project Structure](#project-structure)

## Features

- Responsive design, compatible with all devices.
- Instant Preview: As users type, the text updates instantly on the image, showcasing React’s real-time UI updates.
- API Integration: Fetches meme images from an online meme database, demonstrating React’s ability to work with external APIs.
- Customizable Text: Users can input top and bottom text, which updates in real-time as they type.
- Dynamic Meme Generation: Fetches random meme images from an external API, providing a new meme template with a button click.
- Component-Based Architecture: Built with reusable React components for better maintainability.
- Clear and modular code structure.

## Getting Started

### Installation

Install the dependencies and run the project

- npm install
- npm start

Head over to https://vitejs.dev/ to learn more about configuring vite

## Usage

To start the development server, run:
**npm run dev**
The application will be accessible at **http://localhost:5173.**

## Available Scripts

Available Scripts
In the project directory, you can run:

- npm run dev : Starts the development server
- npm run build : Builds the application for production
- npx prettier --check : Checks prettier formatting
- npx prettier --write : Runs prettier and formats it

## Dependencies

- "react": "19.0.0-rc-b57d2823-20240822",
- "react-dom": "19.0.0-rc-b57d2823-20240822",
- "vite": "latest"

## Project Structure

This project follows a modular structure for better organization and maintainability. Here's an overview of the folder structure:

- **assets**: Contains all images used thrughout the project.
- **components**: Stateless components used in multiple places.
- **node_modules**: Stores all dependencies and libraries used throughout the project.
- **pages**: Main folder for the view (page) of the application.
- **public**: Stores all static assets that are not processed by the build system.
- **style**: View (page) css (style) file exported into index.html.

Below is an example folder structure for the "components" view:

```
components/
└─ Header/
├── Header-component.jsx/

```
