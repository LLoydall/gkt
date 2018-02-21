## GKT

This package is totally useless and only use for analytics purposes for PM2.
When we started working on PM2, there was no analytics available on NPM so we simply make a **optional** dependency to monitor these.
For example we made a little website that show them in realtime on https://map.keymetrics.io


## FAQ

- It fail installing when i'm behind a corporate proxy ! Help
  - It should not, that's why it's an optional dependency, you should try with `--no-optional`
- You need to remove it from PM2 for my company to use it
  - We still use it for analytics so it's not possible right now. You can still ask for specific license without the package at sales@keymetrics.io

Do not hesitate to open an issue if you have any questions

## License

MIT License Copyright (c) 2018 Keymetrics

