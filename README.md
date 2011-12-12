## What's this project for?
This project rebuild the SQLite database from source code, and provide a static library for other projects to link with. This project added **FTS** support for SQLite.

## Why create such a project while iOS already provide sqlite library?
Because the SQLite library provided by Apple does not include FTS moudle. Thus, you can not use powerful SQLite FTS feature.

## How to use FTS with SQLite?
Visit SQLite's [official FTS page](http://www.sqlite.org/fts3.html) for more detailed information.

## License
SQLite is distributed in [Public Domain](http://en.wikipedia.org/wiki/Public_Domain), and does not require a license. This convient project is distributed in [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html), which means you can use it for open source/commercial software.