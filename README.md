# Best practices and code conventions

  > The ultimate goal is to have our whole codebase look like the same person wrote it.

  *work in progress*

  * [Workflow](https://github.com/infektweb/conventions/blob/master/docs/workflow.md)
  * [JavaScript](https://github.com/infektweb/conventions/blob/master/docs/javascript.md)
  * [DB](https://github.com/infektweb/conventions/blob/master/docs/db.md)
  * [CSS/SASS](https://github.com/infektweb/conventions/blob/master/docs/css.md)
  * [React + Flux](https://github.com/infektweb/conventions/blob/master/docs/react-flux.md)

## ESLint

  * Use these configs for a new project: [eslint-config-infektweb](https://github.com/infektweb/eslint-config-infektweb)
  * Add an ESLint plugin to your IDE/editor. For example:
    * [Atom](https://atom.io/)
      * [linter](https://atom.io/packages/linter)
      * [linter-eslint](https://atom.io/packages/linter-eslint)
    * [Sublime Text](http://www.sublimetext.com/)
      * [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)
      * [Sublime​Linter-contrib-eslint](https://packagecontrol.io/packages/SublimeLinter-contrib-eslint)

## Shellcheck

  Used to lint bash scripts.

  * Install shellcheck [shellcheck](https://github.com/koalaman/shellcheck#installing)
    * [Atom](https://atom.io/)
      * First you have to install the [linter](https://atom.io/packages/linter) from above.
        * Add plugin [linter-shellcheck](https://atom.io/packages/linter-shellcheck)
    * [Sublime Text](http://www.sublimetext.com/)
      * First you have to install the [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter) from above.
        * Add plugin [SublimeLinter-shellcheck](https://packagecontrol.io/packages/SublimeLinter-shellcheck)
