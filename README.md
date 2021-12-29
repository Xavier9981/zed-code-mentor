# Zed Code Mentor
This is my personal blog site where I share unbiased articles on web development for beginners in Zambia. The website is operating using the new system called JAMStack which is an architecture of building static websites. 

Now all this is archived with a couple addition technologies like the static site generetor netlify and eleventy.

The starting files used by [Xavier K Muneku] in the `Zed-Code-Mentor` folder are:

- `node_modules` this folder is automatically added upon the installation of eleventy.
- `public` folder containing all of my public facing folders and files.
- `src` folder basically has the same files and folders as the `public` folder.
- `.eleventy.js` configuration of eleventy to figure out the location for all the folders and files it can't find for itself.
- `.gitignore` untracked files that Git should ignore.
- `LICENSE` handles all the copyright documentation.
- `package-lock.json` The goal of package-lock.json file is to keep track of the exact version of every package that is installed so that our product is 100% reproducible in the same way even if packages are updated by their maintainers.
- `package.json` this file is the heart of our Node project. It records important metadata about our project which is required before publishing to NPM, and also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package.

The `src` folder also has:
- `html` and `nunjucks` files that are to be templated and used as a base for different page layouts. 
- `assets` folder has all the documents, images and logos. 
- `blog` folder that containers all the blogs added to the site.
- `css` folder for styling the pages.
- `pages` folder has the sub `nunjucks` and `html` files.
- `script` folder has `javascript` code snippets.