# ticktack-builder

## Setup

```shell
$ npm clone https://github.com/.../ticktack-builder
$ cd ticktack-builder
$ npm install
$ git clone https://github.com/.../ticktack app
```

The latest app source should be in `./app`

## Stamp Release

```shell
$ cd ticktack-builder
$ npm run update
$ npm run release
```

Output to `./dist`

## dependencies

You'll need some more dependencies to create builds.

See the `electron-builder` wiki page: [Multi Platform Build](https://github.com/electron-userland/electron-builder/wiki/Multi-Platform-Build)

On linux you'll need a few more deps:

```
sudo apt-get install icnsutils graphicsmagick
```
