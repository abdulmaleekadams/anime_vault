# Anime Explorer

Welcome to Anime Explorer, a web application that allows users to explore a diverse collection of anime. This project is built using Next.js and leverages the Shikimori API to fetch and display anime information. The application features a dynamic grid layout, motion effects, and a "Load More" functionality for seamless exploration.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Components](#components)
- [Pages](#pages)
- [Server-Side Logic](#server-side-logic)
- [How to Run](#how-to-run)
- [Contributing](#contributing)

## Getting Started

To get started with the project, make sure you have Node.js installed on your machine. Clone the repository and install the dependencies using:

```bash
npm install
```

## Project Structure

The project is organized as follows:

- **components:** Contains reusable React components used throughout the application.
- **pages:** Defines the different pages/routes of the application.
- **server:** Houses server-side logic, including the `fetchAnime` function for fetching anime data from the Shikimori API.
- **styles:** Contains styling files for the application.
- **public:** Holds public assets such as images and icons.

## Components

- **AnimeCard:** Represents a card displaying information about a specific anime, including its name, image, kind, episodes, and score.
- **Hero:** The header component showcasing the project logo and a captivating tagline, inviting users to explore diverse anime realms.
- **LoadMore:** Implements a "Load More" section, dynamically fetching and displaying additional anime cards as the user scrolls.

## Pages

- **Home:** The main landing page displaying a grid of anime cards and a "Load More" section for continuous exploration.

## Server-Side Logic

- **fetchAnime:** A server-side function that fetches anime data from the Shikimori API based on the specified page, limit, and order parameters.

## How to Run

To run the application locally, use the following command:

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your web browser to explore Anime Explorer.

## Contributing

If you'd like to contribute to the project, please follow the standard GitHub workflow: fork the repository, create a new branch, make your changes, and submit a pull request.

Happy exploring! 🌟
