# React Hooks - Counter and Theme Changer

This repository demonstrates the usage of React Hooks to create a simple counter and a theme toggle (light/dark mode) in a React application.

## Features

- **Counter**: A basic counter with increment, decrement, and reset functionality.
- **Theme Switcher**: Toggle between light and dark themes using React's `useState` hook.

## React Hooks Used

- `useState`: Used to manage the state for the counter and theme toggler.
- `useEffect`: (Optional, if used for side effects like saving the theme preference in localStorage).

## Demo

- **Counter**: Click to increment or decrement the count. Reset the counter to zero with a button.
- **Theme Changer**: Toggle the theme between light and dark modes with a button.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/aarshpatel1/react-hooks.git

Sure! Here's a sample `README.md` for the GitHub repository you mentioned, focusing on the use of React Hooks to create a counter and theme switcher:

```markdown
# React Hooks - Counter and Theme Changer

This repository demonstrates the usage of React Hooks to create a simple counter and a theme toggle (light/dark mode) in a React application.

## Features

- **Counter**: A basic counter with increment, decrement, and reset functionality.
- **Theme Switcher**: Toggle between light and dark themes using React's `useState` hook.

## React Hooks Used

- `useState`: Used to manage the state for the counter and theme toggler.
- `useEffect`: (Optional, if used for side effects like saving the theme preference in localStorage).

## Demo

- **Counter**: Click to increment or decrement the count. Reset the counter to zero with a button.
- **Theme Changer**: Toggle the theme between light and dark modes with a button.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/aarshpatel1/react-hooks.git
   ```

2. Navigate into the project folder:

   ```bash
   cd react-hooks
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the application:

   ```bash
   npm start
   ```

The app will be available at `http://localhost:3000` in your browser.

## Code Explanation

### Counter with `useState`

The counter is created using React's `useState` hook. The state is initialized to `0` and can be updated through `increment`, `decrement`, and `reset` functions.

```js
const [count, setCount] = useState(0);

const increment = () => setCount(count + 1);
const decrement = () => setCount(count - 1);
const reset = () => setCount(0);
```

### Theme Changer with `useState`

The theme changer uses the `useState` hook to toggle between two states: `'light'` and `'dark'`.

```js
const [theme, setTheme] = useState('light');

const toggleTheme = () => setTheme(theme === 'light' ? 'dark' : 'light');
```

The application also utilizes CSS classes to apply the styles for the respective themes.

## Contributing

Feel free to fork the repository, make improvements, or fix issues! To contribute:

1. Fork the repo.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

```
