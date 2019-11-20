### NEXUS United reveal.js template

This repo contains spryker usergroup presentation.
Demo: https://tasteless-passenger.surge.sh

### Presentation History

Select a branch from the github UI to view the conference summary.

### Full setup

1. Install [Node.js](http://nodejs.org/) (9.0.0 or later)

1. Clone the this repository
   ```sh
   $ git clone https://github.com/nexusnetsoftgmbh/nexusrevealjs.git
   ```

1. Navigate to the reveal.js folder
   ```sh
   $ cd nexusrevealjs
   ```
1. Create a new branch from master with the conference name and date (e.g `symfonyLiveBerlin2019`)

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
   
1. Add your slides to `index.html`

1. Add the link to the Hosten Version into the readme


### Deployement

```sh
npm install --global surge
surge # inside your project directory
```
  
See [surge.sh documentation](https://surge.sh/) for more
   
### Contributors

thx @ **[mschulera](https://github.com/mschulera)** for the styling in our corporate identity design
