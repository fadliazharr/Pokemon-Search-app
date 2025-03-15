# Pokemon Search App

### Link
Click the link below to try the app yourself:
(https://fadliazharr.github.io/Pokemon-Search-app/)
## Overview
The **Pokemon Search App** is a simple web-based application that allows users to search for Pokémon by name or ID. It fetches data from the [freeCodeCamp PokeAPI proxy](https://pokeapi-proxy.freecodecamp.rocks/api/pokemon/) and displays essential Pokémon information, including:

- Name and ID
- Height and Weight
- Sprite Image
- Types
- Base Stats (HP, Attack, Defense, Special Attack, Special Defense, Speed)

## Technologies Used
- **HTML**: Structure of the application
- **CSS**: Styling and layout
- **JavaScript**: Fetching and displaying Pokémon data
- **PokeAPI**: Data source for Pokémon information

## Features
- Users can search for a Pokémon by entering its name or ID in the input field.
- Displays Pokémon details including stats and image.
- Type backgrounds dynamically change based on the Pokémon's type.
- Handles errors gracefully when an invalid Pokémon name or ID is entered.

## Installation & Setup
### Prerequisites
- A web browser
- Internet connection (to fetch Pokémon data)

### Steps
1. **Download or Clone the Repository**
   ```sh
   git clone https://github.com/your-username/pokemon-search-app.git
   ```
2. **Navigate to the Project Folder**
   ```sh
   cd pokemon-search-app
   ```
3. **Open the `index.html` File in a Browser**
   - Simply double-click the `index.html` file,
  

## How It Works
1. Enter a Pokémon name (e.g., "Pikachu") or ID (e.g., "25") into the search field.
2. Click the **Search** button.
3. The app fetches data from the API and displays the Pokémon's details.
4. If an invalid name or ID is entered, an alert appears saying "Pokémon not found."

## Code Structure
### 1. `index.html`
- Contains the basic structure of the app, including input fields, buttons, and display areas.

### 2. `styles.css`
- Styles the layout and colors of the app.
- Includes specific styles for different Pokémon types (e.g., Fire, Water, Grass, etc.).

### 3. `script.js`
- Handles fetching data from the API.
- Updates the DOM with Pokémon details.
- Includes error handling and display reset functions.

## Example Output
If you search for "Pikachu", you will see:
![image](https://github.com/user-attachments/assets/8e082411-8af3-47a6-9578-e6fd3d977359)



---

and thats all! :)

