
# Change Log

Change log for postcss-lazysprite. [Details at Github](https://github.com/Jeff2Ma/postcss-lazysprite)

## [2.1.4] - 2018-06-08

- Update Dependencies.

## [2.1.0] - 2018-06-08

- Fix svg id different in win / mac.

## [2.0.0] - 2018-06-01

- Support for SVG Sprites.

- Remove `smartUpdate` option.

- Update DevDependencies.

## [1.8.2] - 2018-05-28

- Dropped support for Node 4 and Node 5.

- Update DevDependencies.

## [1.8.0] - 2018-02-28

- `new Buffer` -> `Buffer.from`.

- Remove `gulp-util`.

## [1.7.0] - 2017-11-14

- Fix orders issue in mac and win's difference.

## [1.6.2] - 2017-08-07

- Update `pseudoClass` option.

## [1.6.1] - 2017-06-23

- Update `rev-hash` to version 2.0.

## [1.6.0] - 2017-05-24

- Remove `positionUnit` option.

- Remove hasSourceImg obj.

## [1.5.0] - 2017-05-11

- Fix bug when with second or more depth directory css files.

- Fix bug with basename like 'icon2' in v1.3.0.

- Add support for PostCSS 6.0.

- Add support for gulp-postcss 7.0.

- Deprecated option `stylesheetPath` and repalce with `stylesheetRelative`.

- Add option `stylesheetInput`.

- Add alert for incorrect `2x` or `3x` dimensions.

- Add better dimensions stylesheet (`width`/`hegith` decls) output way.

> If you are going to upgrade from v1.3.x, please see [readme](README.md) to set option again. :)


## [1.3.0] - 2017-04-21

- Fix bug with basename like 'icon2'.

## [1.2.3] - 2017-04-08

- Change logLevel, 'already existed' info not show in slient logLevel.

## [1.2.2] - 2017-03-31

- Support for better css format result.

## [1.2.1] - 2017-03-28

- Change log output prefix.

## [1.2.0] - 2017-03-27

- Support deleting old sprites when with `smartUpdate` option.

- Change absolute path to relative path in output log.

## [1.1.0] - 2017-03-23

- Add `pseudoClass` option for `:hover` and`:active` condition.

## [1.0.0] - 2017-02-12

- Add smart update mod for high performance.

- Add logLevel to control log output level.

- Add support for dynamic class name `block` part.

- Add support sprites with`:hover` and`:active` condition.

- Add more examples and tests.

## [0.1.4] - 2017-01-12

- 	Fix wrong readme demo which will confuse users.

## [0.1.3] - 2017-01-12

- 	Fix wrong english grammar.

## [0.1.2] - 2017-01-11

- 	Add better alert when with wrong dirname.

## [0.1.1] - 2017-01-11

- 	Fix path problem on Windows stystem.

## [0.1.0] - 2017-01-09

- Migrate from `Q` to `Bluebird` as promise libary.

- Support 3x retina.

- Support `@2x`, `@3x`, `_2x`, `_3x` suffix.

- Add eslint for better code stander.

- All comments are English.

## [0.0.1] - 2016-12-30

- Initial release.
