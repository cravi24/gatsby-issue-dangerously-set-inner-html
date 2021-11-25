<p align="center">
  <a href="https://www.gatsbyjs.com/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>

### Issue

Need to add custom scripts or execute JS code. There are some workarounds like crating HTML component and adding scripts from there but couldn't find a way to pass a prop from page context to this `HTML` component

### Steps to reproduce

- Clone the repo
- Install dependencies
- Run `npm run start`. `custom.js` code is not executed
- Run `npm run build && npm run serve`. `custom.js` code is
  executed
