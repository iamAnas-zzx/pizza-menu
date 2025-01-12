# Fast React Pizza Co.

Welcome to **Fast React Pizza Co.**, a simple yet modern React-based web page showcasing an Italian pizza menu. This project was built to deepen understanding of **React components**, **props**, and **JSX**, and demonstrates how they can be effectively used to build a dynamic and reusable user interface.

## Features

- **Dynamic Menu Rendering**: The menu dynamically displays a list of pizzas, including their ingredients, price, and availability.
- **Component-Based Design**: The application is structured with reusable React components like `Header`, `Menu`, `Pizza`, and `Footer`.
- **Props and JSX**: Efficient use of props to pass data between components and JSX for rendering dynamic content.
- **Conditional Rendering**: Show different UI elements based on the state (e.g., sold-out pizzas or menu availability).
- **Operating Hours Check**: Displays whether the restaurant is open or closed based on current time.

## Components Overview

### 1. **App**
The main component that serves as the root of the application. It combines other components to create the full structure.

### 2. **Header**
Displays the application title, "Fast React Pizza Co."

### 3. **Menu**
Handles the menu logic:
- Maps over the `pizzaData` array to render individual pizzas.
- Displays a placeholder message when no pizzas are available.

### 4. **Pizza**
A reusable component for each pizza item, displaying:
- Name
- Ingredients
- Price
- Sold-out status

### 5. **Footer**
Checks the current time and displays whether the restaurant is open or closed. If open, it shows an **Order** button.

### 6. **Order**
Renders the opening hours and a button for placing orders when the restaurant is open.


## Key Learnings

1. **Components**:
   - Broke down the application into small, reusable components.
   - Learned how to manage and structure components effectively.

2. **Props**:
   - Used props to pass dynamic data, such as pizza details, from parent to child components.

3. **JSX**:
   - Leveraged JSX for writing clean, declarative UI code.

4. **Conditional Rendering**:
   - Implemented logic to render UI elements based on conditions (e.g., whether a pizza is sold out or the restaurant is open).

5. **Data Mapping**:
   - Used `map()` to dynamically generate UI for each pizza item.

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fast-react-pizza-co.git


