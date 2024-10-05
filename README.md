# Code_First_Basic

This repository demonstrates the Code First approach using Entity Framework Core to create a database with two independent tables: `Movies` and `Games`.

## Overview

The `Movies` table contains information about films, while the `Games` table holds details about video games. This project serves as a basic example of setting up a database schema and performing migrations with Entity Framework Core.

## Tables

### Movies Table

- **Id**: `int`, primary key, auto-incrementing.
- **Title**: `string`, the title of the movie.
- **Genre**: `string`, the genre of the movie (e.g., "Action", "Comedy", "Drama").
- **ReleaseYear**: `int`, the year the movie was released.

### Games Table

- **Id**: `int`, primary key, auto-incrementing.
- **Name**: `string`, the name of the game.
- **Platform**: `string`, the platform on which the game is played (e.g., "PC", "PlayStation", "Xbox").
- **Rating**: `decimal`, the rating of the game (ranging from 0 to 10).

## Technologies Used

- .NET 8.0
- Entity Framework Core
- SQLite (or any preferred database provider)

![image](https://github.com/user-attachments/assets/51a70084-b7c4-4660-aa03-2c460c9784b8)

