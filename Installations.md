# Installations

A list of how to install complicated stuff.

## Table of contents

- [Tailwind CSS](#tailwind-css)

  ## Tailwind CSS

  1. cd Into your project folder and run the command
     ```bash
     npm install tailwindcss @tailwindcss/vite
     ```

2. In your `vite.config.ts` file, import tailwindcss, then call it as a function in the plugins array in the arguement passed into the `defineConfig` function being called and exported in the file.

3. Import tailwind css at the top of your css file. Import without “url()”. import as
```css
@import "tailwindcss";
```
