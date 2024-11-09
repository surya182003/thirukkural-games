# Thirukkural Games
by Surya Prakash V

Welcome to **Thirukkural Games**! This project is an interactive web-based game developed to help users engage with the ancient Tamil text "Thirukkural" in a fun and educational way. The game challenges players to arrange words in the correct order for Thirukkural couplets, making learning both enjoyable and meaningful.

## Table of Contents
- [Introduction](#introduction)
- [Game Rules](#game-rules)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)
- [Code Overview](#code-overview)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The **Thirukkural Games** project is designed to promote learning of the Thirukkural—a respected Tamil classic—through an interactive drag-and-drop game. Users are tasked with arranging scrambled words to form Thirukkural couplets correctly. Additionally, there is a visual representation that displays the cultural essence of Tamil literature and language.

## Game Rules
- Each Thirukkural couplet is presented with words in a randomized order.
- The player needs to drag and drop words into the correct sequence to form the Thirukkural.
- The game can be extended with additional couplets for continued learning and interaction.

## Getting Started

### Prerequisites
To run the project, you will need:
- A modern web browser
- An internet connection (for any images or linked resources)

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/surya182003/thirukkural-games.git
   cd thirukkural-games
   
2. Open the index.html file in your preferred web browser:
    ```bash
    open index.html

3. The game will load in your browser, ready for you to play!

## Features
- Interactive Drag-and-Drop Game: Players can arrange words to form a Thirukkural couplet.
- Traditional Tamil Styling: The interface is designed with Tamil cultural elements, enhancing the traditional learning experience.
- Educational Visualization: The "boxes" and "del" classes allow for a visually engaging layout for the displayed Thirukkural lines.

## Code Overview

### HTML File 1 (`index.html`)
- **Purpose**: Displays a Thirukkural couplet with draggable words for the user to arrange in the correct order.
- **Structure**:
  - A grid-based layout where each word of a Thirukkural is presented as a draggable "box" within a container.
  - Includes JavaScript functions to manage drag-and-drop events (such as `dragstart`, `dragover`, `drop`, etc.).
  - CSS styles are applied to give the game a traditional and engaging look, with dark violet backgrounds for draggable items.

### HTML File 2 (`test.html`)
- **Purpose**: Provides an additional representation of the Thirukkural interface in Tamil, with visual cues and styled elements that align with the theme.
- **Structure**:
  - Displays "del" tags styled to simulate clickable or hoverable Tamil text phrases, enhancing interaction.
  - CSS styling for hover effects that change colors to indicate interactivity and maintain user engagement.

### JavaScript
- **Drag-and-Drop Mechanics**: JavaScript enables users to drag words and drop them in sequence to match the Thirukkural. It includes functions to handle events and reset word positions if needed.

### CSS
- **Styling**: CSS classes like `.boxes` and `.del` create a visually pleasing layout, with styles such as rounded corners, color schemes, and interactive hover effects that add to the traditional and educational feel of the game.

## Contributing
Contributions to this project are welcome! If you find any issues or have improvements to suggest, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.




