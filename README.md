# QUBPhotographyManager

A Java-based application developed for the Photography Department at Queen's University Belfast, this project manages a collection of photographic images across various genres. The application allows users to add, search, and display images with detailed metadata for cataloging and album creation. 

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Classes and Design](#classes-and-design)
6. [Additional Features](#additional-features)
7. [Acknowledgments](#acknowledgments)
8. [ChatGPT Usage Report](#chatgpt-usage-report)

---

## Project Overview

This project is divided into two main parts:
1. **Core Functionality**: A console-based Java application (`QUBImages`) for image catalog management.
2. **Enhanced Functionality**: A graphical console application (`QUBMediaImages`) that uses the CSC1029Console library to display images, text, and colors in a more interactive user interface.

### Image Genres Supported:
- Astronomy, Architecture, Sport, Landscape, Portrait, Nature, Aerial, Food, and Other

## Features

### Core Functionality
- **Add Image**: Add a new image record with details like title, description, genre, and date.
- **Search Functionality**:
    - By unique ID, title, description, genre, and date range.
- **Display All**: Show all images in the system.
- **Exit**: Safely close the application.

### Additional Functionality
- Use of a custom `Console` class for enhanced visuals.
- Includes fonts, color, and image rendering to create a more engaging display experience.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/QUBPhotographyManager.git
   cd QUBPhotographyManager
