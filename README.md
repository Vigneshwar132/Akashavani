# Akashavani

This project is a weather application built using React and Vite. It leverages modern tools to provide a fast, interactive user experience with hot module replacement (HMR) and follows best practices for code quality with ESLint.
Live Demo
---------

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#live-demo)

Check out the live demo of this project on Netlify:

[![Netlify](https://camo.githubusercontent.com/cef91fbc008f777b354805ef918be72c68f7b96c8eb6b81ce5715571c3c27df8/68747470733a2f2f7777772e6e65746c6966792e636f6d2f76332f696d672f636f6d706f6e656e74732f66756c6c2d6c6f676f2d6461726b2e737667)](https://earnest-tiramisu-c1119c.netlify.app/)

Or visit the site directly: [Weather-App.netlify.app](https://effulgent-semolina-ecc30a.netlify.app/)

Features
--------

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#features)

-   React: A popular JavaScript library for building user interfaces.
-   Vite: A fast build tool that provides HMR and optimizes the development experience.
-   ESLint: For maintaining code quality and enforcing coding standards.
-   OpenWeather API: Fetches real-time weather data for different locations around the world.
-   Responsive Design: The app is designed to be responsive and user-friendly on various devices.

Getting Started
---------------

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#getting-started)

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#prerequisites)

-   Node.js: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#installation)

1.  Clone the repository:

    ```source-shell
    git clone <repository-url>
    cd <project-folder>
    ```

2.  Install dependencies:

    ```source-shell
    npm install
    ```

3.  Create a `.env` file:

    -   Get an [OpenWeather](https://openweathermap.org/api) API Key
    -   Create a `.env` file in the root directory of the project.
    -   Add your API key for the weather service:

        ```source-dotenv
        VITE_WEATHER_API_KEY=your_api_key_here
        ```

### Running the Application

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#running-the-application)

To start the development server and view the application locally, run:

```source-shell
npm run dev
```

-   Open your browser and go to `http://localhost:3000` to see the app in action.

### Building for Production

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#building-for-production)

To build the project for production, use:

```source-shell
npm run build
```

-   The build output will be located in the `dist` folder.

### Deploying

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#deploying)

For deployment, you can upload the contents of the `dist` folder to your hosting platform (e.g., Netlify, Vercel). Follow the hosting platform's instructions for deploying static sites.

### Code Structure

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#code-structure)

-   `src`: Contains the source code for the application.
    -   `assets`: Static assets such as images.
    -   `components`: React components used in the application.
    -   `styles`: CSS files for styling the components.
    -   `App.jsx`: Main application component.
    -   `main.jsx`: Entry point for React.
-   `public`: Contains public assets like the favicon.
-   `dist`: Build output directory (generated after running `npm run build`).

### Configuration

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#configuration)

-   `vite.config.js`: Vite configuration file for setting up the build and development environment.
-   `.eslintrc.cjs`: ESLint configuration file for code linting rules.

### Available Scripts

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#available-scripts)

-   `npm run dev`: Start the development server with hot module replacement.
-   `npm run build`: Build the application for production.
-   `npm run preview`: Preview the production build locally.

### Plugins Used

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#plugins-used)

-   [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md): Vite plugin for React that uses Babel for fast refresh.
-   [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc): Alternative Vite plugin for React that uses SWC for fast refresh.

### Contributing

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#contributing)

1.  Fork the repository and create a new branch for your changes:

    ```source-shell
    git checkout -b feature/your-feature
    ```

2.  Make your changes and commit them:

    ```source-shell
    git add .
    git commit -m "Add your message here"
    ```

3.  Push your changes to your fork:

    ```source-shell
    git push origin feature/your-feature
    ```

4.  Create a pull request to the main repository.

### License

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#license)

This project is licensed under the MIT License - see the [LICENSE](https://github.com/m-manish03/Weather-App/blob/main/LICENSE) file for details.

### Acknowledgments

[](https://github.com/m-manish03/Weather-App?tab=readme-ov-file#acknowledgments)

-   Thanks to the developers of [React](https://reactjs.org/) and [Vite](https://vitejs.dev/) for creating such powerful tools.
-   Thanks to [Flaticon](https://www.flaticon.com/) for the weather icons used in the app.
-   Thanks to [OpenWeather](https://openweathermap.org/) for providing the weather data API that powers this application.
