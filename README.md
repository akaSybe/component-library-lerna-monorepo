# component-library-lerna-monorepo

Experimental project to setup component library where every component is an standalone npm package

## TODO

- [x] Lerna setup
- [х] Conventional commit
- [x] Editorconfig
- [x] Prettier
- [x] husky + lint-staged
- [ ] ESLint
- [ ] Babel 7
- [ ] SCSS
- [ ] Browserslist
- [ ] Jest
- [ ] Storybook
- [ ] Typescript
- [ ] Template to generate new component
- [ ] Changelog generation
- [ ] Package publishing
- [ ] CI

### Development

Clone repository

Run `npm install`

Bootstrap lerna project using `npm run bootstrap`

Run in terminal `npm run local-npm-registry` to setup local [Verdaccio](https://www.verdaccio.org/) registry

Then run in another terminal `local-npm-registry:prepare` to create default user

Verdaccio should be runned when you want to push packages

#### EditorConfig

Most editors (IDE) respect this file and use its settings for repository.

Check [official site](https://editorconfig.org/) for more info.

Plugin for Visual Studio Code – [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

#### Prettier

Code should be formatted with Prettier. Staged files will be formatted before commit.

#### husky + lint-staged

Allow to define hooks on different Git events
