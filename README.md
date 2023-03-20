# Valantic CEC reveal.js template

This repo contains Reveal.js boilerplate code in our corporate identity design.
> Select a branch from the Github UI to view already created presentations.

### Workflow

1. Create a new branch with a meaningful name
2. Make your changes, replace the content of this readme with `README_TEMPLATE.md` & push it
3. Your presentation will now be automatically deployed with [Surge.sh](https://surge.sh) onto the following URL `https://val-BRANCH-NAME.surge.sh`
4. Alternatively you can get the URL from the [Github actions tab](https://github.com/nexusunited/valantic-revealjs/actions)

### Full setup

1. Install [Node.js](http://nodejs.org/) (10.0.0 or later)

1. Clone the repository
   ```sh
   $ git clone https://github.com/nexusunited/valantic-revealjs.git
   ```

1. Navigate to the reveal.js folder
   ```sh
   $ cd valantic-revealjs
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.

### How to use different templates

Change the template by exchanging the css file.

```html
<link rel="stylesheet" href="dist/theme/<theme>.css">
```

The following themes follow the coperate identity guidelines:

- valantic-simple
- valantic-dark
- valantic-color


### Additions
If you add some custom JS logic or style improvements to your presentation, consider making a pull request back into this repository
