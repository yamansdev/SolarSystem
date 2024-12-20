
# Solar System Simulation

This project is a 3D solar system simulation built with Three.js and Tweakpane. It includes a sun, planets, and moons, all rendered in a 3D scene with realistic textures and lighting.

## Project Structure

```
.gitignore


package.json


src/
    

index.html


    

script.js


    

style.css


static/
    textures/
        

2k_stars_milky_way.hdr


        

8k_stars_milky_way.hdr


        cubeMap/


vite.config.js


```

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd <project-directory>
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Running the Project

To start the development server, run:
```sh
npm run dev
```

This will start the Vite development server and open the project in your default web browser.

### Building the Project

To build the project for production, run:
```sh
npm run build
```

The built files will be output to the `dist` directory.

### Previewing the Build

To preview the built project, run:
```sh
npm run preview
```

## Project Details

- **Three.js**: A JavaScript 3D library used to create and display animated 3D computer graphics in a web browser.
- **Tweakpane**: A pane library for tweaking parameters in the UI.
- **Vite**: A build tool that aims to provide a faster and leaner development experience for modern web projects.

## License

This project is licensed under the MIT License.
