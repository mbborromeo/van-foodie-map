# Vancouver Foodie Map

React website project which calls Google Maps API to plot cafes I've been to using latitute and longitude information listed in a JSON file.

Note: This project was setup in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# System Dependencies

Note: You will need your own .env file in the root folder, and define VITE_GOOGLE_MAPS_API_KEY so it equals your Google Maps API Key wrapped in quotation marks. Can use the .env.example file I provided, just be sure to rename it to .env and paste your key there. You will need to create a [Google Maps API Key](https://developers.google.com/maps/documentation/embed/get-api-key) first.

## Available Scripts

In the project directory, you can run:

### `npm install`

Install the project and system dependencies.

### `npm run dev`

Runs the app in the development mode.\
Open [http://localhost:5173/](http://localhost:5173/) to view it in the browser.

### `npm run build`

Build files required for deployment.

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
