<p align="center"><img src="/src/medias/political-avatar.svg" alt="Political Avatar" width="200"></p>

# Despolitizador

[![Netlify Status](https://api.netlify.com/api/v1/badges/a0990c78-c967-47c2-b9ff-562b477324f7/deploy-status)](https://app.netlify.com/sites/despolitizador/deploys)
[![license](https://img.shields.io/github/license/felipefialho/despolitizador.svg)](./license.md)
[![GitHub contributors](https://img.shields.io/github/contributors/felipefialho/despolitizador.svg)](https://github.com/felipefialho/despolitizador/graphs/contributors)

> To translate political language for people's language

[View project](https://despolitizador.felipefialho.com/)

## Add new words

It is simple, you need to access the [`src/library.json`](https://github.com/felipefialho/despolitizador/edit/master/src/library.json), add the new word and submit a pull request. 

Example:

```json
  "vossa excelência": "mano"
```

It need that all words in our library.json using the correct grammar.

## Getting Started

This project uses Pug, Stylus and Webpack.


```sh
# Clone this repository
$ git clone git@github.com:felipefialho/despolitizador.git
$ cd despolitizador

# install dependencies
$ npm i

# Run the project
$ npm start

```

With the commands above, you have everything to start.

### Post CSS libs

For grid system uses [Autoprefixer](https://github.com/postcss/autoprefixer) to make easy use browser prefixes, [Lost](https://github.com/peterramsing/lost) with some help from, [Rucksack](http://simplaio.github.io/rucksack/) for animations, reset and a lot of great mixins, [Rupture](https://github.com/jenius/rupture) for responsive utilities. And [Font Magician](https://github.com/jonathantneal/postcss-font-magician/) to get the webfonts.

### Code Standards

This project uses my own [Coding Style](https://github.com/felipefialho/coding-style) as code reference.

To help you, this project has a `npm run fix` command to fix all eslint errors.

### Tasks

- `npm start`: run all tasks and initialize watch for changes and a server
- `npm run build`: run all production tasks create a `dist` folder to deploy
- `npm run lint`: lint javascript and css
- `npm run fix`: command to fix all eslint errors

## Credits

Thanks [marcelokohl](https://github.com/marcelokohl) for the ideia to name of project 😄

## License

MIT License © Felipe Fialho
