Step 1: Create a New React Component for the Theme Toggle Button

- In your project, create a new React component for the theme
toggle button. You can name this component something
like ThemeToggle.js.

Step 2: Define State for Theme

- In your App.js or a top-level component, define a state variable
to track the current theme. You can use the useState hook for this.

Step 3: Create a Function to Toggle Theme

- Create a function, such as toggleTheme, to toggle between
"light" and "dark" themes when the button is clicked.
You can use the setTheme function to update the theme state.

Step 4: Create a Function to Get Theme Icon

- Create a function, such as getThemeIcon, to conditionally 
render different icons or elements based on the current theme.

Step 5: Create CSS for Light and Dark Themes

- In your CSS or stylesheets, define styles for both the light
and dark themes. You can use CSS classes to distinguish
between the two themes.

Step 6: Use the Theme State in Your Component
- In your component (e.g., App.js), use the theme state to
conditionally apply the theme classes to the root container
and the theme toggle button.

Step 7: Handle Local Storage

- If you want to persist the user's theme preference across
sessions, you can use localStorage. Add logic to store and 
retrieve the theme from localStorage in the useEffect hook.

Step 8: Test and Style

- Test your application and ensure that the theme toggle button
works as expected, switching between the light and dark themes.

Step 9: Style the Rest of Your Application

- Style the rest of your application, including components,
to ensure a consistent and visually appealing look for both themes.

