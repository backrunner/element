# better-element-ui

This repo is a modded version of [element-ui](https://github.com/elemefe).

I fixed some issues in original version by add codes from some PR that waiting for merging (and may never merge to master) in original repo.

IMPORTANT: MODIFICATION MAY CAUSE SOME UNKNOWN ISSUES, PLEASE USE THIS CAREFULLY.

## Usage

// vue.config.js
module.exports = {
  configureWebpack: {
    resolve: {
      alias: {
        'element-ui': '@pwpapp/better-element-ui',
      },
    },
  },
};

## LICENSE

MIT
