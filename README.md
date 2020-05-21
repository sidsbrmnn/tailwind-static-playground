# Tailwind CSS Static Playground

A simple starter project for playing around with Tailwind in a proper PostCSS environment.

To get started:

1. Clone the repository:

    ```bash
    git clone https://github.com/sidsbrmnn/tailwind-static-playground.git tailwindcss-playground

    cd tailwindcss-playground
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

    Now you should be able to see the project running at localhost:8080.

4. Open `public/index.html` in your editor and start experimenting!

## Building for production

I've included both [Purgecss](https://www.purgecss.com/) and [cssnano](https://cssnano.co/) to optimize your CSS for production.

To build an optimized version of your CSS, simply run:

```bash
npm run build
```

After that's done, check out `./public/dist/tailwind.css` to see the optimized output.
