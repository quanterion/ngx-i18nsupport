<a name="0.6.2"></a>
# [0.6.2](https://github.com/martinroob/ngx-i18nsupport/compare/v0.6.1...v0.6.2) (2017-06-02)

### Bug Fixes

* **xliffmerge:** Improve error messages ([#31](https://github.com/martinroob/ngx-i18nsupport/issues/31)).

* **xliffmerge:** problems with parsing messages that contain same tag multiple times ([lib #26](https://github.com/martinroob/ngx-i18nsupport-lib/issues/26)).

<a name="0.6.1"></a>
# [0.6.1](https://github.com/martinroob/ngx-i18nsupport/compare/v0.6.0...v0.6.1) (2017-05-26)

### Bug Fixes

* **xliffmerge:** xlifffmerge emits wrong message 'WARNING: transferred 28 source references from master to "de" for format xtb' ([#28](https://github.com/martinroob/ngx-i18nsupport/issues/28)).

<a name="0.6.0"></a>
# [0.6.0](https://github.com/martinroob/ngx-i18nsupport/compare/v0.5.0...v0.6.0) (2017-05-25)

### Bug Fixes

* **xliffmerge:** Format xmb should create xtb files for translations. ([#25](https://github.com/martinroob/ngx-i18nsupport/issues/25)).
There is no migration tooling, so if you do have translated xmb files, you must manually correct them to xtb. 

* **xliffmerge:** File suffix change. For format XLIFF 2.0 the suffix of the generated files is `xlf` now (was `xlf2`, which is not correct).
If you already have such files, you should rename them before running xliffmerge. Otherwise they will not be merged.

### Features

* **xliffmerge:** xliffmerge does not merge the new source references. ([#24](https://github.com/martinroob/ngx-i18nsupport/issues/24))

* **xliffmerge:** For format XLIFF 2.0 source references are supported now.

<a name="0.5.0"></a>
# [0.5.0](https://github.com/martinroob/ngx-i18nsupport/compare/v0.4.0...v0.5.0) (2017-05-05)

### Features

* **xliffmerge:** added XLIFF 2.0 support. ([#20](https://github.com/martinroob/ngx-i18nsupport/issues/20))

<a name="0.4.0"></a>
# [0.4.0](https://github.com/martinroob/ngx-i18nsupport/compare/v0.3.1...v0.4.0) (2017-05-03)

### Bug Fixes

* **xliffmerge:** xliffmerge creates empty json files ([#18](https://github.com/martinroob/ngx-i18nsupport/issues/18))

### Features

* **xliffmerge:** create an API to access parsing functionality. ([#11](https://github.com/martinroob/ngx-i18nsupport/issues/11)). 
The API is in a separate npm package [ngx-i18nsupport-lib](https://github.com/martinroob/ngx-i18nsupport-lib).

* **xliffmerge:** use explicitly set IDs for ngx-translate data generation. ([#15](https://github.com/martinroob/ngx-i18nsupport/issues/15))
For detail have a look at the Wiki page [ngx translate usage](https://github.com/martinroob/ngx-i18nsupport/wiki/ngx-translate-usage).

* **xliffmerge:** Handle new source element introduced with Angular 4. ([#21](https://github.com/martinroob/ngx-i18nsupport/issues/21))

<a name="0.3.1"></a>
# [0.3.1](https://github.com/martinroob/ngx-i18nsupport/compare/v0.3.0...v0.3.1) (2017-04-25)

### Bug Fixes

* **xliffmerge:** compilation problem in WriterToString ([#19](https://github.com/martinroob/ngx-i18nsupport/issues/19))

<a name="0.3.0"></a>
# [0.3.0](https://github.com/martinroob/ngx-i18nsupport/compare/v0.2.3...v0.3.0) (2017-04-24)

### Features

* **xliffmerge:** Added useSourceAsTargetOption, allows empty translations if set to false.

<a name="0.2.1"></a>
# [0.2.1](https://github.com/martinroob/ngx-i18nsupport/compare/v0.2.0...v0.2.1) (2017-03-27)


### Bug Fixes

* **xliffmerge:** Wrong line endings in bin ([#12](https://github.com/martinroob/ngx-i18nsupport/issues/12))

<a name="0.2.0"></a>
# [0.2.0](https://github.com/martinroob/ngx-i18nsupport/compare/v0.1.0...v0.2.0) (2017-03-17)


### Bug Fixes

* **xliffmerge:** Wrong version displayed ([#2](https://github.com/martinroob/ngx-i18nsupport/issues/2)) (second try to fix it)
* **xliffmerge:** Code coverage display is too low ([#8](https://github.com/martinroob/ngx-i18nsupport/issues/8))

### Features

* **xliffmerge:** Added support for placeholders, linebreaks, embedded html ([#9](https://github.com/martinroob/ngx-i18nsupport/issues/9))
* **xliffmerge:** Added support for ngx-translate ([#5](https://github.com/martinroob/ngx-i18nsupport/issues/5))
* **documentation:** added ngx-translate integration page (as part of the wiki) ([#5](https://github.com/martinroob/ngx-i18nsupport/issues/5))

<a name="0.1.0"></a>
# [0.1.0](https://github.com/martinroob/ngx-i18nsupport/compare/v0.0.4...v0.1.0) (2017-03-10)


### Bug Fixes

* **xliffmerge:** Wrong version displayed ([#2](https://github.com/martinroob/ngx-i18nsupport/issues/2))

### Features

* **xliffmerge:** Added support for xmb format ([#4](https://github.com/martinroob/ngx-i18nsupport/issues/4))
* **xliffmerge:** languages can now be specified in the profile ([#6](https://github.com/martinroob/ngx-i18nsupport/issues/6))
* **documentation:** added Usage Tutorial (as part of the wiki) ([#3](https://github.com/martinroob/ngx-i18nsupport/issues/3))
* **documentation:** added this Changelog.md

<a name="0.0.4"></a>
# [0.0.4](https://github.com/martinroob/ngx-i18nsupport/compare/v0.0.3...v0.0.4) (2017-02-28)


### Bug Fixes

* **xliffmerge:** missing .npmignore prevents starting ([#1](https://github.com/martinroob/ngx-i18nsupport/issues/1))

<a name="0.0.3"></a>
# 0.0.3 (2017-02-24)

Initial version