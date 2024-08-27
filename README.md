# React Button Counter

A simple ReactJS application that demonstrates the basics of React components, state management, and event handling by creating a button that logs messages to the console when clicked and a title that logs messages when hovered over.

## Features

- **Dynamic Title**: A title that logs a message to the console when the mouse enters it.
- **Interactive Button**: A button that logs a message to the console when clicked.
- **Basic Component Structure**: Demonstrates a basic component structure using functional components in React.

## Technologies Used

- **ReactJS**: A JavaScript library for building user interfaces.
- **JavaScript (ES6)**: Modern JavaScript features for building the application.
- **HTML5**: Structuring the application layout.

## Code Overview

This application is a simple example to help understand the basics of React components, JSX syntax, and event handling.

### Components

1. **Title Component**:

   - Displays a title with an `onMouseEnter` event handler that logs "Mouse Entered" to the console.

   ```jsx
   const Title = () => (
   	<h3 id='title' onMouseEnter={() => console.log("Mouse Entered")}>
   		Hello, I am a title
   	</h3>
   );
   ```

2. **Button Component:**
   - A button styled with a background color of tomato
   ```jsx
   const Button = () => (
   	<button style={{ backgroundColor: "tomato" }}>Click me</button>
   );
   ```
3. **Container Component:**
   - A container that houses both the Title and Button components, rendering them together.
   ```jsx
   const Container = () => (
   	<div>
   		<Title />
   		<Button />
   	</div>
   );
   ```

### Rendering

- The Container component is rendered into the root element of the HTML page.
  ```jsx
  ReactDOM.render(<Container />, root);
  ```

### How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/react-button-counter.git
   cd button-counter
   ```
2. **Open `index.html` in your browser**
   Simply open the index.html file in a web browser to see the application in action.

## Usage

- **Mouse Over the Title**: Hover your mouse over the title to see the "Mouse Entered" message in the console.
- **Click the Button**: Click the "Click me" button to see the "clicked" message in the console.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, please feel free to fork the repository and submit a pull request.

## License

This project is open source and available under the MIT License.

## Contact

For any questions or suggestions, please contact [hominsong@naver.com](mailto:hominsong@naver.com).

---

**Enjoy using Button Counter!**
