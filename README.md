# IDMX 11ty Sass Starter
## Prayer Poem
### This assignment showcases a poem called prayer by Ella Wheeler Wilcox this poem advocates self-reliance and personal responsibility. It suggests using one's own judgment and effort to navigate life's challenges. While emphasizing the importance of individual agency, the poem also acknowledges the role of prayer as a source of guidance and support. Ultimately, it promotes a balanced approach that combines self-reliance with seeking divine assistance when needed.

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small><br>
[Image](https://unsplash.com/photos/ReEqHw2GyeI)<br>
[Poem](https://www.public-domain-poetry.com/ella-wheeler-wilcox/prayer-33000)