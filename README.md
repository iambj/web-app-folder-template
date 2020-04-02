# Readme

[![LICENSE](https://img.shields.io/badge/license-MIT-green)](https://github.com/iambj/web-app-folder-template/blob/master/LICENSE)

This is a basic folder structure to to set up a new web project.

It is mainly for Node.JS and React.JS apps but would be fine for other projects such as a static website.

Some ideas and files pull from the [HTML5 Boilerplate](https://html5boilerplate.com/) project. Many things have been removed to make this more versatile. I got tired of downloading and stripping HTML5 Boilerplate every time I started a new project.

## Usage

Download or clone from this repo into your desired location:

    git clone --depth=1 https://github.com/iambj/web-app-folder-template.git

This clones with a shallow copy which is more suitable for a boilerplate. To start from a fresh Git history, delete the .git folder.

All app development work and resources should go in the `src` folder. These are files that are to be deployed. Ideally your build process would build this folder and create a package in the `dist` folder. The `public` folder should be for public facing web documents that most likely would be served by a web server (i.e. Nginx or Apache). The root folder (where this readme is) should contain config and build files.

If you are using React.JS, it will not allow `create-react-app` to run in a non-empty folder, so you will need to copy files from here to your react app or use this as a checklist.

Without using React, you can run `npm build` to compile JavaScript using Babel.

_Note: Be sure to edit the files as necessary because they are customized for repetitive use by myself._

### TODO

- [ ] Fix up babel
- [ ] Simplify CSS files
- [ ] CSS build process
- [ ] Server configs
- [ ] npm init version
