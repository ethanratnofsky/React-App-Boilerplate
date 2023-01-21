# React App Template (Ethan's Version)

This repository contains the source code for the frontend of a React web application.

## Getting Started

### Prerequisites

-   [Node.js](https://nodejs.org/en/)

### Installation

1. Clone this repository.
    ```bash
    git clone https://github.com/ethanratnofsky/React-App-Template.git
    ```
2. Navigate to the project directory.
    ```bash
    cd React-App-Template
    ```
3. Edit the following values in the `package.json` file.
    - `name`
        - This should be the desired name of your NPM package. It must be unique and lowercase.
    - `description`
        - This should be a short description of your project.
    - `keywords`
        - This should be a list of keywords that describe your project.
    - `author`
        - This should be your name.
    - `repository.url`
        - This should be the URL of your GitHub repository.
    - `bugs.url`
        - This should be the URL of your GitHub repository's issues page.
    - `homepage`
        - This should be the URL of your project's README file in your GitHub repository.
4. Install the Node dependencies.
    ```bash
    npm install
    ```
5. Start the development server.
    ```bash
    npm start
    ```
6. Navigate to [http://localhost:8080](http://localhost:8080) in your browser.

## Development Notes

### Prettier Formatting

To format your code with the Prettier formatter, run the following command:

```bash
npm run format
```

Prettier formatting configurations are stored in the `.prettierrc` file.

### Custom Favicon

1. Navigate to [https://favicon.io/favicon-converter/](https://favicon.io/favicon-converter/).
2. Upload your desired image.
3. Download the generated favicon.
4. Extract the contents of the downloaded archive.
5. Copy (and replace) the contents of the `favicon` directory to the `public` directory in your project.

#### Search Engine Optimization (SEO)

1. Edit the `description` and `keywords` meta tags in the `index.html` file in the `public` directory.
2. Edit the `short_name`, `name`, and `homepage` fields in the `manifest.json` file in the `public` directory.
