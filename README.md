# SvelteKit Frontend Mentor Template

Taking on a challenge from Frontend Mentor? Want to use Sveltekit, Typescript, and Sass?

This project template sets up the tools you need, as well as some basic style reset and layouts styles that many of Frontend Mentor's challenges need.

## Basics

- Download the starter files for your Frontend Mentor Project.

- Clone this repo using the CLI or by downloading the zip. Change the directory name to whatever you want.

  - Update the project name in `package.json`
  - Run `npm i`

- Drag and drop the images from the starter files into `src/lib/imgs`. You will then use Svetle's `import * from $lib/image.jpg` functionality to use the assets in your project.

- Use the `style-guide.md` form the starter files to set global Sass variables in `src/lib/styles/global.scss`. You do not need to `@import` or `@use` this file in any of your components or routes, it is already hooked up in the `svelte.config`.

- The `+layout.svelte` file is what is responsible for any background images or Google Fonts. I also put the FEM attribution footer here.

- The `+page.svelte` is the default spot for you to build your FEM component. Copy/paste anything from the starter file's `index.html` here. Something simple like the QR Code or NTF Preview can just live here. If you are creating something more complex, consider making custom components or routes.

- Before you begin any serious work, run `git init && git add -A && git commit -m "Initial commit"`

## Details

- This template uses the svelte-preprocessor, not Vite's. Documentation can be found here.

- `/Design` is in the gitignore, so you can drag the FEM design pictures into the root folder and it won't be added to your git history.

- The style reset is from
