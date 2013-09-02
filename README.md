Object Oriented Programming library, with different levels of granularity, from raw object manipulation to powerful classes creation. All aimed at creating a better API in the end.

# Introduction

If you don't know anything about this project, please refer the the [introduction](https://github.com/ymeine/oop/wiki/Introduction) article in the wiki.

## Project architecture

The project started from an existing code base. It has been taken from [`ymeine/editor-tools`](https://github.com/ymeine/editors-tools), branch [`utlimate-poc`](https://github.com/ymeine/editors-tools/tree/ultimate-poc), commit [59c05b4205feec0f6ca660b8347e4fb135536862](https://github.com/ymeine/editors-tools/tree/59c05b4205feec0f6ca660b8347e4fb135536862), path [`ultimate-poc/resources/app/node_modules/std`](https://github.com/ymeine/editors-tools/tree/59c05b4205feec0f6ca660b8347e4fb135536862/ultimate-poc/resources/app/node_modules/std), and adapted. Please refer to it for any history (unfortunately mixed with the rest of the project).

A re-engineered version of the library is developed in another branch, from scratch, and in LiveScript instead of JavaScript. Of course, knowledge from the first version as well as changes made to it will be used for that new version.

So to have a working version, use what's available on the master branch, for the new version, see branch [`v2`](https://github.com/ymeine/oop/tree/v2).

# File system layout

* [`README.md`](./README.md): this current file
* [`.gitignore`](./.gitignore): Git related file
* [`LICENSE`](./LICENSE): License of the project
* [`package.json`](./package.json): npm package definition
* [`src`](./): sources of the project
* `node_modules`: 3rd party libraries installed through npm

# Versioning

To ignore:

* `node_modules`: generated from [`package.json`](./package.json)

# Contribute

## Development

For a sort of backlog, see [issues](https://github.com/ymeine/oop/issues) tagged with `todo` and not associated to the milestone `v2`.

Guidelines will be published in the [wiki](https://github.com/ymeine/oop/wiki) of this project (or a less specific one).
