# Music Library System — OOP Lab

A Python-based music library system that uses Object-Oriented Programming (OOP) principles to track songs, artists, and genres. 

Built as part of the **Moringa Module 4 — Object Oriented Programming (Part 2)** lab.

---

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Project Structure](#project-structure)
- [Testing](#testing)
- [Author](#author)
- [License](#license)

---

## Description

This project creates a `Song` class that represents individual songs while maintaining global insights at the class level. 
It tracks the total number of songs created, lists all unique artists and genres, and counts how many songs belong to each genre and artist. This allows the system to provide data analytics for features like personalized recommendations.

---

## Features

- **Instantiation Tracking:** Every time a new `Song` is created, the class automatically increments the total song count.
- **Unique Collections:** Automatically adds new artists and genres to their respective lists without duplicates.
- **Data Aggregation:** Maintains dictionaries to count exactly how many songs each artist has released, and how many songs exist in each genre.
- **Class Methods:** Uses `@classmethod` to update class-level state whenever a new instance is created.

---

## Tech Stack

- **Python 3.10+**
- **pytest** (for the provided test suite)

> *Note: The lab instructions mention `npm install`. However, this is a pure Python lab. Use `pytest` to run tests.*

---

## Installation

Clone the repo and move into it:
```bash
git clone https://github.com/<your-username>/python-music-library-system-lab.git
cd python-music-library-system-lab