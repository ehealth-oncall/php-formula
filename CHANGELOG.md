# Changelog

# [1.6.0](https://github.com/saltstack-formulas/php-formula/compare/v1.5.1...v1.6.0) (2022-03-14)


### Continuous Integration

* update linters to latest versions [skip ci] ([8befefc](https://github.com/saltstack-formulas/php-formula/commit/8befefcfbe50378691cf199f900cf2ca8ba4339f))
* **gemfile:** allow rubygems proxy to be provided as an env var [skip ci] ([4f54474](https://github.com/saltstack-formulas/php-formula/commit/4f5447451d28137f488bcb20313d6c30fe3e9dd8))
* **kitchen+ci:** update with `3004` pre-salted images/boxes [skip ci] ([def6993](https://github.com/saltstack-formulas/php-formula/commit/def69936b47bfd0e65e521a3b2629b591e2a11ca))
* **kitchen+ci:** update with latest CVE pre-salted images [skip ci] ([ded03de](https://github.com/saltstack-formulas/php-formula/commit/ded03de05e777a4c3b0a1aad8de650470c244d6a))
* **kitchen+gitlab:** update for new pre-salted images [skip ci] ([2e98aed](https://github.com/saltstack-formulas/php-formula/commit/2e98aed831e0adcfdc7f34df7c29529614a4ce0e))
* **vagrant:** replace FreeBSD 12.2 with 12.3 [skip ci] ([4e5af98](https://github.com/saltstack-formulas/php-formula/commit/4e5af9875abd9e4149db2d3e10c9f6dfcca435f2))


### Features

* **modules:** add `xmlrpc` and `xmlreader` as FreeBSD `xml` module ([67e565f](https://github.com/saltstack-formulas/php-formula/commit/67e565f5e2ce83c26a79267f25317e6e4340a73e))


### Tests

* **system:** add `build_platform_codename` [skip ci] ([f159202](https://github.com/saltstack-formulas/php-formula/commit/f1592024d507873415debcdc03aa2c885af2e4cf))

## [1.5.1](https://github.com/saltstack-formulas/php-formula/compare/v1.5.0...v1.5.1) (2021-09-17)


### Bug Fixes

* **module:** include php version in redis module package name ([2f62f6f](https://github.com/saltstack-formulas/php-formula/commit/2f62f6fa4edcd660dc6247d11b99e871d963adcb))
* **module:** include php version in redis module package name ([55939d5](https://github.com/saltstack-formulas/php-formula/commit/55939d5cd12cc8e91b5502e7181f8d826464e82d))


### Continuous Integration

* **3003.1:** update inc. AlmaLinux, Rocky & `rst-lint` [skip ci] ([c7a0c3c](https://github.com/saltstack-formulas/php-formula/commit/c7a0c3c3ea73a42a9e4682c204a620a3f7f2f2ee))
* **freebsd:** update with latest pre-salted Vagrant boxes [skip ci] ([368ca34](https://github.com/saltstack-formulas/php-formula/commit/368ca34fabc10d7baffb1ea2c047cfe118f0569c))
* **gemfile+lock:** use `ssf` customised `inspec` repo [skip ci] ([fbf2518](https://github.com/saltstack-formulas/php-formula/commit/fbf25184558f07766b06b946f8af5b742ac7665a))
* **kitchen:** move `provisioner` block & update `run_command` [skip ci] ([9964b38](https://github.com/saltstack-formulas/php-formula/commit/9964b38aa31fc44742a856bda5cdffd6aeb91a2a))
* **kitchen+ci:** update with latest `3003.2` pre-salted images [skip ci] ([f8e4ba0](https://github.com/saltstack-formulas/php-formula/commit/f8e4ba0e88e58c72ed14b8e7cf4143a446fda74b))
* add Debian 11 Bullseye & update `yamllint` configuration [skip ci] ([c22aba7](https://github.com/saltstack-formulas/php-formula/commit/c22aba797e7bd02200a7a9d3b13ba95bd2195fca))
* **kitchen+gitlab:** remove Ubuntu 16.04 & Fedora 32 (EOL) [skip ci] ([4891bf6](https://github.com/saltstack-formulas/php-formula/commit/4891bf6e77b90e6ec1a80160f48f86869aa46b88))


### Tests

* **_mapdata:** add verification file for `debian-11` [skip ci] ([9b05109](https://github.com/saltstack-formulas/php-formula/commit/9b05109c28d05ebc11c253eabbd6bb219e7726ff))
* **alma+rocky:** add platforms (based on CentOS 8) [skip ci] ([f55d512](https://github.com/saltstack-formulas/php-formula/commit/f55d5128ab10e9b21bbe315f4588ff13c74de68a))

# [1.5.0](https://github.com/saltstack-formulas/php-formula/compare/v1.4.0...v1.5.0) (2021-06-17)


### Continuous Integration

* add `arch-master` to matrix and update `.travis.yml` [skip ci] ([6dc94ca](https://github.com/saltstack-formulas/php-formula/commit/6dc94cae109a98e3d317b890bc86c9353a9e6fbe))
* **kitchen+gitlab:** adjust matrix to add `3003` [skip ci] ([ace2ca9](https://github.com/saltstack-formulas/php-formula/commit/ace2ca9241698bb9035fbc9df9dc9ffe73a20bed))
* **vagrant:** add FreeBSD 13.0 [skip ci] ([378a66a](https://github.com/saltstack-formulas/php-formula/commit/378a66a4bd0e9ee1d50ec3986773d4be930aa822))
* **vagrant:** use pre-salted boxes & conditional local settings [skip ci] ([3173cc0](https://github.com/saltstack-formulas/php-formula/commit/3173cc08511aa99dd645571c9961f097db283e53))


### Documentation

* **readme:** add `Testing with Vagrant` section [skip ci] ([48a0f1f](https://github.com/saltstack-formulas/php-formula/commit/48a0f1f95ca2fad6bb6c88520642e6815a50357a))


### Features

* **mods:** add `bcmath` module for FreeBSD ([6381ad4](https://github.com/saltstack-formulas/php-formula/commit/6381ad46347862cd3ab78cbedc7cf3b85572d513))
* **mods:** add `soap` module for FreeBSD ([7eef994](https://github.com/saltstack-formulas/php-formula/commit/7eef994582ca9ea894368eb37826d9fd3d9cc878))
* **mods:** add `xsl` module for FreeBSD ([4c9ed02](https://github.com/saltstack-formulas/php-formula/commit/4c9ed0295ce039ef32a4f881f944f0ac82c108df))


### Tests

* **_mapdata:** add verification file for `fedora-34` [skip ci] ([cfa76bd](https://github.com/saltstack-formulas/php-formula/commit/cfa76bdf0442be31ff681dc135fd9b3788232a45))
* **freebsd:** add `map.jinja` verification file (for 13.0) ([8510473](https://github.com/saltstack-formulas/php-formula/commit/8510473f36fc8101cb43bf2a2f29fd79a39158f2))
* **mods:** update integration tests accordingly ([b776b00](https://github.com/saltstack-formulas/php-formula/commit/b776b00168497f23f9afd843a442d44773ea19d0))

# [1.4.0](https://github.com/saltstack-formulas/php-formula/compare/v1.3.5...v1.4.0) (2021-03-31)


### Continuous Integration

* enable Vagrant-based testing using GitHub Actions ([a0306ce](https://github.com/saltstack-formulas/php-formula/commit/a0306cee31439cbbe34cdbdef2e26fc597306592))
* **gemfile+lock:** use `ssf` customised `kitchen-docker` repo [skip ci] ([009dab4](https://github.com/saltstack-formulas/php-formula/commit/009dab4dee008259ca5643da6496bb21d28a13f5))
* **kitchen+ci:** use latest pre-salted images (after CVE) [skip ci] ([e762a51](https://github.com/saltstack-formulas/php-formula/commit/e762a51387660694b53e5340f808446a6f9d28b7))
* **kitchen+gitlab-ci:** use latest pre-salted images [skip ci] ([daa4c9e](https://github.com/saltstack-formulas/php-formula/commit/daa4c9ef43da8bbe45d5068c280dbd85cad17809))
* **pre-commit:** update hook for `rubocop` [skip ci] ([08332f5](https://github.com/saltstack-formulas/php-formula/commit/08332f5b6f4f69bf4a612289e50772ce93a73e04))


### Features

* **composer:** make dependencies configurable ([d727b15](https://github.com/saltstack-formulas/php-formula/commit/d727b15557e2223cd82fe5fde0bc16365e20ebb8))


### Tests

* **freebsd:** add specific tests for FreeBSD ([cb2758d](https://github.com/saltstack-formulas/php-formula/commit/cb2758d86e181356c1fbb9a6c5450d22a011418b))
* **pillar:** list PHP versions for FreeBSD 11.4/12.2 (using `7.4`) ([b876d6b](https://github.com/saltstack-formulas/php-formula/commit/b876d6b1f0d1002712dc33c8525bee4622142947))
* standardise use of `share` suite & `_mapdata` state [skip ci] ([bf6a758](https://github.com/saltstack-formulas/php-formula/commit/bf6a7582b74369935e4a9e1a7291119587eca4ba))
* **_mapdata:** add verification files for new platforms ([610cfee](https://github.com/saltstack-formulas/php-formula/commit/610cfee03119cf29958b59edd4880d9200837f67))
* **share:** standardise with latest changes [skip ci] ([147c996](https://github.com/saltstack-formulas/php-formula/commit/147c996a696d8d9ceb409e8497e97a49cbc18d7e))

## [1.3.5](https://github.com/saltstack-formulas/php-formula/compare/v1.3.4...v1.3.5) (2021-01-14)


### Bug Fixes

* **_mapdata:** ensure map data is directly under `values` ([579a613](https://github.com/saltstack-formulas/php-formula/commit/579a61371a59db75971ecd6e0526125e7388198d))


### Tests

* **_mapdata:** update for `_mapdata/init.sls` change ([b30f514](https://github.com/saltstack-formulas/php-formula/commit/b30f5146d0dcf546d6ce26dcb9eafbc462a00fe0))

## [1.3.4](https://github.com/saltstack-formulas/php-formula/compare/v1.3.3...v1.3.4) (2020-12-23)


### Code Refactoring

* **map:** use top-level `values:` key in `map.jinja` dumps ([46ad65e](https://github.com/saltstack-formulas/php-formula/commit/46ad65e39eff11eba8bd8dfbfb0a0b52e4e79cfb))


### Continuous Integration

* **pre-commit:** enable `rubocop` linter after fix ([71dbf34](https://github.com/saltstack-formulas/php-formula/commit/71dbf345d6a5d1701c6012277ae8215d2f7c1dc5))

## [1.3.3](https://github.com/saltstack-formulas/php-formula/compare/v1.3.2...v1.3.3) (2020-12-22)


### Continuous Integration

* **commitlint:** ensure `upstream/master` uses main repo URL [skip ci] ([6ea8950](https://github.com/saltstack-formulas/php-formula/commit/6ea8950307db990b93f6e92dc19108c392a11bea))
* **gitlab-ci:** add `rubocop` linter (with `allow_failure`) [skip ci] ([992e934](https://github.com/saltstack-formulas/php-formula/commit/992e9348c71ff02ada8443751c8423eb7eb83576))


### Tests

* fix rubocop violations ([1a4d208](https://github.com/saltstack-formulas/php-formula/commit/1a4d20877ce9ff7e5c09ba38ff4ea4b2502e0665))
* **_mapdata:** generate verification files ([f88fdf7](https://github.com/saltstack-formulas/php-formula/commit/f88fdf784ab67ff5083f2e06ee6f5f5aa90b42fb))
* **map:** verify `map.jinja` dump using `_mapdata` state ([e9591db](https://github.com/saltstack-formulas/php-formula/commit/e9591db3551073ad9b7a747b848702dc4f75a22c))

## [1.3.2](https://github.com/saltstack-formulas/php-formula/compare/v1.3.1...v1.3.2) (2020-12-16)


### Continuous Integration

* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([8720cc1](https://github.com/saltstack-formulas/php-formula/commit/8720cc1708d4b24e532290e61da8aea8a593a8d4))
* **gitlab-ci:** use GitLab CI as Travis CI replacement ([15ed749](https://github.com/saltstack-formulas/php-formula/commit/15ed749de43b1a24b4f86a71cf9272a46b71042e))
* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([4cd9a3a](https://github.com/saltstack-formulas/php-formula/commit/4cd9a3a2137f02e1e9234512959491d421cb1e24))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([8dd9c54](https://github.com/saltstack-formulas/php-formula/commit/8dd9c545dba022c06778c1b9a802bb40b9101c66))
* **pre-commit:** add to formula [skip ci] ([5d71e0b](https://github.com/saltstack-formulas/php-formula/commit/5d71e0b24e376393d89b9c6d0439de1de4ef1b0d))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([7f73dbb](https://github.com/saltstack-formulas/php-formula/commit/7f73dbbf31dc8a6208c73ec583a3bed7161ae04c))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([ab6338e](https://github.com/saltstack-formulas/php-formula/commit/ab6338e6d49c0882e856a27db12738efa0fe2abf))
* **travis:** add notifications => zulip [skip ci] ([b64b1c2](https://github.com/saltstack-formulas/php-formula/commit/b64b1c2b08a2ac853f40d7c0d9d7991a92396f74))
* **workflows/commitlint:** add to repo [skip ci] ([b30a6bd](https://github.com/saltstack-formulas/php-formula/commit/b30a6bd8a70c2e0a5ef32382f08f475d95fdcf1a))


### Styles

* **libtofs.jinja:** use Black-inspired Jinja formatting [skip ci] ([1def34c](https://github.com/saltstack-formulas/php-formula/commit/1def34c36847174a0fbfad6da679dcc2c4df5fcb))

## [1.3.1](https://github.com/saltstack-formulas/php-formula/compare/v1.3.0...v1.3.1) (2020-04-20)


### Documentation

* add example to use a specific php version when using multiple ones ([53068f7](https://github.com/saltstack-formulas/php-formula/commit/53068f73b0bc0e40ce80fea4eac1e8fb0f159808))

# [1.3.0](https://github.com/saltstack-formulas/php-formula/compare/v1.2.3...v1.3.0) (2020-02-27)


### Bug Fixes

* **libtofs:** “files_switch” mess up the variable exported by “map.jinja” [skip ci] ([dca51de](https://github.com/saltstack-formulas/php-formula/commit/dca51de154d8dcbe5e141673322d39c4e1b6f7a6))
* **map.jinja:** fix pid file location for debian ([393d69e](https://github.com/saltstack-formulas/php-formula/commit/393d69eb0fda49f3598d5f9040be5d3bad59b5dd))


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([d7c188e](https://github.com/saltstack-formulas/php-formula/commit/d7c188e73c0fd9a109f997c52aa84e5c30a0bbf6))
* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([dd796b0](https://github.com/saltstack-formulas/php-formula/commit/dd796b070c3922f043078b181922d8a4ba0c33b2))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([109df07](https://github.com/saltstack-formulas/php-formula/commit/109df0781d6832d46cd48162280ead4976ec403d))


### Documentation

* **readme:** fix broken sub-heading [skip ci] ([51dd6e9](https://github.com/saltstack-formulas/php-formula/commit/51dd6e9bf292e7b13e19a7aa81df21045ebeb99b))


### Features

* **odbc:** add odbc module support ([8b69034](https://github.com/saltstack-formulas/php-formula/commit/8b69034c5b59dda60ac1ef128e4d381eec2db52b))

## [1.2.3](https://github.com/saltstack-formulas/php-formula/compare/v1.2.2...v1.2.3) (2019-12-02)


### Bug Fixes

* **map.jinja:** fix useflags regex (gentoo) ([39b1307](https://github.com/saltstack-formulas/php-formula/commit/39b130767104a5486c99f14df593669ee3705f01))
* **release.config.js:** use full commit hash in commit link [skip ci] ([d8f279f](https://github.com/saltstack-formulas/php-formula/commit/d8f279f9cd75e30f1276c7f5dae6b48827670421))


### Continuous Integration

* **kitchen:** use `debian-10-master-py3` instead of `develop` [skip ci] ([fc9ad29](https://github.com/saltstack-formulas/php-formula/commit/fc9ad298747d2df6714c3bcc3f4c166a0fae6630))
* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([97b7a36](https://github.com/saltstack-formulas/php-formula/commit/97b7a36aa7a22278c86ea81853d32a6a0172a481))
* **kitchen+travis:** upgrade matrix after `2019.2.2` release [skip ci] ([85e1f0e](https://github.com/saltstack-formulas/php-formula/commit/85e1f0ec25fe3ec0b99271a053f41ea7657f4d15))
* **travis:** apply changes from build config validation [skip ci] ([3862c37](https://github.com/saltstack-formulas/php-formula/commit/3862c37d06f3a57202d7b5b42a572aa6bbfaa839))
* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([0bb68c5](https://github.com/saltstack-formulas/php-formula/commit/0bb68c5b1796087215c254afde7b63fbed893fb2))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([0090c91](https://github.com/saltstack-formulas/php-formula/commit/0090c91b606f6d4ed5926d1b1985f2a1867b49af))
* **travis:** run `shellcheck` during lint job [skip ci] ([298a7d6](https://github.com/saltstack-formulas/php-formula/commit/298a7d61c26902c0193c887705e290158e866d23))
* **travis:** update `salt-lint` config for `v0.0.10` [skip ci] ([5c7d1aa](https://github.com/saltstack-formulas/php-formula/commit/5c7d1aa5016705da9645161e96e6be676866bc41))
* **travis:** use build config validation (beta) [skip ci] ([bcc0690](https://github.com/saltstack-formulas/php-formula/commit/bcc0690c8ac5f462d1dd5fb28d4f563987126a28))
* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([75f8d4d](https://github.com/saltstack-formulas/php-formula/commit/75f8d4dcb8cc6431f9bbc43dab97ece141d16d74))


### Documentation

* **contributing:** remove to use org-level file instead [skip ci] ([8aee949](https://github.com/saltstack-formulas/php-formula/commit/8aee949cab703e4d989c20c000a628bfbf1c6fcb))
* **readme:** update link to `CONTRIBUTING` [skip ci] ([05d112f](https://github.com/saltstack-formulas/php-formula/commit/05d112f63b5ebf0e117d2c181fdc02cf8ea6dbac))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([56d7314](https://github.com/saltstack-formulas/php-formula/commit/56d73148b31bb2f81adedb023748cd8a461ee0e3))

## [1.2.2](https://github.com/saltstack-formulas/php-formula/compare/v1.2.1...v1.2.2) (2019-10-10)


### Bug Fixes

* **composer.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/php-formula/commit/4e48a7a))
* **map.jinja:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/php-formula/commit/01f5ede))
* **repo.sls:** fix `salt-lint` errors ([](https://github.com/saltstack-formulas/php-formula/commit/b4d994c))


### Continuous Integration

* merge travis matrix, add `salt-lint` & `rubocop` to `lint` job ([](https://github.com/saltstack-formulas/php-formula/commit/a5a8a95))

## [1.2.1](https://github.com/saltstack-formulas/php-formula/compare/v1.2.0...v1.2.1) (2019-10-07)


### Bug Fixes

* **pillar.example:** fix `yamllint` error ([1b1747a](https://github.com/saltstack-formulas/php-formula/commit/1b1747a)), closes [/travis-ci.org/myii/php-formula/builds/594703019#L208-L210](https://github.com//travis-ci.org/myii/php-formula/builds/594703019/issues/L208-L210)


### Continuous Integration

* **kitchen:** change `log_level` to `debug` instead of `info` ([b86237e](https://github.com/saltstack-formulas/php-formula/commit/b86237e))
* **kitchen:** install required packages to bootstrapped `opensuse` [skip ci] ([20be85a](https://github.com/saltstack-formulas/php-formula/commit/20be85a))
* **kitchen:** use bootstrapped `opensuse` images until `2019.2.2` [skip ci] ([f70ebd2](https://github.com/saltstack-formulas/php-formula/commit/f70ebd2))
* **platform:** add `arch-base-latest` (commented out for now) [skip ci] ([55d5df1](https://github.com/saltstack-formulas/php-formula/commit/55d5df1))

# [1.2.0](https://github.com/saltstack-formulas/php-formula/compare/v1.1.1...v1.2.0) (2019-09-13)


### Continuous Integration

* use `dist: bionic` & apply `opensuse-leap-15` SCP error workaround ([76a2f76](https://github.com/saltstack-formulas/php-formula/commit/76a2f76))
* **yamllint:** add rule `empty-values` & use new `yaml-files` setting ([6f6d4bc](https://github.com/saltstack-formulas/php-formula/commit/6f6d4bc))


### Features

* **tofs:** implementation for all file.managed ([8e79a35](https://github.com/saltstack-formulas/php-formula/commit/8e79a35))

## [1.1.1](https://github.com/saltstack-formulas/php-formula/compare/v1.1.0...v1.1.1) (2019-09-05)


### Continuous Integration

* **kitchen+travis:** replace EOL pre-salted images ([c9eea17](https://github.com/saltstack-formulas/php-formula/commit/c9eea17))


### Tests

* **suse:** update version to `7.0` for `opensuse-leap-15` ([fd67570](https://github.com/saltstack-formulas/php-formula/commit/fd67570))

# [1.1.0](https://github.com/saltstack-formulas/php-formula/compare/v1.0.1...v1.1.0) (2019-09-05)


### Bug Fixes

* **fpm:** be sure to restart all Php instances in case of multi-versions ([d4772f9](https://github.com/saltstack-formulas/php-formula/commit/d4772f9))
* **tests:** don't test services on Suse and RedHat ([23214bf](https://github.com/saltstack-formulas/php-formula/commit/23214bf))
* **xdebug:** fix xdebug package name ([496ec28](https://github.com/saltstack-formulas/php-formula/commit/496ec28))
* **yamllint:** use separate suite for `ubuntu` ([6cba4af](https://github.com/saltstack-formulas/php-formula/commit/6cba4af)), closes [#174](https://github.com/saltstack-formulas/php-formula/issues/174)


### Code Refactoring

* **macro:** extract file_requisites macro ([d26c4f8](https://github.com/saltstack-formulas/php-formula/commit/d26c4f8))


### Continuous Integration

* **kitchen:** add test pillars for Debian and call some states ([d4fc842](https://github.com/saltstack-formulas/php-formula/commit/d4fc842))


### Features

* **repo:** add repo pattern so we can set distro repo during tests ([3c9efc7](https://github.com/saltstack-formulas/php-formula/commit/3c9efc7))


### Styles

* **spec:** remove empty lines ([dc12a0b](https://github.com/saltstack-formulas/php-formula/commit/dc12a0b))


### Tests

* **config:** add tests on Php config ([6555cf0](https://github.com/saltstack-formulas/php-formula/commit/6555cf0))
* **package:** fix package spec in case of multi Php versions ([59f648c](https://github.com/saltstack-formulas/php-formula/commit/59f648c))
* **service:** add tests on Php services ([baeac04](https://github.com/saltstack-formulas/php-formula/commit/baeac04))
* **ubuntu:** fix tests on Ubuntu distro ([b13bed2](https://github.com/saltstack-formulas/php-formula/commit/b13bed2))

## [1.0.1](https://github.com/saltstack-formulas/php-formula/compare/v1.0.0...v1.0.1) (2019-08-26)


### Bug Fixes

* **pillar:** fix pillar.get still looking under 'ng' namespace ([378b5b1](https://github.com/saltstack-formulas/php-formula/commit/378b5b1))

# [1.0.0](https://github.com/saltstack-formulas/php-formula/compare/v0.41.1...v1.0.0) (2019-08-26)


### Features

* **ng:** promote NG formula ([57b37dd](https://github.com/saltstack-formulas/php-formula/commit/57b37dd)), closes [#183](https://github.com/saltstack-formulas/php-formula/issues/183)


### BREAKING CHANGES

* **ng:** all previous `php` based configurations must be reviewed;
`php.ng` usage must be promoted to `php` and any uses of the original
`php` will have to be converted.

## [0.41.1](https://github.com/saltstack-formulas/php-formula/compare/v0.41.0...v0.41.1) (2019-08-26)


### Documentation

* **readme:** remove duplicate contents (local) ([f16796a](https://github.com/saltstack-formulas/php-formula/commit/f16796a))

# [0.41.0](https://github.com/saltstack-formulas/php-formula/compare/v0.40.1...v0.41.0) (2019-08-26)


### Features

* **ng:** promote NG formula ([f1b71d0](https://github.com/saltstack-formulas/php-formula/commit/f1b71d0))

## [0.40.1](https://github.com/saltstack-formulas/php-formula/compare/v0.40.0...v0.40.1) (2019-08-17)


### Bug Fixes

* **map:** fix missing value for php.lookup.fpm.user in multi-php mode ([f91d942](https://github.com/saltstack-formulas/php-formula/commit/f91d942))

# [0.40.0](https://github.com/saltstack-formulas/php-formula/compare/v0.39.2...v0.40.0) (2019-08-17)


### Features

* **yamllint:** include for this repo and apply rules throughout ([571cc4b](https://github.com/saltstack-formulas/php-formula/commit/571cc4b))

## [0.39.2](https://github.com/saltstack-formulas/php-formula/compare/v0.39.1...v0.39.2) (2019-08-13)


### Bug Fixes

* **tests:** fix package name for debian ([4f75eac](https://github.com/saltstack-formulas/php-formula/commit/4f75eac))

## [0.39.1](https://github.com/saltstack-formulas/php-formula/compare/v0.39.0...v0.39.1) (2019-08-12)


### Bug Fixes

* **installed.jinja:** remove `include` to prevent conflicting IDs ([cb11784](https://github.com/saltstack-formulas/php-formula/commit/cb11784)), closes [#188](https://github.com/saltstack-formulas/php-formula/issues/188)

# [0.39.0](https://github.com/saltstack-formulas/php-formula/compare/v0.38.1...v0.39.0) (2019-08-07)


### Bug Fixes

* **php/ng:** don't iterate on string, make sure list is not string ([dbb542c](https://github.com/saltstack-formulas/php-formula/commit/dbb542c))


### Documentation

* **pillar.example:** add example for alternatives with multiversion ([23a6ec1](https://github.com/saltstack-formulas/php-formula/commit/23a6ec1))
* **pillar.example:** example of versions ([a98aa7e](https://github.com/saltstack-formulas/php-formula/commit/a98aa7e))


### Features

* **php/ng:** support for php cli multiversion ([bb4a077](https://github.com/saltstack-formulas/php-formula/commit/bb4a077))
* **php/ng:** support the use of a list of php versions ([b303239](https://github.com/saltstack-formulas/php-formula/commit/b303239)), closes [#138](https://github.com/saltstack-formulas/php-formula/issues/138)


### Styles

* **pillar.example:** add line break ([38fe58f](https://github.com/saltstack-formulas/php-formula/commit/38fe58f))

## [0.38.1](https://github.com/saltstack-formulas/php-formula/compare/v0.38.0...v0.38.1) (2019-08-03)


### Bug Fixes

* update deprecation version number in `semantic-release` run ([a87fb91](https://github.com/saltstack-formulas/php-formula/commit/a87fb91)), closes [/github.com/saltstack-formulas/php-formula/pull/175#issuecomment-517492613](https://github.com//github.com/saltstack-formulas/php-formula/pull/175/issues/issuecomment-517492613) [/github.com/saltstack-formulas/php-formula/pull/185#issuecomment-517603898](https://github.com//github.com/saltstack-formulas/php-formula/pull/185/issues/issuecomment-517603898)

# [0.38.0](https://github.com/saltstack-formulas/php-formula/compare/v0.37.1...v0.38.0) (2019-08-01)


### Features

* **map:** add xmlrpc package for xml module, as it was done for SUSE ([a09ef92](https://github.com/saltstack-formulas/php-formula/commit/a09ef92))

## [0.37.1](https://github.com/saltstack-formulas/php-formula/compare/v0.37.0...v0.37.1) (2019-08-01)


### Bug Fixes

* add warning message for ng states ([d45bae8](https://github.com/saltstack-formulas/php-formula/commit/d45bae8))
* allow muting deprecation warning via. pillar/config entry ([8e7471e](https://github.com/saltstack-formulas/php-formula/commit/8e7471e))
* change message to warn about upcoming deprecation ([e97eeae](https://github.com/saltstack-formulas/php-formula/commit/e97eeae))
* warn formula users ng states will be promoted in `v1.0.0` ([d033381](https://github.com/saltstack-formulas/php-formula/commit/d033381))
* **pillar_from_files:** use `{}` pillar files to ensure tests pass ([1a5d734](https://github.com/saltstack-formulas/php-formula/commit/1a5d734))
* **readme:** add warning in  docs/README.rst ([3ac59e4](https://github.com/saltstack-formulas/php-formula/commit/3ac59e4))

# [0.37.0](https://github.com/saltstack-formulas/php-formula/compare/v0.36.0...v0.37.0) (2019-07-09)


### Bug Fixes

* **mods:** fixup for [#181](https://github.com/saltstack-formulas/php-formula/issues/181) ([e2d7b4b](https://github.com/saltstack-formulas/php-formula/commit/e2d7b4b))


### Features

* **mods:** added some mods support for FreeBSD ([3f6c0bc](https://github.com/saltstack-formulas/php-formula/commit/3f6c0bc))

# [0.36.0](https://github.com/saltstack-formulas/php-formula/compare/v0.35.1...v0.36.0) (2019-06-29)


### Documentation

* **readme:** update with modules, bz2 & dba ([5e04187](https://github.com/saltstack-formulas/php-formula/commit/5e04187))


### Features

* add 'bz2' and 'dba' module support ([758ae88](https://github.com/saltstack-formulas/php-formula/commit/758ae88))

## [0.35.1](https://github.com/saltstack-formulas/php-formula/compare/v0.35.0...v0.35.1) (2019-06-28)


### Documentation

* merge latest changes from `template-formula` ([4af569a](https://github.com/saltstack-formulas/php-formula/commit/4af569a)), closes [#179](https://github.com/saltstack-formulas/php-formula/issues/179)

# [0.35.0](https://github.com/saltstack-formulas/php-formula/compare/v0.34.0...v0.35.0) (2019-06-27)


### Features

* **semantic-release:** add support of semantic-release ([cdd206a](https://github.com/saltstack-formulas/php-formula/commit/cdd206a))
