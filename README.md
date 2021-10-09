# kew
A single page landing site for Kevin Wilson to promote his voice acting business

## Setting up the project and building the navigation bar
### Directory structure and file setup
1. Create `index.html` and folders for javascript, scss, and images
   - `index.html`
   - `/app`
   - `/app/js`
   - `/app/scss`
   - `/images`
2. Create `.scss` files for styles, globals, and variables
   - `/app/scss/style.scss`
   - `/app/scss/_globals.scss`
   - `/app/scss/_variables.scss`
3. Import `_variables.scss` and `_globals.scss` into `style.scss`
   - `@import 'variables';`
   - `@import 'globals';`
4. Add css rules for `html`, `*`, and `body` tags in `_globals.scss`
  ```html {
      font-size: 100%;
      box-sizing: border-box;
  }

  *, *::before, *::after {
      box-sizing: inherit;
  }

  body {
      margin: 0;
      padding: 0;
      font-family: 'Raleway', sans-serif;
      line-height: 1.3;
  }```