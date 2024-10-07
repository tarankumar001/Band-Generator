# Band Generator

A simple web application that generates random band names based on randomly selected adjectives and nouns. This project uses Node.js with Express for the server-side logic, and EJS as the templating engine to render dynamic content.

## Features

- Generates random band names based on predefined adjectives and nouns.
- Dynamic content rendering using EJS.
- Simple, minimalistic UI with basic CSS.
- Dynamic footer with the current year.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web framework for Node.js.
- **EJS**: Embedded JavaScript templates for rendering views.
- **body-parser**: Middleware for parsing request bodies.
- **CSS**: Styling for the application.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/tarankumar001/Band-Generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Band-Generator
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. Open your browser and navigate to:

   ```
   http://localhost:3000
   ```

## Usage

- Open the home page.
- Click the "Generate Name" button to generate a random band name.
- The generated name will be displayed on the page.

## Project Structure

```
- /public               # Contains static files (CSS, images, etc.)
  - /css
    - styles.css        # Main CSS file for styling

- /views                # EJS templates for rendering views
  - /partials           # EJS partials (header, footer)
    - header.ejs
    - footer.ejs
  - index.ejs           # Main template for rendering the homepage

- index.js              # Main Node.js server file
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b your-feature-branch`.
3. Make your changes and commit them: `git commit -m "Add your commit message"`.
4. Push your changes to your fork: `git push origin your-feature-branch`.
5. Create a pull request on GitHub.
