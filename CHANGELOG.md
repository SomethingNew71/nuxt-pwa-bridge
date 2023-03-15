# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 4.0.0 (2023-03-15)


### ⚠ BREAKING CHANGES

* Requeires Node 10.x
* **workbox:** default changed from NetworkOnly to NetworkFirst when offlinePage is enabled
* needs nuxt 2.x or later
* webpack >= 4 (Nuxt >= 2) is required

### Features

* `pwa.` scopped options ([010fe0e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/010fe0e0ec0266c39392c831020d477bbb0e3acc))
* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c0efb1d2f9923f227ffbb5421ec285c97d3daca6))
* add HMR test suit ([ff3d502](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/ff3d5023b0c91b2795889297143a293077b293fb))
* add og:image support ([#30](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/30)) ([afebd96](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/afebd962d2047c5e9efd039b6832e8503632fcce))
* add oneSignal module ([bbc7b72](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/bbc7b72b3742643c02b8c82276359e43bf60ee87))
* add option to register third-party sw ([#12](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/12)) ([9c0b61e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9c0b61e3e22754fb1de9ab43ecb049791822eb2e))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b17bbd04dc67778004392da91841092e55847d37))
* add types ([#323](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/323)) ([8723d07](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/8723d076cb87ff9e583ba755f72f4d62360d6eb1))
* cleanupOutdatedCaches ([9167013](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/91670138999cb3039b42ee9b398b6bcafe7db650))
* **icon:** add combined option sources ([539430f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/539430fdf540e2f0be8ebd6417454ad0a316c9b0))
* **icon:** add support for icon purpose ([#246](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/246)) ([9248174](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9248174fe8bac352318c8fe292012156ccfd56ad))
* **icon:** allow reading icon from assetc/icon.png ([#29](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/29)) ([9e0fde3](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9e0fde33df9e6fe3e3c275f577ad91f92e180433))
* **icon:** default purpose to any + maskable ([30f0f63](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/30f0f63bcd1601cc6aa5595a851de965dde9af88))
* **icon:** expose options.cacheDir ([f8dbf1d](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/f8dbf1dac99519648a53dc22ab4019af25a677aa))
* **icon:** make icons accessible ([#51](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/51)) ([92bccd3](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/92bccd37cf2e1b2471ea3d70126a7428a983b083))
* **icon:** new options ([#126](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/126)) ([12e6576](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/12e65762e995f9f270e3b88ed1938990d49d0607))
* **icon:** register `favicon.ico` when available ([#258](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/258)) ([7a48d2a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7a48d2a60b1f2ccaa1287789adb846806afd5224))
* **icon:** rename `accessibleIcons` to `iconPlugin` ([3e175f9](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/3e175f93c046028b6f3f9479085ec98d014b460b))
* **icon:** support for iOS splash screens ([#308](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/308)) ([f4eeda7](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/f4eeda7ce05cdd7dda4e4c4ab81e986f6c94a951))
* **icon:** update to jimp 0.5.0 ([b071c4b](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b071c4b437d8cf5a51721129131f19f7ff13e586))
* improve computed cacheId ([cd6c9cc](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/cd6c9cc6d7233145d212379aac514c3bc339a493))
* improve sw.register error handling ([9aa76f8](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9aa76f89bdf34cefc018ae602a2514bf9ea38944))
* **manifest:** add `useWebmanifestExtension` option and improve docs ([#241](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/241)) ([4484e6c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/4484e6c697c5534103969894252f1d356d4016ee))
* **manifest:** add revision to start_url ([ad26827](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/ad26827a9d76b6a4f1123f8a06fd0c946b90b5dd))
* **manifest:** allow overriding publicPath ([#19](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/19)) ([4e6782e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/4e6782ed7d261055b40cbc0678624c74d89897c1))
* **manifest:** support crossorigin option ([#71](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/71)) ([ccb2c33](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/ccb2c339e9092c162c29dab9c36bb7cfdd51883a))
* **meta:** add author property ([#41](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/41)) ([cafcfc4](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/cafcfc40eb020a03c0f39d2a121c4f1a54e915b6))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/3c7aa7d0199ce3ab0d7fff606d52b913dba0f34e)), closes [#10](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/42)) ([3990ddf](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/3990ddf325bfe092d7590dee4ca6877cc638c4dc))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/dc39fcbaa2fa63ecf909c0183b0a55b3f3ad2397))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/43)) ([fe11c76](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/fe11c76941ba53eb85659c3cd9a970924f51abf3))
* **meta:** merge head at runtime ([#363](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/363)) ([c0d86ea](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c0d86ead374efcfd66282959e65055262e4a27cf))
* **module:** allow disabling with top-level options ([65800f9](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/65800f91a671e61d59a9faf885c2ff7ecc9d9ca0))
* offlineAnalytics ([#55](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/55)) ([4c4d3ff](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/4c4d3ff93f16eb25ce51027a43e559e2da8a601f))
* ogSiteName ([#50](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/50)) ([0c99ab9](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/0c99ab94cb8f6f06e0658f958345609f31da7748))
* **onesignal:** enable CDN by default ([7c78c67](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7c78c679283f6314bc9e7695411b962fd9f835ce))
* **onesignal:** move init options under init ([dd61c18](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/dd61c18093ada4ed936c08b6a25a96d7f93cdfbb))
* options.dev ([fb0d38c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/fb0d38cdaec4821f479222b038d88a1a56d06e19))
* remove debug ([92ba73e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/92ba73e9cccca6c3561d8b6a0b27b00ccf86f720))
* rewrite icon with async image resizer ([#171](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/171)) ([a4a457e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/a4a457efe98461cf28249742952ca49e9ebfe847))
* rewrite workbox ([#122](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/122)) ([9e49896](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9e49896be3f89b15116c60a6ddebf71d62a131c9))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/fdcda0f420b01f637e9ddd8b7ad127c8e5cf2e86))
* support `manifest.fileName` with template ([f05353b](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/f05353b7ccfef88f5f95f0fa7b0109c2ece4236b)), closes [#193](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/193)
* sync workbox version with workbox-window ([9a3632a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9a3632a8cda8d66c454d76bf633a0ebf14218487))
* update onesignal sdk once ([c08e423](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c08e4231991d849eb1c7c63942109f034afaee3e))
* use `jimp-compact` ([5e37b58](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/5e37b58a3c6b07062ab012d3c53641e2d9e7302a))
* use better regexes ([318228e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/318228e8a88a97f4a50e86ebf4b784acd48f523d))
* use integraty file to invalidate icon cache ([6661a09](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/6661a09f86bbc169a99effac3d9cb1620f530b3d))
* **worbox:** add offline option for making it optional ([#59](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/59)) ([76de33c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/76de33cc4f7dde9e1b930be773add3736851a95e)), closes [#24](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/24)
* **worbox:** offlineAssets ([#86](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/86)) ([27c8fa1](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/27c8fa1b5c89a1f2ae044a1eac8028757bfa029b))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/5ac89cffdb7b9462172399f7789a4f56031fb53d))
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/f1e1fe127c7a9e15e74dbed243194c68a6422ed2))
* **workbox:** allow cache names to be configured ([#154](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/154)) ([2d7ed53](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/2d7ed53a3e66fa8d9607591ddfc9225ecbc7744a))
* **workbox:** assetsURLPattern, pagesURLPattern ([5fc3d66](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/5fc3d66856d9d932c66b8c6b0a72362ff01c2758))
* **workbox:** bump to 4.0.0-rc.2 ([7e278f0](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7e278f0d3cf37a8c9b7ba6d06fd85ceb464abd0e))
* **workbox:** change the order of default runtimeCache ([#106](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/106)) ([033b504](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/033b50472bd4172ce562b9efb818d093458861c5))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/e7677d8c317aa4c189dfe563a2ec5e279d53d691))
* **workbox:** enabled option and self destroying sw ([c64226c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c64226cea36c1b0b9f0efe7640439e6bb134ddce))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/a5ddf5992c61ee759a292d1af95a2cf0daac9d73))
* workboxExtensions and extension reading fixes ([5c56484](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/5c564844047e86484ace65bfcffbdf542528e420))
* **workbox:** importScripts option ([7c8644c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7c8644cbf612a5686e590074a2848e10cf9c37c8))
* **workbox:** improve sw.register ([c35f610](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c35f6104a66ef125a0d33f8e32ee8f5f9a1cfc28))
* **workbox:** make plugin fully asynchronous ([1eb1190](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/1eb11905a7499cb3b886265969a939d55eb53ca1))
* **workbox:** offline page assets ([#85](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/85)) ([8bc4a3b](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/8bc4a3bbca296f9470f6ec7b63cef1abae810932))
* **workbox:** offlineStrategy ([e377436](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/e377436cedf7fc88288889a1021dfe2855e783b4))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/80)) ([88cc602](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/88cc60275d8e4cff46d20c99708bd34a689c2aba))
* **workbox:** preCaching option ([67f1c3d](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/67f1c3d1b839b05f2c09d436c4eec62675001030))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b0af84e0751bc023e33b6bc6923ae2a17fb8d0a1))
* **workbox:** support pass config object to `workbox.setConfig` ([#95](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/95)) ([b5dab8a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b5dab8a821eb474ecd5351cc2d779a4c17ed4802))
* **workbox:** upgrade workboxVersion to 4.0.0-rc.0 ([b364572](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b3645727e43817027bed6e32e1c06b8ad2bfb559))
* **workbox:** use workbox 4.0.0-0 ([70813ef](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/70813ef1146fa0a1db27534531f82b537d7e0f14))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/60)) ([0fef874](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/0fef874441e0b98230cb3a96d7035cdebcd294e4))
* **workbox:** workbox-window support ([2e356d0](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/2e356d059ee73810db5512fedbd92f92d9e2e822))


### Bug Fixes

* add workboxExtensions to defaults ([#138](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/138)) ([ac8ba74](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/ac8ba745b81ef339665661a7fa436ab48819d801))
* append to start_url without query param (fixes [#403](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/403)) ([054b8a2](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/054b8a299274fafc61275b50374b4eb1e83e7e46))
* avoid adding revision to start_url ([1c44cff](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/1c44cffbe1ae7c9096c5696d6b6521f60b3fe32f))
* **docs:** add reference to pwa module ([49b7c49](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/49b7c49b7b79b613bdbedc4fa3c97d5bff7feaa2))
* don't override title when titleTemplate is provided  ([#48](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/48)) ([8c3f319](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/8c3f319a0ca3983535c88feff2c444d544d3dd45))
* expose modified pwa context to the config ([c325e44](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c325e4434b940789309f80aa91b1e436363aa906))
* **icon:** await on build ([e3c1be2](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/e3c1be2c7804ec374116d0c177a1537b6c764042))
* **icon:** clean cacheDir when generating icons ([1e6eb19](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/1e6eb19851bbb6bcb51106cea5611475edec75cc))
* **icon:** fork without original process args ([#343](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/343)) ([8b1f19f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/8b1f19f56ddc31a49445334ddc8abe2162b4b760))
* **icon:** generate only on build ([9d68d70](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9d68d70bb8ce5d3f9ef23b98e305e8ac136d8ef2))
* **icon:** handle jimp.write callback ([bffe6ed](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/bffe6eda94e266e17e0dee7069a63393b6dc9455))
* **icon:** handle situation where the iconSrc is `null` or `undefined` ([#187](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/187)) ([66be874](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/66be874bbdbb9ba796e0406c63a455455bc4caf2))
* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/84)) ([3f0e718](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/3f0e71892f6d1c39090dad4107d74871f4a44446))
* **icon:** update warning url to docs ([#329](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/329)) ([61633fa](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/61633fa640793c344748efdf790a56456fad8e2f))
* **manifest:** do not use nuxt loading bar color as default `theme_color` ([#344](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/344)) ([a18a79f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/a18a79f62a49a3a563621929e30fc8703c3c133a))
* **manifest:** invalidate start_url cache ([240d4a1](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/240d4a14868fe46ab98bb79ba3a22c7973875d45))
* **manifest:** remove publicPath field ([b03dc14](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b03dc14b7c99cbf0eac9470f09b50d9089ea760a))
* **manifest:** run only on build ([ecaa835](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/ecaa8355f76d9bd9ea12392b557254b743548600))
* **meta:** add missing `hid` to icon tags ([#428](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/428)) ([d9addb7](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/d9addb7917363e812fe277acc1cf228018a8342b))
* **meta:** add missing `router.base` prefix to favicon ([#354](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/354)) ([3e910ae](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/3e910ae7e87d341c6a6ea018d013105ce1721b5b))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/23)) ([76a1f89](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/76a1f89259224f195084515d4b88d05376e1402a))
* **meta:** allow setting `appleStatusBarStyle` without `mobileAppIOS` ([b0f226a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b0f226aadeee50b47790ac064852b444e33d9b95)), closes [#338](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/338)
* **meta:** avoid unnecessary log for meta.json ([de8e039](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/de8e039740a5618b59312682ecdea4f023d88414))
* **meta:** fix `mergeMeta` cjs export ([774f1a8](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/774f1a87d8c102ad3754374e53a41b434a01b82c))
* **meta:** fix issues regarding favicon.ico fallback ([7a1e773](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7a1e77384eb88f0886180bc784efa242ae59e5ad))
* **meta:** generate only on build ([1cace26](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/1cace266e3528aa53d5a562e3d7ce1fefff7f4dc))
* **meta:** load meta when `ssr` is disable and using `nuxt dev` (fixes [#219](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/219)) ([b6a5ead](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b6a5ead17cdb8f2edff9d12c326ae59d8ac372be))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/44)) ([354f818](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/354f818708e91cbabbbe97fdfaceecce90236689))
* **meta:** prevent build failure for ios splash image when no icon is used ([#362](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/362)) ([494eed5](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/494eed5db00e7cf6863fc854e6ccb6b7bb8c0ba4))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/cf48b3fb6c64fe4cbbac2ae8bb4474cbd21390b3)), closes [#10](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/10)
* **module:** handle readJSFiles for string param ([#143](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/143)) ([4f06479](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/4f064799cf01b95432b0f7d28b7010b60b9f4146))
* **module:** icon purpose warning appearing when it shouldn't ([#305](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/305)) ([5833e31](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/5833e311e0379f6617c845a4f319733047ef7a53))
* offlinePage syntax error ([af21d74](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/af21d7401a9f28932ed98a08cdf2363a708e6777))
* **onesignal:** add cache query to sw.js ([33f8f61](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/33f8f61ffac193c7ccdeeb65a294925253460e6f))
* **onesignal:** ensure no duplicate script is added ([#161](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/161)) ([89c1a1d](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/89c1a1da2a55125867c1ddae4cb7144ddb5ca6d5))
* path ogImage if is url ([#121](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/121)) ([d6dc82b](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/d6dc82b9c11b33735b9b27006855ca64994c15fd))
* precached files are not updated ([#386](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/386)) ([872dce1](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/872dce1ec2df58cbf6efcfe4a080f632510ea32b))
* **pwa-utils:** don't combine with esm ([fddfa7a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/fddfa7a687f043aaa4a3719a02f45b7cc803214a)), closes [#147](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/147)
* **pwa-utils:** ensure joinUrl not modifying scheme part ([09a465a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/09a465ac888c947fd8119a57f27c54c370694ee4))
* **pwa-utils:** handle non-strings in `startCase` ([#150](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/150)) ([782217a](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/782217aca8ea2ece277cb20eaee54b536d55435a))
* **pwa:** no more optimize dependency ([a1c149f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/a1c149f75b41976b3efe99e26a01d68f1c5af639))
* relax pages regex for workbox 4 compatiblity ([04e74a7](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/04e74a7843ea54bcebca491c9abc0daa7ede3515))
* revert compileTemplate as is fixed by nuxt/nuxt.js[#6283](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/6283) for 2.9.x ([d0f96de](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/d0f96de4f40cb33bb859ed8401205fcb70181747))
* routing order for default offline route (/.*). it must be last order ([#100](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/100)) ([1c829d0](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/1c829d01d23ca4fd40a23eecbfc24ce6be48e48d))
* serve static webpack assets from disk in dev mode (fixes [#373](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/373)) ([8298f95](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/8298f955bf80eb44090cfb7b56070dc7e1a50aa8))
* **serveStatic:** wrap serveStatic in `fromNodeMiddleware` for @nuxt/bridge compatibility (fixes [#532](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/532)) ([87457c7](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/87457c7d13dfc2bb2ea609c1c07a1388b3b53704))
* stateWhileRevalidate() -> networkOnly() ([832d60f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/832d60fc1364ddff608822e36d4a70c7eaa04f39))
* support build cache ([#371](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/371)) ([9a825c9](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9a825c9d47c057c5934030142cb6e46d23a46e21))
* truncate manifest hash ([5c74621](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/5c746218a5eafd21d51e5ad9fd330a2bcac04802))
* **types:** mark module options fields as optional ([#420](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/420)) ([7d75c28](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7d75c285485efde4081127ff3bb899565a771c7e))
* use shared pwa context ([3c19bae](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/3c19baebc0a1dba5e8b7ef20c7230e81ce6a8e95))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/a0fb9084462d5f212009ec80cf0c64142ff59126))
* **workbox:** add additional details for uncaught errors and fix chromium CORS ([#417](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/417)) ([f20489c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/f20489c2cc289b9d6f90143078f415d97b3cf4c1))
* **workbox:** add missing lodash dependency ([#91](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/91)) ([da2c36f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/da2c36f90668f9744cb5e8854b677037a70b862e))
* **workbox:** always prepend routerBase to swURL ([d3a52b6](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/d3a52b6e9e5672e06e69269152b9625ae1152b17)), closes [#157](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/157)
* **workbox:** deepClone options to avoid cross-build mutation ([e39027e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/e39027ee7159103d755fe67c1c105235f3257739))
* **workbox:** disable `cacheAssets` for dev mode ([dbf6d67](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/dbf6d67bea83a4e9376a77d46e449606f42c45bf))
* **workbox:** faster service worker register ([07524a2](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/07524a2d4e5605743660b6f0b1e0ceb74aa609ee))
* **workbox:** handle `offlinePage` options (fixes [#365](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/365)) ([2b9856e](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/2b9856e9c226c5f286acb5116cb381e2fc550248))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/73)) ([6d241ec](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/6d241ec8518945115f85892e99de910221420810))
* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/83). ([c7102fd](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/c7102fdede1f790044cdd7e88212997b4693d963))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/b744a270e16d418f826ab8035c184b4bbe3d4185))
* **workbox:** missing required parameter request for `handle()` ([#335](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/335)) ([eedf23f](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/eedf23fa3ab478f8a449817528d0270507babfc8))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/83). ([7a8bb3b](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/7a8bb3bf0469093b3f57a75d2a934860edee4fbf))
* **workbox:** New configuration for specifying plugins when configuring a strategy ([#337](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/337)) ([dacf7ec](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/dacf7ec3613a6cb985990eab6c78879b78bdbbbc)), closes [/github.com/nuxt-community/pwa-module/pull/337#issuecomment-681870522](https://github.com/somethingnew71//github.com/nuxt-community/pwa-module/pull/337/issues/issuecomment-681870522)
* **workbox:** precache `start_url` (resolves [#372](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/372)) ([27e19a0](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/27e19a04d6f2b14943a0bb4a9b7414382591d4e0))
* **workbox:** restore `sw.js` with smart build (fixes [#352](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/352)) ([491f440](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/491f440936e107c424864a1aa1121e6995d4e87b))
* **workbox:** unregister only to avoid loop ([44c5cd3](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/44c5cd3aa86f12929aeb03d37cfa20df5171f855))
* **workbox:** use NetworkFirst for dev ([9a67580](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9a67580badc5f3d80fc1d56f8b5a44dc4aebf60b))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/14). ([f384103](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/f384103e55b2109f8a6302fd4dcbeed13530163d))


* update execa to 4.x ([301a07c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/301a07cd8733b29231bdfbc0390681e59f5decb7))
* only support nuxt.hook ([854d826](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/854d826e05363a4a8756ed77159fcd532f11b353))
* use tapable hooks ([#103](https://github.com/somethingnew71/pwa-nuxt-bridge/issues/103)) ([9f27d5c](https://github.com/somethingnew71/pwa-nuxt-bridge/commit/9f27d5cdae0e0341d6d4b4f6814f91db6eab1432))

## 4.0.0 (2023-03-15)


### ⚠ BREAKING CHANGES

* Requeires Node 10.x
* **workbox:** default changed from NetworkOnly to NetworkFirst when offlinePage is enabled
* needs nuxt 2.x or later
* webpack >= 4 (Nuxt >= 2) is required

### Features

* `pwa.` scopped options ([010fe0e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/010fe0e0ec0266c39392c831020d477bbb0e3acc))
* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c0efb1d2f9923f227ffbb5421ec285c97d3daca6))
* add HMR test suit ([ff3d502](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ff3d5023b0c91b2795889297143a293077b293fb))
* add og:image support ([#30](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/30)) ([afebd96](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/afebd962d2047c5e9efd039b6832e8503632fcce))
* add oneSignal module ([bbc7b72](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/bbc7b72b3742643c02b8c82276359e43bf60ee87))
* add option to register third-party sw ([#12](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/12)) ([9c0b61e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9c0b61e3e22754fb1de9ab43ecb049791822eb2e))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b17bbd04dc67778004392da91841092e55847d37))
* add types ([#323](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/323)) ([8723d07](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8723d076cb87ff9e583ba755f72f4d62360d6eb1))
* cleanupOutdatedCaches ([9167013](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/91670138999cb3039b42ee9b398b6bcafe7db650))
* **icon:** add combined option sources ([539430f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/539430fdf540e2f0be8ebd6417454ad0a316c9b0))
* **icon:** add support for icon purpose ([#246](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/246)) ([9248174](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9248174fe8bac352318c8fe292012156ccfd56ad))
* **icon:** allow reading icon from assetc/icon.png ([#29](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/29)) ([9e0fde3](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9e0fde33df9e6fe3e3c275f577ad91f92e180433))
* **icon:** default purpose to any + maskable ([30f0f63](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/30f0f63bcd1601cc6aa5595a851de965dde9af88))
* **icon:** expose options.cacheDir ([f8dbf1d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f8dbf1dac99519648a53dc22ab4019af25a677aa))
* **icon:** make icons accessible ([#51](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/51)) ([92bccd3](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/92bccd37cf2e1b2471ea3d70126a7428a983b083))
* **icon:** new options ([#126](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/126)) ([12e6576](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/12e65762e995f9f270e3b88ed1938990d49d0607))
* **icon:** register `favicon.ico` when available ([#258](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/258)) ([7a48d2a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7a48d2a60b1f2ccaa1287789adb846806afd5224))
* **icon:** rename `accessibleIcons` to `iconPlugin` ([3e175f9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3e175f93c046028b6f3f9479085ec98d014b460b))
* **icon:** support for iOS splash screens ([#308](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/308)) ([f4eeda7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f4eeda7ce05cdd7dda4e4c4ab81e986f6c94a951))
* **icon:** update to jimp 0.5.0 ([b071c4b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b071c4b437d8cf5a51721129131f19f7ff13e586))
* improve computed cacheId ([cd6c9cc](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/cd6c9cc6d7233145d212379aac514c3bc339a493))
* improve sw.register error handling ([9aa76f8](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9aa76f89bdf34cefc018ae602a2514bf9ea38944))
* **manifest:** add `useWebmanifestExtension` option and improve docs ([#241](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/241)) ([4484e6c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4484e6c697c5534103969894252f1d356d4016ee))
* **manifest:** add revision to start_url ([ad26827](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ad26827a9d76b6a4f1123f8a06fd0c946b90b5dd))
* **manifest:** allow overriding publicPath ([#19](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/19)) ([4e6782e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4e6782ed7d261055b40cbc0678624c74d89897c1))
* **manifest:** support crossorigin option ([#71](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/71)) ([ccb2c33](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ccb2c339e9092c162c29dab9c36bb7cfdd51883a))
* **meta:** add author property ([#41](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/41)) ([cafcfc4](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/cafcfc40eb020a03c0f39d2a121c4f1a54e915b6))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3c7aa7d0199ce3ab0d7fff606d52b913dba0f34e)), closes [#10](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/42)) ([3990ddf](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3990ddf325bfe092d7590dee4ca6877cc638c4dc))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dc39fcbaa2fa63ecf909c0183b0a55b3f3ad2397))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/43)) ([fe11c76](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fe11c76941ba53eb85659c3cd9a970924f51abf3))
* **meta:** merge head at runtime ([#363](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/363)) ([c0d86ea](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c0d86ead374efcfd66282959e65055262e4a27cf))
* **module:** allow disabling with top-level options ([65800f9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/65800f91a671e61d59a9faf885c2ff7ecc9d9ca0))
* offlineAnalytics ([#55](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/55)) ([4c4d3ff](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4c4d3ff93f16eb25ce51027a43e559e2da8a601f))
* ogSiteName ([#50](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/50)) ([0c99ab9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/0c99ab94cb8f6f06e0658f958345609f31da7748))
* **onesignal:** enable CDN by default ([7c78c67](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7c78c679283f6314bc9e7695411b962fd9f835ce))
* **onesignal:** move init options under init ([dd61c18](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dd61c18093ada4ed936c08b6a25a96d7f93cdfbb))
* options.dev ([fb0d38c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fb0d38cdaec4821f479222b038d88a1a56d06e19))
* remove debug ([92ba73e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/92ba73e9cccca6c3561d8b6a0b27b00ccf86f720))
* rewrite icon with async image resizer ([#171](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/171)) ([a4a457e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a4a457efe98461cf28249742952ca49e9ebfe847))
* rewrite workbox ([#122](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/122)) ([9e49896](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9e49896be3f89b15116c60a6ddebf71d62a131c9))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fdcda0f420b01f637e9ddd8b7ad127c8e5cf2e86))
* support `manifest.fileName` with template ([f05353b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f05353b7ccfef88f5f95f0fa7b0109c2ece4236b)), closes [#193](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/193)
* sync workbox version with workbox-window ([9a3632a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9a3632a8cda8d66c454d76bf633a0ebf14218487))
* update onesignal sdk once ([c08e423](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c08e4231991d849eb1c7c63942109f034afaee3e))
* use `jimp-compact` ([5e37b58](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5e37b58a3c6b07062ab012d3c53641e2d9e7302a))
* use better regexes ([318228e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/318228e8a88a97f4a50e86ebf4b784acd48f523d))
* use integraty file to invalidate icon cache ([6661a09](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/6661a09f86bbc169a99effac3d9cb1620f530b3d))
* **worbox:** add offline option for making it optional ([#59](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/59)) ([76de33c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/76de33cc4f7dde9e1b930be773add3736851a95e)), closes [#24](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/24)
* **worbox:** offlineAssets ([#86](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/86)) ([27c8fa1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/27c8fa1b5c89a1f2ae044a1eac8028757bfa029b))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5ac89cffdb7b9462172399f7789a4f56031fb53d))
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f1e1fe127c7a9e15e74dbed243194c68a6422ed2))
* **workbox:** allow cache names to be configured ([#154](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/154)) ([2d7ed53](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/2d7ed53a3e66fa8d9607591ddfc9225ecbc7744a))
* **workbox:** assetsURLPattern, pagesURLPattern ([5fc3d66](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5fc3d66856d9d932c66b8c6b0a72362ff01c2758))
* **workbox:** bump to 4.0.0-rc.2 ([7e278f0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7e278f0d3cf37a8c9b7ba6d06fd85ceb464abd0e))
* **workbox:** change the order of default runtimeCache ([#106](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/106)) ([033b504](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/033b50472bd4172ce562b9efb818d093458861c5))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e7677d8c317aa4c189dfe563a2ec5e279d53d691))
* **workbox:** enabled option and self destroying sw ([c64226c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c64226cea36c1b0b9f0efe7640439e6bb134ddce))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a5ddf5992c61ee759a292d1af95a2cf0daac9d73))
* workboxExtensions and extension reading fixes ([5c56484](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5c564844047e86484ace65bfcffbdf542528e420))
* **workbox:** importScripts option ([7c8644c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7c8644cbf612a5686e590074a2848e10cf9c37c8))
* **workbox:** improve sw.register ([c35f610](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c35f6104a66ef125a0d33f8e32ee8f5f9a1cfc28))
* **workbox:** make plugin fully asynchronous ([1eb1190](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1eb11905a7499cb3b886265969a939d55eb53ca1))
* **workbox:** offline page assets ([#85](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/85)) ([8bc4a3b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8bc4a3bbca296f9470f6ec7b63cef1abae810932))
* **workbox:** offlineStrategy ([e377436](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e377436cedf7fc88288889a1021dfe2855e783b4))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/80)) ([88cc602](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/88cc60275d8e4cff46d20c99708bd34a689c2aba))
* **workbox:** preCaching option ([67f1c3d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/67f1c3d1b839b05f2c09d436c4eec62675001030))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b0af84e0751bc023e33b6bc6923ae2a17fb8d0a1))
* **workbox:** support pass config object to `workbox.setConfig` ([#95](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/95)) ([b5dab8a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b5dab8a821eb474ecd5351cc2d779a4c17ed4802))
* **workbox:** upgrade workboxVersion to 4.0.0-rc.0 ([b364572](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b3645727e43817027bed6e32e1c06b8ad2bfb559))
* **workbox:** use workbox 4.0.0-0 ([70813ef](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/70813ef1146fa0a1db27534531f82b537d7e0f14))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/60)) ([0fef874](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/0fef874441e0b98230cb3a96d7035cdebcd294e4))
* **workbox:** workbox-window support ([2e356d0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/2e356d059ee73810db5512fedbd92f92d9e2e822))


### Bug Fixes

* add workboxExtensions to defaults ([#138](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/138)) ([ac8ba74](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ac8ba745b81ef339665661a7fa436ab48819d801))
* append to start_url without query param (fixes [#403](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/403)) ([054b8a2](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/054b8a299274fafc61275b50374b4eb1e83e7e46))
* avoid adding revision to start_url ([1c44cff](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1c44cffbe1ae7c9096c5696d6b6521f60b3fe32f))
* **docs:** add reference to pwa module ([49b7c49](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/49b7c49b7b79b613bdbedc4fa3c97d5bff7feaa2))
* don't override title when titleTemplate is provided  ([#48](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/48)) ([8c3f319](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8c3f319a0ca3983535c88feff2c444d544d3dd45))
* expose modified pwa context to the config ([c325e44](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c325e4434b940789309f80aa91b1e436363aa906))
* **icon:** await on build ([e3c1be2](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e3c1be2c7804ec374116d0c177a1537b6c764042))
* **icon:** clean cacheDir when generating icons ([1e6eb19](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1e6eb19851bbb6bcb51106cea5611475edec75cc))
* **icon:** fork without original process args ([#343](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/343)) ([8b1f19f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8b1f19f56ddc31a49445334ddc8abe2162b4b760))
* **icon:** generate only on build ([9d68d70](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9d68d70bb8ce5d3f9ef23b98e305e8ac136d8ef2))
* **icon:** handle jimp.write callback ([bffe6ed](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/bffe6eda94e266e17e0dee7069a63393b6dc9455))
* **icon:** handle situation where the iconSrc is `null` or `undefined` ([#187](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/187)) ([66be874](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/66be874bbdbb9ba796e0406c63a455455bc4caf2))
* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/84)) ([3f0e718](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3f0e71892f6d1c39090dad4107d74871f4a44446))
* **icon:** update warning url to docs ([#329](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/329)) ([61633fa](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/61633fa640793c344748efdf790a56456fad8e2f))
* **manifest:** do not use nuxt loading bar color as default `theme_color` ([#344](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/344)) ([a18a79f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a18a79f62a49a3a563621929e30fc8703c3c133a))
* **manifest:** invalidate start_url cache ([240d4a1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/240d4a14868fe46ab98bb79ba3a22c7973875d45))
* **manifest:** remove publicPath field ([b03dc14](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b03dc14b7c99cbf0eac9470f09b50d9089ea760a))
* **manifest:** run only on build ([ecaa835](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ecaa8355f76d9bd9ea12392b557254b743548600))
* **meta:** add missing `hid` to icon tags ([#428](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/428)) ([d9addb7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d9addb7917363e812fe277acc1cf228018a8342b))
* **meta:** add missing `router.base` prefix to favicon ([#354](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/354)) ([3e910ae](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3e910ae7e87d341c6a6ea018d013105ce1721b5b))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/23)) ([76a1f89](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/76a1f89259224f195084515d4b88d05376e1402a))
* **meta:** allow setting `appleStatusBarStyle` without `mobileAppIOS` ([b0f226a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b0f226aadeee50b47790ac064852b444e33d9b95)), closes [#338](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/338)
* **meta:** avoid unnecessary log for meta.json ([de8e039](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/de8e039740a5618b59312682ecdea4f023d88414))
* **meta:** fix `mergeMeta` cjs export ([774f1a8](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/774f1a87d8c102ad3754374e53a41b434a01b82c))
* **meta:** fix issues regarding favicon.ico fallback ([7a1e773](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7a1e77384eb88f0886180bc784efa242ae59e5ad))
* **meta:** generate only on build ([1cace26](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1cace266e3528aa53d5a562e3d7ce1fefff7f4dc))
* **meta:** load meta when `ssr` is disable and using `nuxt dev` (fixes [#219](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/219)) ([b6a5ead](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b6a5ead17cdb8f2edff9d12c326ae59d8ac372be))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/44)) ([354f818](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/354f818708e91cbabbbe97fdfaceecce90236689))
* **meta:** prevent build failure for ios splash image when no icon is used ([#362](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/362)) ([494eed5](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/494eed5db00e7cf6863fc854e6ccb6b7bb8c0ba4))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/cf48b3fb6c64fe4cbbac2ae8bb4474cbd21390b3)), closes [#10](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/10)
* **module:** handle readJSFiles for string param ([#143](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/143)) ([4f06479](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4f064799cf01b95432b0f7d28b7010b60b9f4146))
* **module:** icon purpose warning appearing when it shouldn't ([#305](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/305)) ([5833e31](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5833e311e0379f6617c845a4f319733047ef7a53))
* offlinePage syntax error ([af21d74](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/af21d7401a9f28932ed98a08cdf2363a708e6777))
* **onesignal:** add cache query to sw.js ([33f8f61](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/33f8f61ffac193c7ccdeeb65a294925253460e6f))
* **onesignal:** ensure no duplicate script is added ([#161](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/161)) ([89c1a1d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/89c1a1da2a55125867c1ddae4cb7144ddb5ca6d5))
* path ogImage if is url ([#121](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/121)) ([d6dc82b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d6dc82b9c11b33735b9b27006855ca64994c15fd))
* precached files are not updated ([#386](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/386)) ([872dce1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/872dce1ec2df58cbf6efcfe4a080f632510ea32b))
* **pwa-utils:** don't combine with esm ([fddfa7a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fddfa7a687f043aaa4a3719a02f45b7cc803214a)), closes [#147](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/147)
* **pwa-utils:** ensure joinUrl not modifying scheme part ([09a465a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/09a465ac888c947fd8119a57f27c54c370694ee4))
* **pwa-utils:** handle non-strings in `startCase` ([#150](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/150)) ([782217a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/782217aca8ea2ece277cb20eaee54b536d55435a))
* **pwa:** no more optimize dependency ([a1c149f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a1c149f75b41976b3efe99e26a01d68f1c5af639))
* relax pages regex for workbox 4 compatiblity ([04e74a7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/04e74a7843ea54bcebca491c9abc0daa7ede3515))
* revert compileTemplate as is fixed by nuxt/nuxt.js[#6283](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/6283) for 2.9.x ([d0f96de](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d0f96de4f40cb33bb859ed8401205fcb70181747))
* routing order for default offline route (/.*). it must be last order ([#100](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/100)) ([1c829d0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1c829d01d23ca4fd40a23eecbfc24ce6be48e48d))
* serve static webpack assets from disk in dev mode (fixes [#373](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/373)) ([8298f95](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8298f955bf80eb44090cfb7b56070dc7e1a50aa8))
* **serveStatic:** wrap serveStatic in `fromNodeMiddleware` for @nuxt/bridge compatibility (fixes [#532](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/532)) ([87457c7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/87457c7d13dfc2bb2ea609c1c07a1388b3b53704))
* stateWhileRevalidate() -> networkOnly() ([832d60f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/832d60fc1364ddff608822e36d4a70c7eaa04f39))
* support build cache ([#371](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/371)) ([9a825c9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9a825c9d47c057c5934030142cb6e46d23a46e21))
* truncate manifest hash ([5c74621](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5c746218a5eafd21d51e5ad9fd330a2bcac04802))
* **types:** mark module options fields as optional ([#420](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/420)) ([7d75c28](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7d75c285485efde4081127ff3bb899565a771c7e))
* use shared pwa context ([3c19bae](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3c19baebc0a1dba5e8b7ef20c7230e81ce6a8e95))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a0fb9084462d5f212009ec80cf0c64142ff59126))
* **workbox:** add additional details for uncaught errors and fix chromium CORS ([#417](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/417)) ([f20489c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f20489c2cc289b9d6f90143078f415d97b3cf4c1))
* **workbox:** add missing lodash dependency ([#91](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/91)) ([da2c36f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/da2c36f90668f9744cb5e8854b677037a70b862e))
* **workbox:** always prepend routerBase to swURL ([d3a52b6](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d3a52b6e9e5672e06e69269152b9625ae1152b17)), closes [#157](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/157)
* **workbox:** deepClone options to avoid cross-build mutation ([e39027e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e39027ee7159103d755fe67c1c105235f3257739))
* **workbox:** disable `cacheAssets` for dev mode ([dbf6d67](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dbf6d67bea83a4e9376a77d46e449606f42c45bf))
* **workbox:** faster service worker register ([07524a2](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/07524a2d4e5605743660b6f0b1e0ceb74aa609ee))
* **workbox:** handle `offlinePage` options (fixes [#365](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/365)) ([2b9856e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/2b9856e9c226c5f286acb5116cb381e2fc550248))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/73)) ([6d241ec](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/6d241ec8518945115f85892e99de910221420810))
* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/83). ([c7102fd](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c7102fdede1f790044cdd7e88212997b4693d963))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b744a270e16d418f826ab8035c184b4bbe3d4185))
* **workbox:** missing required parameter request for `handle()` ([#335](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/335)) ([eedf23f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/eedf23fa3ab478f8a449817528d0270507babfc8))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/83). ([7a8bb3b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7a8bb3bf0469093b3f57a75d2a934860edee4fbf))
* **workbox:** New configuration for specifying plugins when configuring a strategy ([#337](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/337)) ([dacf7ec](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dacf7ec3613a6cb985990eab6c78879b78bdbbbc)), closes [/github.com/nuxt-community/pwa-module/pull/337#issuecomment-681870522](https://github.com/somethingnew71//github.com/nuxt-community/pwa-module/pull/337/issues/issuecomment-681870522)
* **workbox:** precache `start_url` (resolves [#372](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/372)) ([27e19a0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/27e19a04d6f2b14943a0bb4a9b7414382591d4e0))
* **workbox:** restore `sw.js` with smart build (fixes [#352](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/352)) ([491f440](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/491f440936e107c424864a1aa1121e6995d4e87b))
* **workbox:** unregister only to avoid loop ([44c5cd3](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/44c5cd3aa86f12929aeb03d37cfa20df5171f855))
* **workbox:** use NetworkFirst for dev ([9a67580](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9a67580badc5f3d80fc1d56f8b5a44dc4aebf60b))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/14). ([f384103](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f384103e55b2109f8a6302fd4dcbeed13530163d))


* update execa to 4.x ([301a07c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/301a07cd8733b29231bdfbc0390681e59f5decb7))
* only support nuxt.hook ([854d826](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/854d826e05363a4a8756ed77159fcd532f11b353))
* use tapable hooks ([#103](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/103)) ([9f27d5c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9f27d5cdae0e0341d6d4b4f6814f91db6eab1432))

## 6.0.0 (2023-03-15)


### ⚠ BREAKING CHANGES

* Requeires Node 10.x
* **workbox:** default changed from NetworkOnly to NetworkFirst when offlinePage is enabled
* needs nuxt 2.x or later
* webpack >= 4 (Nuxt >= 2) is required

### Features

* `pwa.` scopped options ([010fe0e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/010fe0e0ec0266c39392c831020d477bbb0e3acc))
* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c0efb1d2f9923f227ffbb5421ec285c97d3daca6))
* add HMR test suit ([ff3d502](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ff3d5023b0c91b2795889297143a293077b293fb))
* add og:image support ([#30](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/30)) ([afebd96](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/afebd962d2047c5e9efd039b6832e8503632fcce))
* add oneSignal module ([bbc7b72](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/bbc7b72b3742643c02b8c82276359e43bf60ee87))
* add option to register third-party sw ([#12](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/12)) ([9c0b61e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9c0b61e3e22754fb1de9ab43ecb049791822eb2e))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b17bbd04dc67778004392da91841092e55847d37))
* add types ([#323](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/323)) ([8723d07](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8723d076cb87ff9e583ba755f72f4d62360d6eb1))
* cleanupOutdatedCaches ([9167013](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/91670138999cb3039b42ee9b398b6bcafe7db650))
* **icon:** add combined option sources ([539430f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/539430fdf540e2f0be8ebd6417454ad0a316c9b0))
* **icon:** add support for icon purpose ([#246](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/246)) ([9248174](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9248174fe8bac352318c8fe292012156ccfd56ad))
* **icon:** allow reading icon from assetc/icon.png ([#29](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/29)) ([9e0fde3](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9e0fde33df9e6fe3e3c275f577ad91f92e180433))
* **icon:** default purpose to any + maskable ([30f0f63](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/30f0f63bcd1601cc6aa5595a851de965dde9af88))
* **icon:** expose options.cacheDir ([f8dbf1d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f8dbf1dac99519648a53dc22ab4019af25a677aa))
* **icon:** make icons accessible ([#51](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/51)) ([92bccd3](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/92bccd37cf2e1b2471ea3d70126a7428a983b083))
* **icon:** new options ([#126](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/126)) ([12e6576](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/12e65762e995f9f270e3b88ed1938990d49d0607))
* **icon:** register `favicon.ico` when available ([#258](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/258)) ([7a48d2a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7a48d2a60b1f2ccaa1287789adb846806afd5224))
* **icon:** rename `accessibleIcons` to `iconPlugin` ([3e175f9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3e175f93c046028b6f3f9479085ec98d014b460b))
* **icon:** support for iOS splash screens ([#308](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/308)) ([f4eeda7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f4eeda7ce05cdd7dda4e4c4ab81e986f6c94a951))
* **icon:** update to jimp 0.5.0 ([b071c4b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b071c4b437d8cf5a51721129131f19f7ff13e586))
* improve computed cacheId ([cd6c9cc](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/cd6c9cc6d7233145d212379aac514c3bc339a493))
* improve sw.register error handling ([9aa76f8](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9aa76f89bdf34cefc018ae602a2514bf9ea38944))
* **manifest:** add `useWebmanifestExtension` option and improve docs ([#241](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/241)) ([4484e6c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4484e6c697c5534103969894252f1d356d4016ee))
* **manifest:** add revision to start_url ([ad26827](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ad26827a9d76b6a4f1123f8a06fd0c946b90b5dd))
* **manifest:** allow overriding publicPath ([#19](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/19)) ([4e6782e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4e6782ed7d261055b40cbc0678624c74d89897c1))
* **manifest:** support crossorigin option ([#71](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/71)) ([ccb2c33](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ccb2c339e9092c162c29dab9c36bb7cfdd51883a))
* **meta:** add author property ([#41](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/41)) ([cafcfc4](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/cafcfc40eb020a03c0f39d2a121c4f1a54e915b6))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3c7aa7d0199ce3ab0d7fff606d52b913dba0f34e)), closes [#10](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/42)) ([3990ddf](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3990ddf325bfe092d7590dee4ca6877cc638c4dc))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dc39fcbaa2fa63ecf909c0183b0a55b3f3ad2397))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/43)) ([fe11c76](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fe11c76941ba53eb85659c3cd9a970924f51abf3))
* **meta:** merge head at runtime ([#363](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/363)) ([c0d86ea](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c0d86ead374efcfd66282959e65055262e4a27cf))
* **module:** allow disabling with top-level options ([65800f9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/65800f91a671e61d59a9faf885c2ff7ecc9d9ca0))
* offlineAnalytics ([#55](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/55)) ([4c4d3ff](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4c4d3ff93f16eb25ce51027a43e559e2da8a601f))
* ogSiteName ([#50](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/50)) ([0c99ab9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/0c99ab94cb8f6f06e0658f958345609f31da7748))
* **onesignal:** enable CDN by default ([7c78c67](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7c78c679283f6314bc9e7695411b962fd9f835ce))
* **onesignal:** move init options under init ([dd61c18](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dd61c18093ada4ed936c08b6a25a96d7f93cdfbb))
* options.dev ([fb0d38c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fb0d38cdaec4821f479222b038d88a1a56d06e19))
* remove debug ([92ba73e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/92ba73e9cccca6c3561d8b6a0b27b00ccf86f720))
* rewrite icon with async image resizer ([#171](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/171)) ([a4a457e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a4a457efe98461cf28249742952ca49e9ebfe847))
* rewrite workbox ([#122](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/122)) ([9e49896](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9e49896be3f89b15116c60a6ddebf71d62a131c9))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fdcda0f420b01f637e9ddd8b7ad127c8e5cf2e86))
* support `manifest.fileName` with template ([f05353b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f05353b7ccfef88f5f95f0fa7b0109c2ece4236b)), closes [#193](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/193)
* sync workbox version with workbox-window ([9a3632a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9a3632a8cda8d66c454d76bf633a0ebf14218487))
* update onesignal sdk once ([c08e423](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c08e4231991d849eb1c7c63942109f034afaee3e))
* use `jimp-compact` ([5e37b58](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5e37b58a3c6b07062ab012d3c53641e2d9e7302a))
* use better regexes ([318228e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/318228e8a88a97f4a50e86ebf4b784acd48f523d))
* use integraty file to invalidate icon cache ([6661a09](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/6661a09f86bbc169a99effac3d9cb1620f530b3d))
* **worbox:** add offline option for making it optional ([#59](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/59)) ([76de33c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/76de33cc4f7dde9e1b930be773add3736851a95e)), closes [#24](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/24)
* **worbox:** offlineAssets ([#86](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/86)) ([27c8fa1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/27c8fa1b5c89a1f2ae044a1eac8028757bfa029b))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5ac89cffdb7b9462172399f7789a4f56031fb53d))
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f1e1fe127c7a9e15e74dbed243194c68a6422ed2))
* **workbox:** allow cache names to be configured ([#154](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/154)) ([2d7ed53](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/2d7ed53a3e66fa8d9607591ddfc9225ecbc7744a))
* **workbox:** assetsURLPattern, pagesURLPattern ([5fc3d66](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5fc3d66856d9d932c66b8c6b0a72362ff01c2758))
* **workbox:** bump to 4.0.0-rc.2 ([7e278f0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7e278f0d3cf37a8c9b7ba6d06fd85ceb464abd0e))
* **workbox:** change the order of default runtimeCache ([#106](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/106)) ([033b504](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/033b50472bd4172ce562b9efb818d093458861c5))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e7677d8c317aa4c189dfe563a2ec5e279d53d691))
* **workbox:** enabled option and self destroying sw ([c64226c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c64226cea36c1b0b9f0efe7640439e6bb134ddce))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a5ddf5992c61ee759a292d1af95a2cf0daac9d73))
* workboxExtensions and extension reading fixes ([5c56484](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5c564844047e86484ace65bfcffbdf542528e420))
* **workbox:** importScripts option ([7c8644c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7c8644cbf612a5686e590074a2848e10cf9c37c8))
* **workbox:** improve sw.register ([c35f610](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c35f6104a66ef125a0d33f8e32ee8f5f9a1cfc28))
* **workbox:** make plugin fully asynchronous ([1eb1190](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1eb11905a7499cb3b886265969a939d55eb53ca1))
* **workbox:** offline page assets ([#85](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/85)) ([8bc4a3b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8bc4a3bbca296f9470f6ec7b63cef1abae810932))
* **workbox:** offlineStrategy ([e377436](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e377436cedf7fc88288889a1021dfe2855e783b4))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/80)) ([88cc602](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/88cc60275d8e4cff46d20c99708bd34a689c2aba))
* **workbox:** preCaching option ([67f1c3d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/67f1c3d1b839b05f2c09d436c4eec62675001030))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b0af84e0751bc023e33b6bc6923ae2a17fb8d0a1))
* **workbox:** support pass config object to `workbox.setConfig` ([#95](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/95)) ([b5dab8a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b5dab8a821eb474ecd5351cc2d779a4c17ed4802))
* **workbox:** upgrade workboxVersion to 4.0.0-rc.0 ([b364572](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b3645727e43817027bed6e32e1c06b8ad2bfb559))
* **workbox:** use workbox 4.0.0-0 ([70813ef](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/70813ef1146fa0a1db27534531f82b537d7e0f14))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/60)) ([0fef874](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/0fef874441e0b98230cb3a96d7035cdebcd294e4))
* **workbox:** workbox-window support ([2e356d0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/2e356d059ee73810db5512fedbd92f92d9e2e822))


### Bug Fixes

* add workboxExtensions to defaults ([#138](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/138)) ([ac8ba74](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ac8ba745b81ef339665661a7fa436ab48819d801))
* append to start_url without query param (fixes [#403](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/403)) ([054b8a2](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/054b8a299274fafc61275b50374b4eb1e83e7e46))
* avoid adding revision to start_url ([1c44cff](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1c44cffbe1ae7c9096c5696d6b6521f60b3fe32f))
* **docs:** add reference to pwa module ([49b7c49](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/49b7c49b7b79b613bdbedc4fa3c97d5bff7feaa2))
* don't override title when titleTemplate is provided  ([#48](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/48)) ([8c3f319](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8c3f319a0ca3983535c88feff2c444d544d3dd45))
* expose modified pwa context to the config ([c325e44](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c325e4434b940789309f80aa91b1e436363aa906))
* **icon:** await on build ([e3c1be2](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e3c1be2c7804ec374116d0c177a1537b6c764042))
* **icon:** clean cacheDir when generating icons ([1e6eb19](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1e6eb19851bbb6bcb51106cea5611475edec75cc))
* **icon:** fork without original process args ([#343](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/343)) ([8b1f19f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8b1f19f56ddc31a49445334ddc8abe2162b4b760))
* **icon:** generate only on build ([9d68d70](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9d68d70bb8ce5d3f9ef23b98e305e8ac136d8ef2))
* **icon:** handle jimp.write callback ([bffe6ed](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/bffe6eda94e266e17e0dee7069a63393b6dc9455))
* **icon:** handle situation where the iconSrc is `null` or `undefined` ([#187](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/187)) ([66be874](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/66be874bbdbb9ba796e0406c63a455455bc4caf2))
* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/84)) ([3f0e718](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3f0e71892f6d1c39090dad4107d74871f4a44446))
* **icon:** update warning url to docs ([#329](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/329)) ([61633fa](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/61633fa640793c344748efdf790a56456fad8e2f))
* **manifest:** do not use nuxt loading bar color as default `theme_color` ([#344](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/344)) ([a18a79f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a18a79f62a49a3a563621929e30fc8703c3c133a))
* **manifest:** invalidate start_url cache ([240d4a1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/240d4a14868fe46ab98bb79ba3a22c7973875d45))
* **manifest:** remove publicPath field ([b03dc14](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b03dc14b7c99cbf0eac9470f09b50d9089ea760a))
* **manifest:** run only on build ([ecaa835](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/ecaa8355f76d9bd9ea12392b557254b743548600))
* **meta:** add missing `hid` to icon tags ([#428](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/428)) ([d9addb7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d9addb7917363e812fe277acc1cf228018a8342b))
* **meta:** add missing `router.base` prefix to favicon ([#354](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/354)) ([3e910ae](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3e910ae7e87d341c6a6ea018d013105ce1721b5b))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/23)) ([76a1f89](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/76a1f89259224f195084515d4b88d05376e1402a))
* **meta:** allow setting `appleStatusBarStyle` without `mobileAppIOS` ([b0f226a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b0f226aadeee50b47790ac064852b444e33d9b95)), closes [#338](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/338)
* **meta:** avoid unnecessary log for meta.json ([de8e039](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/de8e039740a5618b59312682ecdea4f023d88414))
* **meta:** fix `mergeMeta` cjs export ([774f1a8](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/774f1a87d8c102ad3754374e53a41b434a01b82c))
* **meta:** fix issues regarding favicon.ico fallback ([7a1e773](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7a1e77384eb88f0886180bc784efa242ae59e5ad))
* **meta:** generate only on build ([1cace26](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1cace266e3528aa53d5a562e3d7ce1fefff7f4dc))
* **meta:** load meta when `ssr` is disable and using `nuxt dev` (fixes [#219](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/219)) ([b6a5ead](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b6a5ead17cdb8f2edff9d12c326ae59d8ac372be))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/44)) ([354f818](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/354f818708e91cbabbbe97fdfaceecce90236689))
* **meta:** prevent build failure for ios splash image when no icon is used ([#362](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/362)) ([494eed5](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/494eed5db00e7cf6863fc854e6ccb6b7bb8c0ba4))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/cf48b3fb6c64fe4cbbac2ae8bb4474cbd21390b3)), closes [#10](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/10)
* **module:** handle readJSFiles for string param ([#143](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/143)) ([4f06479](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/4f064799cf01b95432b0f7d28b7010b60b9f4146))
* **module:** icon purpose warning appearing when it shouldn't ([#305](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/305)) ([5833e31](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5833e311e0379f6617c845a4f319733047ef7a53))
* offlinePage syntax error ([af21d74](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/af21d7401a9f28932ed98a08cdf2363a708e6777))
* **onesignal:** add cache query to sw.js ([33f8f61](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/33f8f61ffac193c7ccdeeb65a294925253460e6f))
* **onesignal:** ensure no duplicate script is added ([#161](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/161)) ([89c1a1d](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/89c1a1da2a55125867c1ddae4cb7144ddb5ca6d5))
* path ogImage if is url ([#121](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/121)) ([d6dc82b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d6dc82b9c11b33735b9b27006855ca64994c15fd))
* precached files are not updated ([#386](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/386)) ([872dce1](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/872dce1ec2df58cbf6efcfe4a080f632510ea32b))
* **pwa-utils:** don't combine with esm ([fddfa7a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/fddfa7a687f043aaa4a3719a02f45b7cc803214a)), closes [#147](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/147)
* **pwa-utils:** ensure joinUrl not modifying scheme part ([09a465a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/09a465ac888c947fd8119a57f27c54c370694ee4))
* **pwa-utils:** handle non-strings in `startCase` ([#150](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/150)) ([782217a](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/782217aca8ea2ece277cb20eaee54b536d55435a))
* **pwa:** no more optimize dependency ([a1c149f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a1c149f75b41976b3efe99e26a01d68f1c5af639))
* relax pages regex for workbox 4 compatiblity ([04e74a7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/04e74a7843ea54bcebca491c9abc0daa7ede3515))
* revert compileTemplate as is fixed by nuxt/nuxt.js[#6283](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/6283) for 2.9.x ([d0f96de](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d0f96de4f40cb33bb859ed8401205fcb70181747))
* routing order for default offline route (/.*). it must be last order ([#100](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/100)) ([1c829d0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/1c829d01d23ca4fd40a23eecbfc24ce6be48e48d))
* serve static webpack assets from disk in dev mode (fixes [#373](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/373)) ([8298f95](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/8298f955bf80eb44090cfb7b56070dc7e1a50aa8))
* **serveStatic:** wrap serveStatic in `fromNodeMiddleware` for @nuxt/bridge compatibility (fixes [#532](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/532)) ([87457c7](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/87457c7d13dfc2bb2ea609c1c07a1388b3b53704))
* stateWhileRevalidate() -> networkOnly() ([832d60f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/832d60fc1364ddff608822e36d4a70c7eaa04f39))
* support build cache ([#371](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/371)) ([9a825c9](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9a825c9d47c057c5934030142cb6e46d23a46e21))
* truncate manifest hash ([5c74621](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/5c746218a5eafd21d51e5ad9fd330a2bcac04802))
* **types:** mark module options fields as optional ([#420](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/420)) ([7d75c28](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7d75c285485efde4081127ff3bb899565a771c7e))
* use shared pwa context ([3c19bae](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/3c19baebc0a1dba5e8b7ef20c7230e81ce6a8e95))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/a0fb9084462d5f212009ec80cf0c64142ff59126))
* **workbox:** add additional details for uncaught errors and fix chromium CORS ([#417](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/417)) ([f20489c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f20489c2cc289b9d6f90143078f415d97b3cf4c1))
* **workbox:** add missing lodash dependency ([#91](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/91)) ([da2c36f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/da2c36f90668f9744cb5e8854b677037a70b862e))
* **workbox:** always prepend routerBase to swURL ([d3a52b6](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/d3a52b6e9e5672e06e69269152b9625ae1152b17)), closes [#157](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/157)
* **workbox:** deepClone options to avoid cross-build mutation ([e39027e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/e39027ee7159103d755fe67c1c105235f3257739))
* **workbox:** disable `cacheAssets` for dev mode ([dbf6d67](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dbf6d67bea83a4e9376a77d46e449606f42c45bf))
* **workbox:** faster service worker register ([07524a2](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/07524a2d4e5605743660b6f0b1e0ceb74aa609ee))
* **workbox:** handle `offlinePage` options (fixes [#365](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/365)) ([2b9856e](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/2b9856e9c226c5f286acb5116cb381e2fc550248))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/73)) ([6d241ec](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/6d241ec8518945115f85892e99de910221420810))
* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/83). ([c7102fd](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/c7102fdede1f790044cdd7e88212997b4693d963))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/b744a270e16d418f826ab8035c184b4bbe3d4185))
* **workbox:** missing required parameter request for `handle()` ([#335](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/335)) ([eedf23f](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/eedf23fa3ab478f8a449817528d0270507babfc8))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/83). ([7a8bb3b](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/7a8bb3bf0469093b3f57a75d2a934860edee4fbf))
* **workbox:** New configuration for specifying plugins when configuring a strategy ([#337](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/337)) ([dacf7ec](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/dacf7ec3613a6cb985990eab6c78879b78bdbbbc)), closes [/github.com/nuxt-community/pwa-module/pull/337#issuecomment-681870522](https://github.com/somethingnew71//github.com/nuxt-community/pwa-module/pull/337/issues/issuecomment-681870522)
* **workbox:** precache `start_url` (resolves [#372](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/372)) ([27e19a0](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/27e19a04d6f2b14943a0bb4a9b7414382591d4e0))
* **workbox:** restore `sw.js` with smart build (fixes [#352](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/352)) ([491f440](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/491f440936e107c424864a1aa1121e6995d4e87b))
* **workbox:** unregister only to avoid loop ([44c5cd3](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/44c5cd3aa86f12929aeb03d37cfa20df5171f855))
* **workbox:** use NetworkFirst for dev ([9a67580](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9a67580badc5f3d80fc1d56f8b5a44dc4aebf60b))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/14). ([f384103](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/f384103e55b2109f8a6302fd4dcbeed13530163d))


* update execa to 4.x ([301a07c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/301a07cd8733b29231bdfbc0390681e59f5decb7))
* only support nuxt.hook ([854d826](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/854d826e05363a4a8756ed77159fcd532f11b353))
* use tapable hooks ([#103](https://github.com/somethingnew71/nuxt-pwa-bridge/issues/103)) ([9f27d5c](https://github.com/somethingnew71/nuxt-pwa-bridge/commit/9f27d5cdae0e0341d6d4b4f6814f91db6eab1432))

## 5.0.0 (2023-03-15)


### ⚠ BREAKING CHANGES

* Requeires Node 10.x
* **workbox:** default changed from NetworkOnly to NetworkFirst when offlinePage is enabled
* needs nuxt 2.x or later
* webpack >= 4 (Nuxt >= 2) is required

### Features

* `pwa.` scopped options ([010fe0e](https://github.com/somethingnew71/pwa-module-bridge/commit/010fe0e0ec0266c39392c831020d477bbb0e3acc))
* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/somethingnew71/pwa-module-bridge/commit/c0efb1d2f9923f227ffbb5421ec285c97d3daca6))
* add HMR test suit ([ff3d502](https://github.com/somethingnew71/pwa-module-bridge/commit/ff3d5023b0c91b2795889297143a293077b293fb))
* add og:image support ([#30](https://github.com/somethingnew71/pwa-module-bridge/issues/30)) ([afebd96](https://github.com/somethingnew71/pwa-module-bridge/commit/afebd962d2047c5e9efd039b6832e8503632fcce))
* add oneSignal module ([bbc7b72](https://github.com/somethingnew71/pwa-module-bridge/commit/bbc7b72b3742643c02b8c82276359e43bf60ee87))
* add option to register third-party sw ([#12](https://github.com/somethingnew71/pwa-module-bridge/issues/12)) ([9c0b61e](https://github.com/somethingnew71/pwa-module-bridge/commit/9c0b61e3e22754fb1de9ab43ecb049791822eb2e))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/somethingnew71/pwa-module-bridge/commit/b17bbd04dc67778004392da91841092e55847d37))
* add types ([#323](https://github.com/somethingnew71/pwa-module-bridge/issues/323)) ([8723d07](https://github.com/somethingnew71/pwa-module-bridge/commit/8723d076cb87ff9e583ba755f72f4d62360d6eb1))
* cleanupOutdatedCaches ([9167013](https://github.com/somethingnew71/pwa-module-bridge/commit/91670138999cb3039b42ee9b398b6bcafe7db650))
* **icon:** add combined option sources ([539430f](https://github.com/somethingnew71/pwa-module-bridge/commit/539430fdf540e2f0be8ebd6417454ad0a316c9b0))
* **icon:** add support for icon purpose ([#246](https://github.com/somethingnew71/pwa-module-bridge/issues/246)) ([9248174](https://github.com/somethingnew71/pwa-module-bridge/commit/9248174fe8bac352318c8fe292012156ccfd56ad))
* **icon:** allow reading icon from assetc/icon.png ([#29](https://github.com/somethingnew71/pwa-module-bridge/issues/29)) ([9e0fde3](https://github.com/somethingnew71/pwa-module-bridge/commit/9e0fde33df9e6fe3e3c275f577ad91f92e180433))
* **icon:** default purpose to any + maskable ([30f0f63](https://github.com/somethingnew71/pwa-module-bridge/commit/30f0f63bcd1601cc6aa5595a851de965dde9af88))
* **icon:** expose options.cacheDir ([f8dbf1d](https://github.com/somethingnew71/pwa-module-bridge/commit/f8dbf1dac99519648a53dc22ab4019af25a677aa))
* **icon:** make icons accessible ([#51](https://github.com/somethingnew71/pwa-module-bridge/issues/51)) ([92bccd3](https://github.com/somethingnew71/pwa-module-bridge/commit/92bccd37cf2e1b2471ea3d70126a7428a983b083))
* **icon:** new options ([#126](https://github.com/somethingnew71/pwa-module-bridge/issues/126)) ([12e6576](https://github.com/somethingnew71/pwa-module-bridge/commit/12e65762e995f9f270e3b88ed1938990d49d0607))
* **icon:** register `favicon.ico` when available ([#258](https://github.com/somethingnew71/pwa-module-bridge/issues/258)) ([7a48d2a](https://github.com/somethingnew71/pwa-module-bridge/commit/7a48d2a60b1f2ccaa1287789adb846806afd5224))
* **icon:** rename `accessibleIcons` to `iconPlugin` ([3e175f9](https://github.com/somethingnew71/pwa-module-bridge/commit/3e175f93c046028b6f3f9479085ec98d014b460b))
* **icon:** support for iOS splash screens ([#308](https://github.com/somethingnew71/pwa-module-bridge/issues/308)) ([f4eeda7](https://github.com/somethingnew71/pwa-module-bridge/commit/f4eeda7ce05cdd7dda4e4c4ab81e986f6c94a951))
* **icon:** update to jimp 0.5.0 ([b071c4b](https://github.com/somethingnew71/pwa-module-bridge/commit/b071c4b437d8cf5a51721129131f19f7ff13e586))
* improve computed cacheId ([cd6c9cc](https://github.com/somethingnew71/pwa-module-bridge/commit/cd6c9cc6d7233145d212379aac514c3bc339a493))
* improve sw.register error handling ([9aa76f8](https://github.com/somethingnew71/pwa-module-bridge/commit/9aa76f89bdf34cefc018ae602a2514bf9ea38944))
* **manifest:** add `useWebmanifestExtension` option and improve docs ([#241](https://github.com/somethingnew71/pwa-module-bridge/issues/241)) ([4484e6c](https://github.com/somethingnew71/pwa-module-bridge/commit/4484e6c697c5534103969894252f1d356d4016ee))
* **manifest:** add revision to start_url ([ad26827](https://github.com/somethingnew71/pwa-module-bridge/commit/ad26827a9d76b6a4f1123f8a06fd0c946b90b5dd))
* **manifest:** allow overriding publicPath ([#19](https://github.com/somethingnew71/pwa-module-bridge/issues/19)) ([4e6782e](https://github.com/somethingnew71/pwa-module-bridge/commit/4e6782ed7d261055b40cbc0678624c74d89897c1))
* **manifest:** support crossorigin option ([#71](https://github.com/somethingnew71/pwa-module-bridge/issues/71)) ([ccb2c33](https://github.com/somethingnew71/pwa-module-bridge/commit/ccb2c339e9092c162c29dab9c36bb7cfdd51883a))
* **meta:** add author property ([#41](https://github.com/somethingnew71/pwa-module-bridge/issues/41)) ([cafcfc4](https://github.com/somethingnew71/pwa-module-bridge/commit/cafcfc40eb020a03c0f39d2a121c4f1a54e915b6))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/somethingnew71/pwa-module-bridge/commit/3c7aa7d0199ce3ab0d7fff606d52b913dba0f34e)), closes [#10](https://github.com/somethingnew71/pwa-module-bridge/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/somethingnew71/pwa-module-bridge/issues/42)) ([3990ddf](https://github.com/somethingnew71/pwa-module-bridge/commit/3990ddf325bfe092d7590dee4ca6877cc638c4dc))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/somethingnew71/pwa-module-bridge/commit/dc39fcbaa2fa63ecf909c0183b0a55b3f3ad2397))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/somethingnew71/pwa-module-bridge/issues/43)) ([fe11c76](https://github.com/somethingnew71/pwa-module-bridge/commit/fe11c76941ba53eb85659c3cd9a970924f51abf3))
* **meta:** merge head at runtime ([#363](https://github.com/somethingnew71/pwa-module-bridge/issues/363)) ([c0d86ea](https://github.com/somethingnew71/pwa-module-bridge/commit/c0d86ead374efcfd66282959e65055262e4a27cf))
* **module:** allow disabling with top-level options ([65800f9](https://github.com/somethingnew71/pwa-module-bridge/commit/65800f91a671e61d59a9faf885c2ff7ecc9d9ca0))
* offlineAnalytics ([#55](https://github.com/somethingnew71/pwa-module-bridge/issues/55)) ([4c4d3ff](https://github.com/somethingnew71/pwa-module-bridge/commit/4c4d3ff93f16eb25ce51027a43e559e2da8a601f))
* ogSiteName ([#50](https://github.com/somethingnew71/pwa-module-bridge/issues/50)) ([0c99ab9](https://github.com/somethingnew71/pwa-module-bridge/commit/0c99ab94cb8f6f06e0658f958345609f31da7748))
* **onesignal:** enable CDN by default ([7c78c67](https://github.com/somethingnew71/pwa-module-bridge/commit/7c78c679283f6314bc9e7695411b962fd9f835ce))
* **onesignal:** move init options under init ([dd61c18](https://github.com/somethingnew71/pwa-module-bridge/commit/dd61c18093ada4ed936c08b6a25a96d7f93cdfbb))
* options.dev ([fb0d38c](https://github.com/somethingnew71/pwa-module-bridge/commit/fb0d38cdaec4821f479222b038d88a1a56d06e19))
* remove debug ([92ba73e](https://github.com/somethingnew71/pwa-module-bridge/commit/92ba73e9cccca6c3561d8b6a0b27b00ccf86f720))
* rewrite icon with async image resizer ([#171](https://github.com/somethingnew71/pwa-module-bridge/issues/171)) ([a4a457e](https://github.com/somethingnew71/pwa-module-bridge/commit/a4a457efe98461cf28249742952ca49e9ebfe847))
* rewrite workbox ([#122](https://github.com/somethingnew71/pwa-module-bridge/issues/122)) ([9e49896](https://github.com/somethingnew71/pwa-module-bridge/commit/9e49896be3f89b15116c60a6ddebf71d62a131c9))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/somethingnew71/pwa-module-bridge/commit/fdcda0f420b01f637e9ddd8b7ad127c8e5cf2e86))
* support `manifest.fileName` with template ([f05353b](https://github.com/somethingnew71/pwa-module-bridge/commit/f05353b7ccfef88f5f95f0fa7b0109c2ece4236b)), closes [#193](https://github.com/somethingnew71/pwa-module-bridge/issues/193)
* sync workbox version with workbox-window ([9a3632a](https://github.com/somethingnew71/pwa-module-bridge/commit/9a3632a8cda8d66c454d76bf633a0ebf14218487))
* update onesignal sdk once ([c08e423](https://github.com/somethingnew71/pwa-module-bridge/commit/c08e4231991d849eb1c7c63942109f034afaee3e))
* use `jimp-compact` ([5e37b58](https://github.com/somethingnew71/pwa-module-bridge/commit/5e37b58a3c6b07062ab012d3c53641e2d9e7302a))
* use better regexes ([318228e](https://github.com/somethingnew71/pwa-module-bridge/commit/318228e8a88a97f4a50e86ebf4b784acd48f523d))
* use integraty file to invalidate icon cache ([6661a09](https://github.com/somethingnew71/pwa-module-bridge/commit/6661a09f86bbc169a99effac3d9cb1620f530b3d))
* **worbox:** add offline option for making it optional ([#59](https://github.com/somethingnew71/pwa-module-bridge/issues/59)) ([76de33c](https://github.com/somethingnew71/pwa-module-bridge/commit/76de33cc4f7dde9e1b930be773add3736851a95e)), closes [#24](https://github.com/somethingnew71/pwa-module-bridge/issues/24)
* **worbox:** offlineAssets ([#86](https://github.com/somethingnew71/pwa-module-bridge/issues/86)) ([27c8fa1](https://github.com/somethingnew71/pwa-module-bridge/commit/27c8fa1b5c89a1f2ae044a1eac8028757bfa029b))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/somethingnew71/pwa-module-bridge/commit/5ac89cffdb7b9462172399f7789a4f56031fb53d))
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/somethingnew71/pwa-module-bridge/commit/f1e1fe127c7a9e15e74dbed243194c68a6422ed2))
* **workbox:** allow cache names to be configured ([#154](https://github.com/somethingnew71/pwa-module-bridge/issues/154)) ([2d7ed53](https://github.com/somethingnew71/pwa-module-bridge/commit/2d7ed53a3e66fa8d9607591ddfc9225ecbc7744a))
* **workbox:** assetsURLPattern, pagesURLPattern ([5fc3d66](https://github.com/somethingnew71/pwa-module-bridge/commit/5fc3d66856d9d932c66b8c6b0a72362ff01c2758))
* **workbox:** bump to 4.0.0-rc.2 ([7e278f0](https://github.com/somethingnew71/pwa-module-bridge/commit/7e278f0d3cf37a8c9b7ba6d06fd85ceb464abd0e))
* **workbox:** change the order of default runtimeCache ([#106](https://github.com/somethingnew71/pwa-module-bridge/issues/106)) ([033b504](https://github.com/somethingnew71/pwa-module-bridge/commit/033b50472bd4172ce562b9efb818d093458861c5))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/somethingnew71/pwa-module-bridge/commit/e7677d8c317aa4c189dfe563a2ec5e279d53d691))
* **workbox:** enabled option and self destroying sw ([c64226c](https://github.com/somethingnew71/pwa-module-bridge/commit/c64226cea36c1b0b9f0efe7640439e6bb134ddce))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/somethingnew71/pwa-module-bridge/commit/a5ddf5992c61ee759a292d1af95a2cf0daac9d73))
* workboxExtensions and extension reading fixes ([5c56484](https://github.com/somethingnew71/pwa-module-bridge/commit/5c564844047e86484ace65bfcffbdf542528e420))
* **workbox:** importScripts option ([7c8644c](https://github.com/somethingnew71/pwa-module-bridge/commit/7c8644cbf612a5686e590074a2848e10cf9c37c8))
* **workbox:** improve sw.register ([c35f610](https://github.com/somethingnew71/pwa-module-bridge/commit/c35f6104a66ef125a0d33f8e32ee8f5f9a1cfc28))
* **workbox:** make plugin fully asynchronous ([1eb1190](https://github.com/somethingnew71/pwa-module-bridge/commit/1eb11905a7499cb3b886265969a939d55eb53ca1))
* **workbox:** offline page assets ([#85](https://github.com/somethingnew71/pwa-module-bridge/issues/85)) ([8bc4a3b](https://github.com/somethingnew71/pwa-module-bridge/commit/8bc4a3bbca296f9470f6ec7b63cef1abae810932))
* **workbox:** offlineStrategy ([e377436](https://github.com/somethingnew71/pwa-module-bridge/commit/e377436cedf7fc88288889a1021dfe2855e783b4))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/somethingnew71/pwa-module-bridge/issues/80)) ([88cc602](https://github.com/somethingnew71/pwa-module-bridge/commit/88cc60275d8e4cff46d20c99708bd34a689c2aba))
* **workbox:** preCaching option ([67f1c3d](https://github.com/somethingnew71/pwa-module-bridge/commit/67f1c3d1b839b05f2c09d436c4eec62675001030))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/somethingnew71/pwa-module-bridge/commit/b0af84e0751bc023e33b6bc6923ae2a17fb8d0a1))
* **workbox:** support pass config object to `workbox.setConfig` ([#95](https://github.com/somethingnew71/pwa-module-bridge/issues/95)) ([b5dab8a](https://github.com/somethingnew71/pwa-module-bridge/commit/b5dab8a821eb474ecd5351cc2d779a4c17ed4802))
* **workbox:** upgrade workboxVersion to 4.0.0-rc.0 ([b364572](https://github.com/somethingnew71/pwa-module-bridge/commit/b3645727e43817027bed6e32e1c06b8ad2bfb559))
* **workbox:** use workbox 4.0.0-0 ([70813ef](https://github.com/somethingnew71/pwa-module-bridge/commit/70813ef1146fa0a1db27534531f82b537d7e0f14))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/somethingnew71/pwa-module-bridge/issues/60)) ([0fef874](https://github.com/somethingnew71/pwa-module-bridge/commit/0fef874441e0b98230cb3a96d7035cdebcd294e4))
* **workbox:** workbox-window support ([2e356d0](https://github.com/somethingnew71/pwa-module-bridge/commit/2e356d059ee73810db5512fedbd92f92d9e2e822))


### Bug Fixes

* add workboxExtensions to defaults ([#138](https://github.com/somethingnew71/pwa-module-bridge/issues/138)) ([ac8ba74](https://github.com/somethingnew71/pwa-module-bridge/commit/ac8ba745b81ef339665661a7fa436ab48819d801))
* append to start_url without query param (fixes [#403](https://github.com/somethingnew71/pwa-module-bridge/issues/403)) ([054b8a2](https://github.com/somethingnew71/pwa-module-bridge/commit/054b8a299274fafc61275b50374b4eb1e83e7e46))
* avoid adding revision to start_url ([1c44cff](https://github.com/somethingnew71/pwa-module-bridge/commit/1c44cffbe1ae7c9096c5696d6b6521f60b3fe32f))
* **docs:** add reference to pwa module ([49b7c49](https://github.com/somethingnew71/pwa-module-bridge/commit/49b7c49b7b79b613bdbedc4fa3c97d5bff7feaa2))
* don't override title when titleTemplate is provided  ([#48](https://github.com/somethingnew71/pwa-module-bridge/issues/48)) ([8c3f319](https://github.com/somethingnew71/pwa-module-bridge/commit/8c3f319a0ca3983535c88feff2c444d544d3dd45))
* expose modified pwa context to the config ([c325e44](https://github.com/somethingnew71/pwa-module-bridge/commit/c325e4434b940789309f80aa91b1e436363aa906))
* **icon:** await on build ([e3c1be2](https://github.com/somethingnew71/pwa-module-bridge/commit/e3c1be2c7804ec374116d0c177a1537b6c764042))
* **icon:** clean cacheDir when generating icons ([1e6eb19](https://github.com/somethingnew71/pwa-module-bridge/commit/1e6eb19851bbb6bcb51106cea5611475edec75cc))
* **icon:** fork without original process args ([#343](https://github.com/somethingnew71/pwa-module-bridge/issues/343)) ([8b1f19f](https://github.com/somethingnew71/pwa-module-bridge/commit/8b1f19f56ddc31a49445334ddc8abe2162b4b760))
* **icon:** generate only on build ([9d68d70](https://github.com/somethingnew71/pwa-module-bridge/commit/9d68d70bb8ce5d3f9ef23b98e305e8ac136d8ef2))
* **icon:** handle jimp.write callback ([bffe6ed](https://github.com/somethingnew71/pwa-module-bridge/commit/bffe6eda94e266e17e0dee7069a63393b6dc9455))
* **icon:** handle situation where the iconSrc is `null` or `undefined` ([#187](https://github.com/somethingnew71/pwa-module-bridge/issues/187)) ([66be874](https://github.com/somethingnew71/pwa-module-bridge/commit/66be874bbdbb9ba796e0406c63a455455bc4caf2))
* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/somethingnew71/pwa-module-bridge/issues/84)) ([3f0e718](https://github.com/somethingnew71/pwa-module-bridge/commit/3f0e71892f6d1c39090dad4107d74871f4a44446))
* **icon:** update warning url to docs ([#329](https://github.com/somethingnew71/pwa-module-bridge/issues/329)) ([61633fa](https://github.com/somethingnew71/pwa-module-bridge/commit/61633fa640793c344748efdf790a56456fad8e2f))
* **manifest:** do not use nuxt loading bar color as default `theme_color` ([#344](https://github.com/somethingnew71/pwa-module-bridge/issues/344)) ([a18a79f](https://github.com/somethingnew71/pwa-module-bridge/commit/a18a79f62a49a3a563621929e30fc8703c3c133a))
* **manifest:** invalidate start_url cache ([240d4a1](https://github.com/somethingnew71/pwa-module-bridge/commit/240d4a14868fe46ab98bb79ba3a22c7973875d45))
* **manifest:** remove publicPath field ([b03dc14](https://github.com/somethingnew71/pwa-module-bridge/commit/b03dc14b7c99cbf0eac9470f09b50d9089ea760a))
* **manifest:** run only on build ([ecaa835](https://github.com/somethingnew71/pwa-module-bridge/commit/ecaa8355f76d9bd9ea12392b557254b743548600))
* **meta:** add missing `hid` to icon tags ([#428](https://github.com/somethingnew71/pwa-module-bridge/issues/428)) ([d9addb7](https://github.com/somethingnew71/pwa-module-bridge/commit/d9addb7917363e812fe277acc1cf228018a8342b))
* **meta:** add missing `router.base` prefix to favicon ([#354](https://github.com/somethingnew71/pwa-module-bridge/issues/354)) ([3e910ae](https://github.com/somethingnew71/pwa-module-bridge/commit/3e910ae7e87d341c6a6ea018d013105ce1721b5b))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/somethingnew71/pwa-module-bridge/issues/23)) ([76a1f89](https://github.com/somethingnew71/pwa-module-bridge/commit/76a1f89259224f195084515d4b88d05376e1402a))
* **meta:** allow setting `appleStatusBarStyle` without `mobileAppIOS` ([b0f226a](https://github.com/somethingnew71/pwa-module-bridge/commit/b0f226aadeee50b47790ac064852b444e33d9b95)), closes [#338](https://github.com/somethingnew71/pwa-module-bridge/issues/338)
* **meta:** avoid unnecessary log for meta.json ([de8e039](https://github.com/somethingnew71/pwa-module-bridge/commit/de8e039740a5618b59312682ecdea4f023d88414))
* **meta:** fix `mergeMeta` cjs export ([774f1a8](https://github.com/somethingnew71/pwa-module-bridge/commit/774f1a87d8c102ad3754374e53a41b434a01b82c))
* **meta:** fix issues regarding favicon.ico fallback ([7a1e773](https://github.com/somethingnew71/pwa-module-bridge/commit/7a1e77384eb88f0886180bc784efa242ae59e5ad))
* **meta:** generate only on build ([1cace26](https://github.com/somethingnew71/pwa-module-bridge/commit/1cace266e3528aa53d5a562e3d7ce1fefff7f4dc))
* **meta:** load meta when `ssr` is disable and using `nuxt dev` (fixes [#219](https://github.com/somethingnew71/pwa-module-bridge/issues/219)) ([b6a5ead](https://github.com/somethingnew71/pwa-module-bridge/commit/b6a5ead17cdb8f2edff9d12c326ae59d8ac372be))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/somethingnew71/pwa-module-bridge/issues/44)) ([354f818](https://github.com/somethingnew71/pwa-module-bridge/commit/354f818708e91cbabbbe97fdfaceecce90236689))
* **meta:** prevent build failure for ios splash image when no icon is used ([#362](https://github.com/somethingnew71/pwa-module-bridge/issues/362)) ([494eed5](https://github.com/somethingnew71/pwa-module-bridge/commit/494eed5db00e7cf6863fc854e6ccb6b7bb8c0ba4))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/somethingnew71/pwa-module-bridge/commit/cf48b3fb6c64fe4cbbac2ae8bb4474cbd21390b3)), closes [#10](https://github.com/somethingnew71/pwa-module-bridge/issues/10)
* **module:** handle readJSFiles for string param ([#143](https://github.com/somethingnew71/pwa-module-bridge/issues/143)) ([4f06479](https://github.com/somethingnew71/pwa-module-bridge/commit/4f064799cf01b95432b0f7d28b7010b60b9f4146))
* **module:** icon purpose warning appearing when it shouldn't ([#305](https://github.com/somethingnew71/pwa-module-bridge/issues/305)) ([5833e31](https://github.com/somethingnew71/pwa-module-bridge/commit/5833e311e0379f6617c845a4f319733047ef7a53))
* offlinePage syntax error ([af21d74](https://github.com/somethingnew71/pwa-module-bridge/commit/af21d7401a9f28932ed98a08cdf2363a708e6777))
* **onesignal:** add cache query to sw.js ([33f8f61](https://github.com/somethingnew71/pwa-module-bridge/commit/33f8f61ffac193c7ccdeeb65a294925253460e6f))
* **onesignal:** ensure no duplicate script is added ([#161](https://github.com/somethingnew71/pwa-module-bridge/issues/161)) ([89c1a1d](https://github.com/somethingnew71/pwa-module-bridge/commit/89c1a1da2a55125867c1ddae4cb7144ddb5ca6d5))
* path ogImage if is url ([#121](https://github.com/somethingnew71/pwa-module-bridge/issues/121)) ([d6dc82b](https://github.com/somethingnew71/pwa-module-bridge/commit/d6dc82b9c11b33735b9b27006855ca64994c15fd))
* precached files are not updated ([#386](https://github.com/somethingnew71/pwa-module-bridge/issues/386)) ([872dce1](https://github.com/somethingnew71/pwa-module-bridge/commit/872dce1ec2df58cbf6efcfe4a080f632510ea32b))
* **pwa-utils:** don't combine with esm ([fddfa7a](https://github.com/somethingnew71/pwa-module-bridge/commit/fddfa7a687f043aaa4a3719a02f45b7cc803214a)), closes [#147](https://github.com/somethingnew71/pwa-module-bridge/issues/147)
* **pwa-utils:** ensure joinUrl not modifying scheme part ([09a465a](https://github.com/somethingnew71/pwa-module-bridge/commit/09a465ac888c947fd8119a57f27c54c370694ee4))
* **pwa-utils:** handle non-strings in `startCase` ([#150](https://github.com/somethingnew71/pwa-module-bridge/issues/150)) ([782217a](https://github.com/somethingnew71/pwa-module-bridge/commit/782217aca8ea2ece277cb20eaee54b536d55435a))
* **pwa:** no more optimize dependency ([a1c149f](https://github.com/somethingnew71/pwa-module-bridge/commit/a1c149f75b41976b3efe99e26a01d68f1c5af639))
* relax pages regex for workbox 4 compatiblity ([04e74a7](https://github.com/somethingnew71/pwa-module-bridge/commit/04e74a7843ea54bcebca491c9abc0daa7ede3515))
* revert compileTemplate as is fixed by nuxt/nuxt.js[#6283](https://github.com/somethingnew71/pwa-module-bridge/issues/6283) for 2.9.x ([d0f96de](https://github.com/somethingnew71/pwa-module-bridge/commit/d0f96de4f40cb33bb859ed8401205fcb70181747))
* routing order for default offline route (/.*). it must be last order ([#100](https://github.com/somethingnew71/pwa-module-bridge/issues/100)) ([1c829d0](https://github.com/somethingnew71/pwa-module-bridge/commit/1c829d01d23ca4fd40a23eecbfc24ce6be48e48d))
* serve static webpack assets from disk in dev mode (fixes [#373](https://github.com/somethingnew71/pwa-module-bridge/issues/373)) ([8298f95](https://github.com/somethingnew71/pwa-module-bridge/commit/8298f955bf80eb44090cfb7b56070dc7e1a50aa8))
* **serveStatic:** wrap serveStatic in `fromNodeMiddleware` for @nuxt/bridge compatibility (fixes [#532](https://github.com/somethingnew71/pwa-module-bridge/issues/532)) ([87457c7](https://github.com/somethingnew71/pwa-module-bridge/commit/87457c7d13dfc2bb2ea609c1c07a1388b3b53704))
* stateWhileRevalidate() -> networkOnly() ([832d60f](https://github.com/somethingnew71/pwa-module-bridge/commit/832d60fc1364ddff608822e36d4a70c7eaa04f39))
* support build cache ([#371](https://github.com/somethingnew71/pwa-module-bridge/issues/371)) ([9a825c9](https://github.com/somethingnew71/pwa-module-bridge/commit/9a825c9d47c057c5934030142cb6e46d23a46e21))
* truncate manifest hash ([5c74621](https://github.com/somethingnew71/pwa-module-bridge/commit/5c746218a5eafd21d51e5ad9fd330a2bcac04802))
* **types:** mark module options fields as optional ([#420](https://github.com/somethingnew71/pwa-module-bridge/issues/420)) ([7d75c28](https://github.com/somethingnew71/pwa-module-bridge/commit/7d75c285485efde4081127ff3bb899565a771c7e))
* use shared pwa context ([3c19bae](https://github.com/somethingnew71/pwa-module-bridge/commit/3c19baebc0a1dba5e8b7ef20c7230e81ce6a8e95))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/somethingnew71/pwa-module-bridge/commit/a0fb9084462d5f212009ec80cf0c64142ff59126))
* **workbox:** add additional details for uncaught errors and fix chromium CORS ([#417](https://github.com/somethingnew71/pwa-module-bridge/issues/417)) ([f20489c](https://github.com/somethingnew71/pwa-module-bridge/commit/f20489c2cc289b9d6f90143078f415d97b3cf4c1))
* **workbox:** add missing lodash dependency ([#91](https://github.com/somethingnew71/pwa-module-bridge/issues/91)) ([da2c36f](https://github.com/somethingnew71/pwa-module-bridge/commit/da2c36f90668f9744cb5e8854b677037a70b862e))
* **workbox:** always prepend routerBase to swURL ([d3a52b6](https://github.com/somethingnew71/pwa-module-bridge/commit/d3a52b6e9e5672e06e69269152b9625ae1152b17)), closes [#157](https://github.com/somethingnew71/pwa-module-bridge/issues/157)
* **workbox:** deepClone options to avoid cross-build mutation ([e39027e](https://github.com/somethingnew71/pwa-module-bridge/commit/e39027ee7159103d755fe67c1c105235f3257739))
* **workbox:** disable `cacheAssets` for dev mode ([dbf6d67](https://github.com/somethingnew71/pwa-module-bridge/commit/dbf6d67bea83a4e9376a77d46e449606f42c45bf))
* **workbox:** faster service worker register ([07524a2](https://github.com/somethingnew71/pwa-module-bridge/commit/07524a2d4e5605743660b6f0b1e0ceb74aa609ee))
* **workbox:** handle `offlinePage` options (fixes [#365](https://github.com/somethingnew71/pwa-module-bridge/issues/365)) ([2b9856e](https://github.com/somethingnew71/pwa-module-bridge/commit/2b9856e9c226c5f286acb5116cb381e2fc550248))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/somethingnew71/pwa-module-bridge/issues/73)) ([6d241ec](https://github.com/somethingnew71/pwa-module-bridge/commit/6d241ec8518945115f85892e99de910221420810))
* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/somethingnew71/pwa-module-bridge/issues/83). ([c7102fd](https://github.com/somethingnew71/pwa-module-bridge/commit/c7102fdede1f790044cdd7e88212997b4693d963))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/somethingnew71/pwa-module-bridge/commit/b744a270e16d418f826ab8035c184b4bbe3d4185))
* **workbox:** missing required parameter request for `handle()` ([#335](https://github.com/somethingnew71/pwa-module-bridge/issues/335)) ([eedf23f](https://github.com/somethingnew71/pwa-module-bridge/commit/eedf23fa3ab478f8a449817528d0270507babfc8))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/somethingnew71/pwa-module-bridge/issues/83). ([7a8bb3b](https://github.com/somethingnew71/pwa-module-bridge/commit/7a8bb3bf0469093b3f57a75d2a934860edee4fbf))
* **workbox:** New configuration for specifying plugins when configuring a strategy ([#337](https://github.com/somethingnew71/pwa-module-bridge/issues/337)) ([dacf7ec](https://github.com/somethingnew71/pwa-module-bridge/commit/dacf7ec3613a6cb985990eab6c78879b78bdbbbc)), closes [/github.com/nuxt-community/pwa-module/pull/337#issuecomment-681870522](https://github.com/somethingnew71//github.com/nuxt-community/pwa-module/pull/337/issues/issuecomment-681870522)
* **workbox:** precache `start_url` (resolves [#372](https://github.com/somethingnew71/pwa-module-bridge/issues/372)) ([27e19a0](https://github.com/somethingnew71/pwa-module-bridge/commit/27e19a04d6f2b14943a0bb4a9b7414382591d4e0))
* **workbox:** restore `sw.js` with smart build (fixes [#352](https://github.com/somethingnew71/pwa-module-bridge/issues/352)) ([491f440](https://github.com/somethingnew71/pwa-module-bridge/commit/491f440936e107c424864a1aa1121e6995d4e87b))
* **workbox:** unregister only to avoid loop ([44c5cd3](https://github.com/somethingnew71/pwa-module-bridge/commit/44c5cd3aa86f12929aeb03d37cfa20df5171f855))
* **workbox:** use NetworkFirst for dev ([9a67580](https://github.com/somethingnew71/pwa-module-bridge/commit/9a67580badc5f3d80fc1d56f8b5a44dc4aebf60b))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/somethingnew71/pwa-module-bridge/issues/14). ([f384103](https://github.com/somethingnew71/pwa-module-bridge/commit/f384103e55b2109f8a6302fd4dcbeed13530163d))


* update execa to 4.x ([301a07c](https://github.com/somethingnew71/pwa-module-bridge/commit/301a07cd8733b29231bdfbc0390681e59f5decb7))
* only support nuxt.hook ([854d826](https://github.com/somethingnew71/pwa-module-bridge/commit/854d826e05363a4a8756ed77159fcd532f11b353))
* use tapable hooks ([#103](https://github.com/somethingnew71/pwa-module-bridge/issues/103)) ([9f27d5c](https://github.com/somethingnew71/pwa-module-bridge/commit/9f27d5cdae0e0341d6d4b4f6814f91db6eab1432))

## 4.0.0 (2023-03-15)


### ⚠ BREAKING CHANGES

* Requeires Node 10.x
* **workbox:** default changed from NetworkOnly to NetworkFirst when offlinePage is enabled
* needs nuxt 2.x or later
* webpack >= 4 (Nuxt >= 2) is required

### Features

* `pwa.` scopped options ([010fe0e](https://github.com/somethingnew71/pwa-module-bridge/commit/010fe0e0ec0266c39392c831020d477bbb0e3acc))
* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/somethingnew71/pwa-module-bridge/commit/c0efb1d2f9923f227ffbb5421ec285c97d3daca6))
* add HMR test suit ([ff3d502](https://github.com/somethingnew71/pwa-module-bridge/commit/ff3d5023b0c91b2795889297143a293077b293fb))
* add og:image support ([#30](https://github.com/somethingnew71/pwa-module-bridge/issues/30)) ([afebd96](https://github.com/somethingnew71/pwa-module-bridge/commit/afebd962d2047c5e9efd039b6832e8503632fcce))
* add oneSignal module ([bbc7b72](https://github.com/somethingnew71/pwa-module-bridge/commit/bbc7b72b3742643c02b8c82276359e43bf60ee87))
* add option to register third-party sw ([#12](https://github.com/somethingnew71/pwa-module-bridge/issues/12)) ([9c0b61e](https://github.com/somethingnew71/pwa-module-bridge/commit/9c0b61e3e22754fb1de9ab43ecb049791822eb2e))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/somethingnew71/pwa-module-bridge/commit/b17bbd04dc67778004392da91841092e55847d37))
* add types ([#323](https://github.com/somethingnew71/pwa-module-bridge/issues/323)) ([8723d07](https://github.com/somethingnew71/pwa-module-bridge/commit/8723d076cb87ff9e583ba755f72f4d62360d6eb1))
* cleanupOutdatedCaches ([9167013](https://github.com/somethingnew71/pwa-module-bridge/commit/91670138999cb3039b42ee9b398b6bcafe7db650))
* **icon:** add combined option sources ([539430f](https://github.com/somethingnew71/pwa-module-bridge/commit/539430fdf540e2f0be8ebd6417454ad0a316c9b0))
* **icon:** add support for icon purpose ([#246](https://github.com/somethingnew71/pwa-module-bridge/issues/246)) ([9248174](https://github.com/somethingnew71/pwa-module-bridge/commit/9248174fe8bac352318c8fe292012156ccfd56ad))
* **icon:** allow reading icon from assetc/icon.png ([#29](https://github.com/somethingnew71/pwa-module-bridge/issues/29)) ([9e0fde3](https://github.com/somethingnew71/pwa-module-bridge/commit/9e0fde33df9e6fe3e3c275f577ad91f92e180433))
* **icon:** default purpose to any + maskable ([30f0f63](https://github.com/somethingnew71/pwa-module-bridge/commit/30f0f63bcd1601cc6aa5595a851de965dde9af88))
* **icon:** expose options.cacheDir ([f8dbf1d](https://github.com/somethingnew71/pwa-module-bridge/commit/f8dbf1dac99519648a53dc22ab4019af25a677aa))
* **icon:** make icons accessible ([#51](https://github.com/somethingnew71/pwa-module-bridge/issues/51)) ([92bccd3](https://github.com/somethingnew71/pwa-module-bridge/commit/92bccd37cf2e1b2471ea3d70126a7428a983b083))
* **icon:** new options ([#126](https://github.com/somethingnew71/pwa-module-bridge/issues/126)) ([12e6576](https://github.com/somethingnew71/pwa-module-bridge/commit/12e65762e995f9f270e3b88ed1938990d49d0607))
* **icon:** register `favicon.ico` when available ([#258](https://github.com/somethingnew71/pwa-module-bridge/issues/258)) ([7a48d2a](https://github.com/somethingnew71/pwa-module-bridge/commit/7a48d2a60b1f2ccaa1287789adb846806afd5224))
* **icon:** rename `accessibleIcons` to `iconPlugin` ([3e175f9](https://github.com/somethingnew71/pwa-module-bridge/commit/3e175f93c046028b6f3f9479085ec98d014b460b))
* **icon:** support for iOS splash screens ([#308](https://github.com/somethingnew71/pwa-module-bridge/issues/308)) ([f4eeda7](https://github.com/somethingnew71/pwa-module-bridge/commit/f4eeda7ce05cdd7dda4e4c4ab81e986f6c94a951))
* **icon:** update to jimp 0.5.0 ([b071c4b](https://github.com/somethingnew71/pwa-module-bridge/commit/b071c4b437d8cf5a51721129131f19f7ff13e586))
* improve computed cacheId ([cd6c9cc](https://github.com/somethingnew71/pwa-module-bridge/commit/cd6c9cc6d7233145d212379aac514c3bc339a493))
* improve sw.register error handling ([9aa76f8](https://github.com/somethingnew71/pwa-module-bridge/commit/9aa76f89bdf34cefc018ae602a2514bf9ea38944))
* **manifest:** add `useWebmanifestExtension` option and improve docs ([#241](https://github.com/somethingnew71/pwa-module-bridge/issues/241)) ([4484e6c](https://github.com/somethingnew71/pwa-module-bridge/commit/4484e6c697c5534103969894252f1d356d4016ee))
* **manifest:** add revision to start_url ([ad26827](https://github.com/somethingnew71/pwa-module-bridge/commit/ad26827a9d76b6a4f1123f8a06fd0c946b90b5dd))
* **manifest:** allow overriding publicPath ([#19](https://github.com/somethingnew71/pwa-module-bridge/issues/19)) ([4e6782e](https://github.com/somethingnew71/pwa-module-bridge/commit/4e6782ed7d261055b40cbc0678624c74d89897c1))
* **manifest:** support crossorigin option ([#71](https://github.com/somethingnew71/pwa-module-bridge/issues/71)) ([ccb2c33](https://github.com/somethingnew71/pwa-module-bridge/commit/ccb2c339e9092c162c29dab9c36bb7cfdd51883a))
* **meta:** add author property ([#41](https://github.com/somethingnew71/pwa-module-bridge/issues/41)) ([cafcfc4](https://github.com/somethingnew71/pwa-module-bridge/commit/cafcfc40eb020a03c0f39d2a121c4f1a54e915b6))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/somethingnew71/pwa-module-bridge/commit/3c7aa7d0199ce3ab0d7fff606d52b913dba0f34e)), closes [#10](https://github.com/somethingnew71/pwa-module-bridge/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/somethingnew71/pwa-module-bridge/issues/42)) ([3990ddf](https://github.com/somethingnew71/pwa-module-bridge/commit/3990ddf325bfe092d7590dee4ca6877cc638c4dc))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/somethingnew71/pwa-module-bridge/commit/dc39fcbaa2fa63ecf909c0183b0a55b3f3ad2397))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/somethingnew71/pwa-module-bridge/issues/43)) ([fe11c76](https://github.com/somethingnew71/pwa-module-bridge/commit/fe11c76941ba53eb85659c3cd9a970924f51abf3))
* **meta:** merge head at runtime ([#363](https://github.com/somethingnew71/pwa-module-bridge/issues/363)) ([c0d86ea](https://github.com/somethingnew71/pwa-module-bridge/commit/c0d86ead374efcfd66282959e65055262e4a27cf))
* **module:** allow disabling with top-level options ([65800f9](https://github.com/somethingnew71/pwa-module-bridge/commit/65800f91a671e61d59a9faf885c2ff7ecc9d9ca0))
* offlineAnalytics ([#55](https://github.com/somethingnew71/pwa-module-bridge/issues/55)) ([4c4d3ff](https://github.com/somethingnew71/pwa-module-bridge/commit/4c4d3ff93f16eb25ce51027a43e559e2da8a601f))
* ogSiteName ([#50](https://github.com/somethingnew71/pwa-module-bridge/issues/50)) ([0c99ab9](https://github.com/somethingnew71/pwa-module-bridge/commit/0c99ab94cb8f6f06e0658f958345609f31da7748))
* **onesignal:** enable CDN by default ([7c78c67](https://github.com/somethingnew71/pwa-module-bridge/commit/7c78c679283f6314bc9e7695411b962fd9f835ce))
* **onesignal:** move init options under init ([dd61c18](https://github.com/somethingnew71/pwa-module-bridge/commit/dd61c18093ada4ed936c08b6a25a96d7f93cdfbb))
* options.dev ([fb0d38c](https://github.com/somethingnew71/pwa-module-bridge/commit/fb0d38cdaec4821f479222b038d88a1a56d06e19))
* remove debug ([92ba73e](https://github.com/somethingnew71/pwa-module-bridge/commit/92ba73e9cccca6c3561d8b6a0b27b00ccf86f720))
* rewrite icon with async image resizer ([#171](https://github.com/somethingnew71/pwa-module-bridge/issues/171)) ([a4a457e](https://github.com/somethingnew71/pwa-module-bridge/commit/a4a457efe98461cf28249742952ca49e9ebfe847))
* rewrite workbox ([#122](https://github.com/somethingnew71/pwa-module-bridge/issues/122)) ([9e49896](https://github.com/somethingnew71/pwa-module-bridge/commit/9e49896be3f89b15116c60a6ddebf71d62a131c9))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/somethingnew71/pwa-module-bridge/commit/fdcda0f420b01f637e9ddd8b7ad127c8e5cf2e86))
* support `manifest.fileName` with template ([f05353b](https://github.com/somethingnew71/pwa-module-bridge/commit/f05353b7ccfef88f5f95f0fa7b0109c2ece4236b)), closes [#193](https://github.com/somethingnew71/pwa-module-bridge/issues/193)
* sync workbox version with workbox-window ([9a3632a](https://github.com/somethingnew71/pwa-module-bridge/commit/9a3632a8cda8d66c454d76bf633a0ebf14218487))
* update onesignal sdk once ([c08e423](https://github.com/somethingnew71/pwa-module-bridge/commit/c08e4231991d849eb1c7c63942109f034afaee3e))
* use `jimp-compact` ([5e37b58](https://github.com/somethingnew71/pwa-module-bridge/commit/5e37b58a3c6b07062ab012d3c53641e2d9e7302a))
* use better regexes ([318228e](https://github.com/somethingnew71/pwa-module-bridge/commit/318228e8a88a97f4a50e86ebf4b784acd48f523d))
* use integraty file to invalidate icon cache ([6661a09](https://github.com/somethingnew71/pwa-module-bridge/commit/6661a09f86bbc169a99effac3d9cb1620f530b3d))
* **worbox:** add offline option for making it optional ([#59](https://github.com/somethingnew71/pwa-module-bridge/issues/59)) ([76de33c](https://github.com/somethingnew71/pwa-module-bridge/commit/76de33cc4f7dde9e1b930be773add3736851a95e)), closes [#24](https://github.com/somethingnew71/pwa-module-bridge/issues/24)
* **worbox:** offlineAssets ([#86](https://github.com/somethingnew71/pwa-module-bridge/issues/86)) ([27c8fa1](https://github.com/somethingnew71/pwa-module-bridge/commit/27c8fa1b5c89a1f2ae044a1eac8028757bfa029b))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/somethingnew71/pwa-module-bridge/commit/5ac89cffdb7b9462172399f7789a4f56031fb53d))
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/somethingnew71/pwa-module-bridge/commit/f1e1fe127c7a9e15e74dbed243194c68a6422ed2))
* **workbox:** allow cache names to be configured ([#154](https://github.com/somethingnew71/pwa-module-bridge/issues/154)) ([2d7ed53](https://github.com/somethingnew71/pwa-module-bridge/commit/2d7ed53a3e66fa8d9607591ddfc9225ecbc7744a))
* **workbox:** assetsURLPattern, pagesURLPattern ([5fc3d66](https://github.com/somethingnew71/pwa-module-bridge/commit/5fc3d66856d9d932c66b8c6b0a72362ff01c2758))
* **workbox:** bump to 4.0.0-rc.2 ([7e278f0](https://github.com/somethingnew71/pwa-module-bridge/commit/7e278f0d3cf37a8c9b7ba6d06fd85ceb464abd0e))
* **workbox:** change the order of default runtimeCache ([#106](https://github.com/somethingnew71/pwa-module-bridge/issues/106)) ([033b504](https://github.com/somethingnew71/pwa-module-bridge/commit/033b50472bd4172ce562b9efb818d093458861c5))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/somethingnew71/pwa-module-bridge/commit/e7677d8c317aa4c189dfe563a2ec5e279d53d691))
* **workbox:** enabled option and self destroying sw ([c64226c](https://github.com/somethingnew71/pwa-module-bridge/commit/c64226cea36c1b0b9f0efe7640439e6bb134ddce))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/somethingnew71/pwa-module-bridge/commit/a5ddf5992c61ee759a292d1af95a2cf0daac9d73))
* workboxExtensions and extension reading fixes ([5c56484](https://github.com/somethingnew71/pwa-module-bridge/commit/5c564844047e86484ace65bfcffbdf542528e420))
* **workbox:** importScripts option ([7c8644c](https://github.com/somethingnew71/pwa-module-bridge/commit/7c8644cbf612a5686e590074a2848e10cf9c37c8))
* **workbox:** improve sw.register ([c35f610](https://github.com/somethingnew71/pwa-module-bridge/commit/c35f6104a66ef125a0d33f8e32ee8f5f9a1cfc28))
* **workbox:** make plugin fully asynchronous ([1eb1190](https://github.com/somethingnew71/pwa-module-bridge/commit/1eb11905a7499cb3b886265969a939d55eb53ca1))
* **workbox:** offline page assets ([#85](https://github.com/somethingnew71/pwa-module-bridge/issues/85)) ([8bc4a3b](https://github.com/somethingnew71/pwa-module-bridge/commit/8bc4a3bbca296f9470f6ec7b63cef1abae810932))
* **workbox:** offlineStrategy ([e377436](https://github.com/somethingnew71/pwa-module-bridge/commit/e377436cedf7fc88288889a1021dfe2855e783b4))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/somethingnew71/pwa-module-bridge/issues/80)) ([88cc602](https://github.com/somethingnew71/pwa-module-bridge/commit/88cc60275d8e4cff46d20c99708bd34a689c2aba))
* **workbox:** preCaching option ([67f1c3d](https://github.com/somethingnew71/pwa-module-bridge/commit/67f1c3d1b839b05f2c09d436c4eec62675001030))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/somethingnew71/pwa-module-bridge/commit/b0af84e0751bc023e33b6bc6923ae2a17fb8d0a1))
* **workbox:** support pass config object to `workbox.setConfig` ([#95](https://github.com/somethingnew71/pwa-module-bridge/issues/95)) ([b5dab8a](https://github.com/somethingnew71/pwa-module-bridge/commit/b5dab8a821eb474ecd5351cc2d779a4c17ed4802))
* **workbox:** upgrade workboxVersion to 4.0.0-rc.0 ([b364572](https://github.com/somethingnew71/pwa-module-bridge/commit/b3645727e43817027bed6e32e1c06b8ad2bfb559))
* **workbox:** use workbox 4.0.0-0 ([70813ef](https://github.com/somethingnew71/pwa-module-bridge/commit/70813ef1146fa0a1db27534531f82b537d7e0f14))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/somethingnew71/pwa-module-bridge/issues/60)) ([0fef874](https://github.com/somethingnew71/pwa-module-bridge/commit/0fef874441e0b98230cb3a96d7035cdebcd294e4))
* **workbox:** workbox-window support ([2e356d0](https://github.com/somethingnew71/pwa-module-bridge/commit/2e356d059ee73810db5512fedbd92f92d9e2e822))


### Bug Fixes

* add workboxExtensions to defaults ([#138](https://github.com/somethingnew71/pwa-module-bridge/issues/138)) ([ac8ba74](https://github.com/somethingnew71/pwa-module-bridge/commit/ac8ba745b81ef339665661a7fa436ab48819d801))
* append to start_url without query param (fixes [#403](https://github.com/somethingnew71/pwa-module-bridge/issues/403)) ([054b8a2](https://github.com/somethingnew71/pwa-module-bridge/commit/054b8a299274fafc61275b50374b4eb1e83e7e46))
* avoid adding revision to start_url ([1c44cff](https://github.com/somethingnew71/pwa-module-bridge/commit/1c44cffbe1ae7c9096c5696d6b6521f60b3fe32f))
* **docs:** add reference to pwa module ([49b7c49](https://github.com/somethingnew71/pwa-module-bridge/commit/49b7c49b7b79b613bdbedc4fa3c97d5bff7feaa2))
* don't override title when titleTemplate is provided  ([#48](https://github.com/somethingnew71/pwa-module-bridge/issues/48)) ([8c3f319](https://github.com/somethingnew71/pwa-module-bridge/commit/8c3f319a0ca3983535c88feff2c444d544d3dd45))
* expose modified pwa context to the config ([c325e44](https://github.com/somethingnew71/pwa-module-bridge/commit/c325e4434b940789309f80aa91b1e436363aa906))
* **icon:** await on build ([e3c1be2](https://github.com/somethingnew71/pwa-module-bridge/commit/e3c1be2c7804ec374116d0c177a1537b6c764042))
* **icon:** clean cacheDir when generating icons ([1e6eb19](https://github.com/somethingnew71/pwa-module-bridge/commit/1e6eb19851bbb6bcb51106cea5611475edec75cc))
* **icon:** fork without original process args ([#343](https://github.com/somethingnew71/pwa-module-bridge/issues/343)) ([8b1f19f](https://github.com/somethingnew71/pwa-module-bridge/commit/8b1f19f56ddc31a49445334ddc8abe2162b4b760))
* **icon:** generate only on build ([9d68d70](https://github.com/somethingnew71/pwa-module-bridge/commit/9d68d70bb8ce5d3f9ef23b98e305e8ac136d8ef2))
* **icon:** handle jimp.write callback ([bffe6ed](https://github.com/somethingnew71/pwa-module-bridge/commit/bffe6eda94e266e17e0dee7069a63393b6dc9455))
* **icon:** handle situation where the iconSrc is `null` or `undefined` ([#187](https://github.com/somethingnew71/pwa-module-bridge/issues/187)) ([66be874](https://github.com/somethingnew71/pwa-module-bridge/commit/66be874bbdbb9ba796e0406c63a455455bc4caf2))
* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/somethingnew71/pwa-module-bridge/issues/84)) ([3f0e718](https://github.com/somethingnew71/pwa-module-bridge/commit/3f0e71892f6d1c39090dad4107d74871f4a44446))
* **icon:** update warning url to docs ([#329](https://github.com/somethingnew71/pwa-module-bridge/issues/329)) ([61633fa](https://github.com/somethingnew71/pwa-module-bridge/commit/61633fa640793c344748efdf790a56456fad8e2f))
* **manifest:** do not use nuxt loading bar color as default `theme_color` ([#344](https://github.com/somethingnew71/pwa-module-bridge/issues/344)) ([a18a79f](https://github.com/somethingnew71/pwa-module-bridge/commit/a18a79f62a49a3a563621929e30fc8703c3c133a))
* **manifest:** invalidate start_url cache ([240d4a1](https://github.com/somethingnew71/pwa-module-bridge/commit/240d4a14868fe46ab98bb79ba3a22c7973875d45))
* **manifest:** remove publicPath field ([b03dc14](https://github.com/somethingnew71/pwa-module-bridge/commit/b03dc14b7c99cbf0eac9470f09b50d9089ea760a))
* **manifest:** run only on build ([ecaa835](https://github.com/somethingnew71/pwa-module-bridge/commit/ecaa8355f76d9bd9ea12392b557254b743548600))
* **meta:** add missing `hid` to icon tags ([#428](https://github.com/somethingnew71/pwa-module-bridge/issues/428)) ([d9addb7](https://github.com/somethingnew71/pwa-module-bridge/commit/d9addb7917363e812fe277acc1cf228018a8342b))
* **meta:** add missing `router.base` prefix to favicon ([#354](https://github.com/somethingnew71/pwa-module-bridge/issues/354)) ([3e910ae](https://github.com/somethingnew71/pwa-module-bridge/commit/3e910ae7e87d341c6a6ea018d013105ce1721b5b))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/somethingnew71/pwa-module-bridge/issues/23)) ([76a1f89](https://github.com/somethingnew71/pwa-module-bridge/commit/76a1f89259224f195084515d4b88d05376e1402a))
* **meta:** allow setting `appleStatusBarStyle` without `mobileAppIOS` ([b0f226a](https://github.com/somethingnew71/pwa-module-bridge/commit/b0f226aadeee50b47790ac064852b444e33d9b95)), closes [#338](https://github.com/somethingnew71/pwa-module-bridge/issues/338)
* **meta:** avoid unnecessary log for meta.json ([de8e039](https://github.com/somethingnew71/pwa-module-bridge/commit/de8e039740a5618b59312682ecdea4f023d88414))
* **meta:** fix `mergeMeta` cjs export ([774f1a8](https://github.com/somethingnew71/pwa-module-bridge/commit/774f1a87d8c102ad3754374e53a41b434a01b82c))
* **meta:** fix issues regarding favicon.ico fallback ([7a1e773](https://github.com/somethingnew71/pwa-module-bridge/commit/7a1e77384eb88f0886180bc784efa242ae59e5ad))
* **meta:** generate only on build ([1cace26](https://github.com/somethingnew71/pwa-module-bridge/commit/1cace266e3528aa53d5a562e3d7ce1fefff7f4dc))
* **meta:** load meta when `ssr` is disable and using `nuxt dev` (fixes [#219](https://github.com/somethingnew71/pwa-module-bridge/issues/219)) ([b6a5ead](https://github.com/somethingnew71/pwa-module-bridge/commit/b6a5ead17cdb8f2edff9d12c326ae59d8ac372be))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/somethingnew71/pwa-module-bridge/issues/44)) ([354f818](https://github.com/somethingnew71/pwa-module-bridge/commit/354f818708e91cbabbbe97fdfaceecce90236689))
* **meta:** prevent build failure for ios splash image when no icon is used ([#362](https://github.com/somethingnew71/pwa-module-bridge/issues/362)) ([494eed5](https://github.com/somethingnew71/pwa-module-bridge/commit/494eed5db00e7cf6863fc854e6ccb6b7bb8c0ba4))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/somethingnew71/pwa-module-bridge/commit/cf48b3fb6c64fe4cbbac2ae8bb4474cbd21390b3)), closes [#10](https://github.com/somethingnew71/pwa-module-bridge/issues/10)
* **module:** handle readJSFiles for string param ([#143](https://github.com/somethingnew71/pwa-module-bridge/issues/143)) ([4f06479](https://github.com/somethingnew71/pwa-module-bridge/commit/4f064799cf01b95432b0f7d28b7010b60b9f4146))
* **module:** icon purpose warning appearing when it shouldn't ([#305](https://github.com/somethingnew71/pwa-module-bridge/issues/305)) ([5833e31](https://github.com/somethingnew71/pwa-module-bridge/commit/5833e311e0379f6617c845a4f319733047ef7a53))
* offlinePage syntax error ([af21d74](https://github.com/somethingnew71/pwa-module-bridge/commit/af21d7401a9f28932ed98a08cdf2363a708e6777))
* **onesignal:** add cache query to sw.js ([33f8f61](https://github.com/somethingnew71/pwa-module-bridge/commit/33f8f61ffac193c7ccdeeb65a294925253460e6f))
* **onesignal:** ensure no duplicate script is added ([#161](https://github.com/somethingnew71/pwa-module-bridge/issues/161)) ([89c1a1d](https://github.com/somethingnew71/pwa-module-bridge/commit/89c1a1da2a55125867c1ddae4cb7144ddb5ca6d5))
* path ogImage if is url ([#121](https://github.com/somethingnew71/pwa-module-bridge/issues/121)) ([d6dc82b](https://github.com/somethingnew71/pwa-module-bridge/commit/d6dc82b9c11b33735b9b27006855ca64994c15fd))
* precached files are not updated ([#386](https://github.com/somethingnew71/pwa-module-bridge/issues/386)) ([872dce1](https://github.com/somethingnew71/pwa-module-bridge/commit/872dce1ec2df58cbf6efcfe4a080f632510ea32b))
* **pwa-utils:** don't combine with esm ([fddfa7a](https://github.com/somethingnew71/pwa-module-bridge/commit/fddfa7a687f043aaa4a3719a02f45b7cc803214a)), closes [#147](https://github.com/somethingnew71/pwa-module-bridge/issues/147)
* **pwa-utils:** ensure joinUrl not modifying scheme part ([09a465a](https://github.com/somethingnew71/pwa-module-bridge/commit/09a465ac888c947fd8119a57f27c54c370694ee4))
* **pwa-utils:** handle non-strings in `startCase` ([#150](https://github.com/somethingnew71/pwa-module-bridge/issues/150)) ([782217a](https://github.com/somethingnew71/pwa-module-bridge/commit/782217aca8ea2ece277cb20eaee54b536d55435a))
* **pwa:** no more optimize dependency ([a1c149f](https://github.com/somethingnew71/pwa-module-bridge/commit/a1c149f75b41976b3efe99e26a01d68f1c5af639))
* relax pages regex for workbox 4 compatiblity ([04e74a7](https://github.com/somethingnew71/pwa-module-bridge/commit/04e74a7843ea54bcebca491c9abc0daa7ede3515))
* revert compileTemplate as is fixed by nuxt/nuxt.js[#6283](https://github.com/somethingnew71/pwa-module-bridge/issues/6283) for 2.9.x ([d0f96de](https://github.com/somethingnew71/pwa-module-bridge/commit/d0f96de4f40cb33bb859ed8401205fcb70181747))
* routing order for default offline route (/.*). it must be last order ([#100](https://github.com/somethingnew71/pwa-module-bridge/issues/100)) ([1c829d0](https://github.com/somethingnew71/pwa-module-bridge/commit/1c829d01d23ca4fd40a23eecbfc24ce6be48e48d))
* serve static webpack assets from disk in dev mode (fixes [#373](https://github.com/somethingnew71/pwa-module-bridge/issues/373)) ([8298f95](https://github.com/somethingnew71/pwa-module-bridge/commit/8298f955bf80eb44090cfb7b56070dc7e1a50aa8))
* **serveStatic:** wrap serveStatic in `fromNodeMiddleware` for @nuxt/bridge compatibility (fixes [#532](https://github.com/somethingnew71/pwa-module-bridge/issues/532)) ([87457c7](https://github.com/somethingnew71/pwa-module-bridge/commit/87457c7d13dfc2bb2ea609c1c07a1388b3b53704))
* stateWhileRevalidate() -> networkOnly() ([832d60f](https://github.com/somethingnew71/pwa-module-bridge/commit/832d60fc1364ddff608822e36d4a70c7eaa04f39))
* support build cache ([#371](https://github.com/somethingnew71/pwa-module-bridge/issues/371)) ([9a825c9](https://github.com/somethingnew71/pwa-module-bridge/commit/9a825c9d47c057c5934030142cb6e46d23a46e21))
* truncate manifest hash ([5c74621](https://github.com/somethingnew71/pwa-module-bridge/commit/5c746218a5eafd21d51e5ad9fd330a2bcac04802))
* **types:** mark module options fields as optional ([#420](https://github.com/somethingnew71/pwa-module-bridge/issues/420)) ([7d75c28](https://github.com/somethingnew71/pwa-module-bridge/commit/7d75c285485efde4081127ff3bb899565a771c7e))
* use shared pwa context ([3c19bae](https://github.com/somethingnew71/pwa-module-bridge/commit/3c19baebc0a1dba5e8b7ef20c7230e81ce6a8e95))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/somethingnew71/pwa-module-bridge/commit/a0fb9084462d5f212009ec80cf0c64142ff59126))
* **workbox:** add additional details for uncaught errors and fix chromium CORS ([#417](https://github.com/somethingnew71/pwa-module-bridge/issues/417)) ([f20489c](https://github.com/somethingnew71/pwa-module-bridge/commit/f20489c2cc289b9d6f90143078f415d97b3cf4c1))
* **workbox:** add missing lodash dependency ([#91](https://github.com/somethingnew71/pwa-module-bridge/issues/91)) ([da2c36f](https://github.com/somethingnew71/pwa-module-bridge/commit/da2c36f90668f9744cb5e8854b677037a70b862e))
* **workbox:** always prepend routerBase to swURL ([d3a52b6](https://github.com/somethingnew71/pwa-module-bridge/commit/d3a52b6e9e5672e06e69269152b9625ae1152b17)), closes [#157](https://github.com/somethingnew71/pwa-module-bridge/issues/157)
* **workbox:** deepClone options to avoid cross-build mutation ([e39027e](https://github.com/somethingnew71/pwa-module-bridge/commit/e39027ee7159103d755fe67c1c105235f3257739))
* **workbox:** disable `cacheAssets` for dev mode ([dbf6d67](https://github.com/somethingnew71/pwa-module-bridge/commit/dbf6d67bea83a4e9376a77d46e449606f42c45bf))
* **workbox:** faster service worker register ([07524a2](https://github.com/somethingnew71/pwa-module-bridge/commit/07524a2d4e5605743660b6f0b1e0ceb74aa609ee))
* **workbox:** handle `offlinePage` options (fixes [#365](https://github.com/somethingnew71/pwa-module-bridge/issues/365)) ([2b9856e](https://github.com/somethingnew71/pwa-module-bridge/commit/2b9856e9c226c5f286acb5116cb381e2fc550248))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/somethingnew71/pwa-module-bridge/issues/73)) ([6d241ec](https://github.com/somethingnew71/pwa-module-bridge/commit/6d241ec8518945115f85892e99de910221420810))
* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/somethingnew71/pwa-module-bridge/issues/83). ([c7102fd](https://github.com/somethingnew71/pwa-module-bridge/commit/c7102fdede1f790044cdd7e88212997b4693d963))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/somethingnew71/pwa-module-bridge/commit/b744a270e16d418f826ab8035c184b4bbe3d4185))
* **workbox:** missing required parameter request for `handle()` ([#335](https://github.com/somethingnew71/pwa-module-bridge/issues/335)) ([eedf23f](https://github.com/somethingnew71/pwa-module-bridge/commit/eedf23fa3ab478f8a449817528d0270507babfc8))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/somethingnew71/pwa-module-bridge/issues/83). ([7a8bb3b](https://github.com/somethingnew71/pwa-module-bridge/commit/7a8bb3bf0469093b3f57a75d2a934860edee4fbf))
* **workbox:** New configuration for specifying plugins when configuring a strategy ([#337](https://github.com/somethingnew71/pwa-module-bridge/issues/337)) ([dacf7ec](https://github.com/somethingnew71/pwa-module-bridge/commit/dacf7ec3613a6cb985990eab6c78879b78bdbbbc)), closes [/github.com/nuxt-community/pwa-module/pull/337#issuecomment-681870522](https://github.com/somethingnew71//github.com/nuxt-community/pwa-module/pull/337/issues/issuecomment-681870522)
* **workbox:** precache `start_url` (resolves [#372](https://github.com/somethingnew71/pwa-module-bridge/issues/372)) ([27e19a0](https://github.com/somethingnew71/pwa-module-bridge/commit/27e19a04d6f2b14943a0bb4a9b7414382591d4e0))
* **workbox:** restore `sw.js` with smart build (fixes [#352](https://github.com/somethingnew71/pwa-module-bridge/issues/352)) ([491f440](https://github.com/somethingnew71/pwa-module-bridge/commit/491f440936e107c424864a1aa1121e6995d4e87b))
* **workbox:** unregister only to avoid loop ([44c5cd3](https://github.com/somethingnew71/pwa-module-bridge/commit/44c5cd3aa86f12929aeb03d37cfa20df5171f855))
* **workbox:** use NetworkFirst for dev ([9a67580](https://github.com/somethingnew71/pwa-module-bridge/commit/9a67580badc5f3d80fc1d56f8b5a44dc4aebf60b))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/somethingnew71/pwa-module-bridge/issues/14). ([f384103](https://github.com/somethingnew71/pwa-module-bridge/commit/f384103e55b2109f8a6302fd4dcbeed13530163d))


* update execa to 4.x ([301a07c](https://github.com/somethingnew71/pwa-module-bridge/commit/301a07cd8733b29231bdfbc0390681e59f5decb7))
* only support nuxt.hook ([854d826](https://github.com/somethingnew71/pwa-module-bridge/commit/854d826e05363a4a8756ed77159fcd532f11b353))
* use tapable hooks ([#103](https://github.com/somethingnew71/pwa-module-bridge/issues/103)) ([9f27d5c](https://github.com/somethingnew71/pwa-module-bridge/commit/9f27d5cdae0e0341d6d4b4f6814f91db6eab1432))

### [3.3.5](https://github.com/nuxt-community/pwa-module/compare/v3.3.4...v3.3.5) (2021-01-26)


### Bug Fixes

* **meta:** add missing `hid` to icon tags ([#428](https://github.com/nuxt-community/pwa-module/issues/428)) ([d9addb7](https://github.com/nuxt-community/pwa-module/commit/d9addb7917363e812fe277acc1cf228018a8342b))

### [3.3.4](https://github.com/nuxt-community/pwa-module/compare/v3.3.3...v3.3.4) (2021-01-07)


### Bug Fixes

* **types:** mark module options fields as optional ([#420](https://github.com/nuxt-community/pwa-module/issues/420)) ([7d75c28](https://github.com/nuxt-community/pwa-module/commit/7d75c285485efde4081127ff3bb899565a771c7e))

### [3.3.3](https://github.com/nuxt-community/pwa-module/compare/v3.3.2...v3.3.3) (2020-12-20)


### Bug Fixes

* **workbox:** add additional details for uncaught errors and fix chromium CORS ([#417](https://github.com/nuxt-community/pwa-module/issues/417)) ([f20489c](https://github.com/nuxt-community/pwa-module/commit/f20489c2cc289b9d6f90143078f415d97b3cf4c1))
* **workbox:** deepClone options to avoid cross-build mutation ([e39027e](https://github.com/nuxt-community/pwa-module/commit/e39027ee7159103d755fe67c1c105235f3257739))

### [3.3.2](https://github.com/nuxt-community/pwa-module/compare/v3.3.1...v3.3.2) (2020-11-30)


### Bug Fixes

* avoid adding revision to start_url ([1c44cff](https://github.com/nuxt-community/pwa-module/commit/1c44cffbe1ae7c9096c5696d6b6521f60b3fe32f))

### [3.3.1](https://github.com/nuxt-community/pwa-module/compare/v3.3.0...v3.3.1) (2020-11-29)


### Bug Fixes

* append to start_url without query param (fixes [#403](https://github.com/nuxt-community/pwa-module/issues/403)) ([054b8a2](https://github.com/nuxt-community/pwa-module/commit/054b8a299274fafc61275b50374b4eb1e83e7e46))

## [3.3.0](https://github.com/nuxt-community/pwa-module/compare/v3.2.2...v3.3.0) (2020-11-28)


### Features

* **manifest:** add revision to start_url ([ad26827](https://github.com/nuxt-community/pwa-module/commit/ad26827a9d76b6a4f1123f8a06fd0c946b90b5dd))


### Bug Fixes

* **manifest:** invalidate start_url cache ([240d4a1](https://github.com/nuxt-community/pwa-module/commit/240d4a14868fe46ab98bb79ba3a22c7973875d45))
* precached files are not updated ([#386](https://github.com/nuxt-community/pwa-module/issues/386)) ([872dce1](https://github.com/nuxt-community/pwa-module/commit/872dce1ec2df58cbf6efcfe4a080f632510ea32b))

### [3.2.2](https://github.com/nuxt-community/pwa-module/compare/v3.2.1...v3.2.2) (2020-10-13)


### Bug Fixes

* serve static webpack assets from disk in dev mode (fixes [#373](https://github.com/nuxt-community/pwa-module/issues/373)) ([8298f95](https://github.com/nuxt-community/pwa-module/commit/8298f955bf80eb44090cfb7b56070dc7e1a50aa8))

### [3.2.1](https://github.com/nuxt-community/pwa-module/compare/v3.2.0...v3.2.1) (2020-10-13)


### Bug Fixes

* **workbox:** precache `start_url` (resolves [#372](https://github.com/nuxt-community/pwa-module/issues/372)) ([27e19a0](https://github.com/nuxt-community/pwa-module/commit/27e19a04d6f2b14943a0bb4a9b7414382591d4e0))

## [3.2.0](https://github.com/nuxt-community/pwa-module/compare/v3.1.2...v3.2.0) (2020-10-13)


### Bug Fixes

* support build cache ([#371](https://github.com/nuxt-community/pwa-module/issues/371)) ([9a825c9](https://github.com/nuxt-community/pwa-module/commit/9a825c9d47c057c5934030142cb6e46d23a46e21))
* **meta:** fix `mergeMeta` cjs export ([774f1a8](https://github.com/nuxt-community/pwa-module/commit/774f1a87d8c102ad3754374e53a41b434a01b82c))
* **workbox:** restore `sw.js` with smart build (fixes [#352](https://github.com/nuxt-community/pwa-module/issues/352)) ([491f440](https://github.com/nuxt-community/pwa-module/commit/491f440936e107c424864a1aa1121e6995d4e87b))

### [3.1.2](https://github.com/nuxt-community/pwa-module/compare/v3.1.1...v3.1.2) (2020-10-07)


### Bug Fixes

* **meta:** avoid unnecessary log for meta.json ([de8e039](https://github.com/nuxt-community/pwa-module/commit/de8e039740a5618b59312682ecdea4f023d88414))
* **meta:** fix issues regarding favicon.ico fallback ([7a1e773](https://github.com/nuxt-community/pwa-module/commit/7a1e77384eb88f0886180bc784efa242ae59e5ad))

### [3.1.1](https://github.com/nuxt-community/pwa-module/compare/v3.1.0...v3.1.1) (2020-10-07)


### Bug Fixes

* **meta:** load meta when `ssr` is disable and using `nuxt dev` (fixes [#219](https://github.com/nuxt-community/pwa-module/issues/219)) ([b6a5ead](https://github.com/nuxt-community/pwa-module/commit/b6a5ead17cdb8f2edff9d12c326ae59d8ac372be))
* **workbox:** handle `offlinePage` options (fixes [#365](https://github.com/nuxt-community/pwa-module/issues/365)) ([2b9856e](https://github.com/nuxt-community/pwa-module/commit/2b9856e9c226c5f286acb5116cb381e2fc550248))

## [3.1.0](https://github.com/nuxt-community/pwa-module/compare/v3.0.2...v3.1.0) (2020-10-06)


### Features

* **meta:** merge head at runtime ([#363](https://github.com/nuxt-community/pwa-module/issues/363)) ([c0d86ea](https://github.com/nuxt-community/pwa-module/commit/c0d86ead374efcfd66282959e65055262e4a27cf))


### Bug Fixes

* **icon:** fork without original process args ([#343](https://github.com/nuxt-community/pwa-module/issues/343)) ([8b1f19f](https://github.com/nuxt-community/pwa-module/commit/8b1f19f56ddc31a49445334ddc8abe2162b4b760))
* **manifest:** do not use nuxt loading bar color as default `theme_color` ([#344](https://github.com/nuxt-community/pwa-module/issues/344)) ([a18a79f](https://github.com/nuxt-community/pwa-module/commit/a18a79f62a49a3a563621929e30fc8703c3c133a))
* **meta:** add missing `router.base` prefix to favicon ([#354](https://github.com/nuxt-community/pwa-module/issues/354)) ([3e910ae](https://github.com/nuxt-community/pwa-module/commit/3e910ae7e87d341c6a6ea018d013105ce1721b5b))
* **meta:** allow setting `appleStatusBarStyle` without `mobileAppIOS` ([b0f226a](https://github.com/nuxt-community/pwa-module/commit/b0f226aadeee50b47790ac064852b444e33d9b95)), closes [#338](https://github.com/nuxt-community/pwa-module/issues/338)
* **meta:** prevent build failure for ios splash image when no icon is used ([#362](https://github.com/nuxt-community/pwa-module/issues/362)) ([494eed5](https://github.com/nuxt-community/pwa-module/commit/494eed5db00e7cf6863fc854e6ccb6b7bb8c0ba4))
* **workbox:** New configuration for specifying plugins when configuring a strategy ([#337](https://github.com/nuxt-community/pwa-module/issues/337)) ([dacf7ec](https://github.com/nuxt-community/pwa-module/commit/dacf7ec3613a6cb985990eab6c78879b78bdbbbc)), closes [/github.com/nuxt-community/pwa-module/pull/337#issuecomment-681870522](https://github.com/nuxt-community//github.com/nuxt-community/pwa-module/pull/337/issues/issuecomment-681870522)

### [3.0.2](https://github.com/nuxt-community/pwa-module/compare/v3.0.1...v3.0.2) (2020-08-26)


### Bug Fixes

* **workbox:** missing required parameter request for `handle()` ([#335](https://github.com/nuxt-community/pwa-module/issues/335)) ([eedf23f](https://github.com/nuxt-community/pwa-module/commit/eedf23fa3ab478f8a449817528d0270507babfc8))

### [3.0.1](https://github.com/nuxt-community/pwa-module/compare/v3.0.0...v3.0.1) (2020-08-17)


### Bug Fixes

* **icon:** update warning url to docs ([#329](https://github.com/nuxt-community/pwa-module/issues/329)) ([61633fa](https://github.com/nuxt-community/pwa-module/commit/61633fa640793c344748efdf790a56456fad8e2f))

## [3.0.0](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.20...v3.0.0) (2020-08-16)

### ⭐ What's new?

- Using workbox 5
- Support `purpose` option and defaulting to `any maskable`
- Brand new docs powered by [nuxt/content](https://github.com/nuxt/content)

### 🚀 Features

* Update to workbox `5.x`
* Add types ([#323](https://github.com/nuxt-community/pwa-module/issues/323)) ([8723d07](https://github.com/nuxt-community/pwa-module/commit/8723d076cb87ff9e583ba755f72f4d62360d6eb1))
* **icon:** Support for icon purpose ([#246](https://github.com/nuxt-community/pwa-module/issues/246)) ([9248174](https://github.com/nuxt-community/pwa-module/commit/9248174fe8bac352318c8fe292012156ccfd56ad))
* **icon:** Default purpose to `any maskable` ([30f0f63](https://github.com/nuxt-community/pwa-module/commit/30f0f63bcd1601cc6aa5595a851de965dde9af88))
* **icon:** Expose `options.cacheDir` ([f8dbf1d](https://github.com/nuxt-community/pwa-module/commit/f8dbf1dac99519648a53dc22ab4019af25a677aa))
* **icon:** Use `favicon.ico` when available with warning ([#258](https://github.com/nuxt-community/pwa-module/issues/258)) ([7a48d2a](https://github.com/nuxt-community/pwa-module/commit/7a48d2a60b1f2ccaa1287789adb846806afd5224))
* **icon:** Rename `accessibleIcons` to `iconPlugin` ([3e175f9](https://github.com/nuxt-community/pwa-module/commit/3e175f93c046028b6f3f9479085ec98d014b460b))
* **icon** Rename `iconSrc`, `iconFileName`, `iconPlugin` and `iconProperty` to `source`, `fileName`, `plugin` and `pluginName`
* **icon:** Support for iOS splash screens ([#308](https://github.com/nuxt-community/pwa-module/issues/308)) ([f4eeda7](https://github.com/nuxt-community/pwa-module/commit/f4eeda7ce05cdd7dda4e4c4ab81e986f6c94a951))
* **module:** Allow disabling sub-modules with top-level options ([65800f9](https://github.com/nuxt-community/pwa-module/commit/65800f91a671e61d59a9faf885c2ff7ecc9d9ca0))
* **workbox:** Support `enabled` option and self destroying sw ([c64226c](https://github.com/nuxt-community/pwa-module/commit/c64226cea36c1b0b9f0efe7640439e6bb134ddce))
* Support `manifest.fileName` with template ([f05353b](https://github.com/nuxt-community/pwa-module/commit/f05353b7ccfef88f5f95f0fa7b0109c2ece4236b)), closes [#193](https://github.com/nuxt-community/pwa-module/issues/193)
* Use integraty file to invalidate icon cache ([6661a09](https://github.com/nuxt-community/pwa-module/commit/6661a09f86bbc169a99effac3d9cb1620f530b3d))
* **manifest:** Add `useWebmanifestExtension` option and improve docs ([#241](https://github.com/nuxt-community/pwa-module/issues/241)) ([4484e6c](https://github.com/nuxt-community/pwa-module/commit/4484e6c697c5534103969894252f1d356d4016ee))


### 📝 Docs

* Fix a typo on icon (#235)
* Add tip for `pwa.manifest.display: 'browser'` (#249)
* Fix typo in `icon.md` (#253)
* Use `CacheFirst` instead of `cacheFirst` (#251)
* Fix wrong position of a description (#270)
* Add an example for refresh to update implementation (#271)
* Document `workbox.swDest` (#285)
* Add title to external links (#288)
* Migrate to nuxt content (#313)


### 🐛 Bug Fixes

* **icon:** Clean `cacheDir` when generating icons ([1e6eb19](https://github.com/nuxt-community/pwa-module/commit/1e6eb19851bbb6bcb51106cea5611475edec75cc))

### ⚠ BREAKING CHANGES

* Requeires Node 10.x
* Updated to workbox 5.x (optional: [migration guide](https://developers.google.com/web/tools/workbox/guides/migrations/migrate-from-v4))
* Icon options renamed: `iconSrc`, `iconFileName`, `iconPlugin`, `iconProperty`, `accessibleIcons` (see docs)
* Icon purpose is now `any maskable` by default which means you have to consider minimum safe-zone ([read more](https://web.dev/maskable-icon))

###  💖 Contributors

- @alperbicer
- @danbeneventano
- @danielroe
- @daniel-tikken
- @DCsunset
- @debs-obrien
- @dvarnai
- @gangsthub
- @Gomah
- @hans00
- @Hxmic
- @jefrydco
- @jeremy21212121
- @jsulpis
- @ricardogobbosouza
- @s-pace
- @svale
- @Timibadass
- @Wisdom132
- @zachjharris

## [3.0.0-beta.20](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.19...v3.0.0-beta.20) (2020-02-02)

## [3.0.0-beta.19](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.18...v3.0.0-beta.19) (2019-09-11)


### Bug Fixes

* expose modified pwa context to the config ([c325e44](https://github.com/nuxt-community/pwa-module/commit/c325e44))
* truncate manifest hash ([5c74621](https://github.com/nuxt-community/pwa-module/commit/5c74621))

## [3.0.0-beta.18](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.17...v3.0.0-beta.18) (2019-09-09)


### Bug Fixes

* revert compileTemplate as is fixed by nuxt/nuxt.js[#6283](https://github.com/nuxt-community/pwa-module/issues/6283) for 2.9.x ([d0f96de](https://github.com/nuxt-community/pwa-module/commit/d0f96de))
* use shared pwa context ([3c19bae](https://github.com/nuxt-community/pwa-module/commit/3c19bae))

## [3.0.0-beta.17](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.16...v3.0.0-beta.17) (2019-09-05)


### Features

* `pwa.` scopped options ([010fe0e](https://github.com/nuxt-community/pwa-module/commit/010fe0e))
* use `jimp-compact` ([5e37b58](https://github.com/nuxt-community/pwa-module/commit/5e37b58))

# [3.0.0-beta.16](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.15...v3.0.0-beta.16) (2019-05-07)


### Bug Fixes

* **icon:** handle situation where the iconSrc is `null` or `undefined` ([#187](https://github.com/nuxt-community/pwa-module/issues/187)) ([66be874](https://github.com/nuxt-community/pwa-module/commit/66be874))





# [3.0.0-beta.15](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.14...v3.0.0-beta.15) (2019-05-07)


### Bug Fixes

* **workbox:** disable `cacheAssets` for dev mode ([dbf6d67](https://github.com/nuxt-community/pwa-module/commit/dbf6d67))
* **workbox:** use `NetworkFirst `for dev ([9a67580](https://github.com/nuxt-community/pwa-module/commit/9a67580))


### Features

* **workbox:** support `offlineStrategy` ([e377436](https://github.com/nuxt-community/pwa-module/commit/e377436))
* rewrite icon with async image resizer ([#171](https://github.com/nuxt-community/pwa-module/issues/171))


### Reverts

* revert unnecessary HMR regex ([1ac5f5c](https://github.com/nuxt-community/pwa-module/commit/1ac5f5c))


### BREAKING CHANGES

* **workbox:** default `offlineStrategy` changed from `NetworkOnly` to `NetworkFirst` when `offlinePage` is enabled





# [3.0.0-beta.14](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.13...v3.0.0-beta.14) (2019-03-17)


### Bug Fixes

* **onesignal:** ensure no duplicate script is added ([#161](https://github.com/nuxt-community/pwa-module/issues/161)) ([89c1a1d](https://github.com/nuxt-community/pwa-module/commit/89c1a1d))


### Features

* **workbox:** make plugin fully asynchronous ([1eb1190](https://github.com/nuxt-community/pwa-module/commit/1eb1190))
* improve computed cacheId ([cd6c9cc](https://github.com/nuxt-community/pwa-module/commit/cd6c9cc))
* improve sw.register error handling ([9aa76f8](https://github.com/nuxt-community/pwa-module/commit/9aa76f8))





# [3.0.0-beta.13](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.12...v3.0.0-beta.13) (2019-03-17)


### Features

* **workbox:** improve sw.register ([c35f610](https://github.com/nuxt-community/pwa-module/commit/c35f610))
* sync workbox version with workbox-window ([9a3632a](https://github.com/nuxt-community/pwa-module/commit/9a3632a))





# [3.0.0-beta.12](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.11...v3.0.0-beta.12) (2019-03-05)


### Bug Fixes

* **pwa-utils:** don't combine with esm ([fddfa7a](https://github.com/nuxt-community/pwa-module/commit/fddfa7a)), closes [#147](https://github.com/nuxt-community/pwa-module/issues/147)





# [3.0.0-beta.11](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.10...v3.0.0-beta.11) (2019-03-05)


### Bug Fixes

* **workbox:** always prepend routerBase to swURL ([d3a52b6](https://github.com/nuxt-community/pwa-module/commit/d3a52b6)), closes [#157](https://github.com/nuxt-community/pwa-module/issues/157)


### Features

* **workbox:** allow cache names to be configured ([#154](https://github.com/nuxt-community/pwa-module/issues/154)) ([2d7ed53](https://github.com/nuxt-community/pwa-module/commit/2d7ed53))
* **workbox:** workbox-window support ([2e356d0](https://github.com/nuxt-community/pwa-module/commit/2e356d0))





# [3.0.0-beta.10](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.9...v3.0.0-beta.10) (2019-02-27)


### Features

* **workbox:** use workbox 4.0.0-0 ([70813ef](https://github.com/nuxt-community/pwa-module/commit/70813ef))





# [3.0.0-beta.9](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.8...v3.0.0-beta.9) (2019-02-27)


### Bug Fixes

* **pwa-utils:** handle non-strings in `startCase` ([#150](https://github.com/nuxt-community/pwa-module/issues/150)) ([782217a](https://github.com/nuxt-community/pwa-module/commit/782217a))





# [3.0.0-beta.8](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.7...v3.0.0-beta.8) (2019-02-18)


### Bug Fixes

* **manifest:** remove publicPath field ([b03dc14](https://github.com/nuxt-community/pwa-module/commit/b03dc14))





# [3.0.0-beta.7](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.6...v3.0.0-beta.7) (2019-02-17)


### Bug Fixes

* **module:** handle readJSFiles for string param ([#143](https://github.com/nuxt-community/pwa-module/issues/143)) ([4f06479](https://github.com/nuxt-community/pwa-module/commit/4f06479))


### Features

* **workbox:** bump to 4.0.0-rc.2 ([7e278f0](https://github.com/nuxt-community/pwa-module/commit/7e278f0))





# [3.0.0-beta.6](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.5...v3.0.0-beta.6) (2019-02-08)


### Bug Fixes

* relax pages regex for workbox 4 compatiblity ([04e74a7](https://github.com/nuxt-community/pwa-module/commit/04e74a7))


### Features

* cleanupOutdatedCaches ([9167013](https://github.com/nuxt-community/pwa-module/commit/9167013))
* **workbox:** assetsURLPattern, pagesURLPattern ([5fc3d66](https://github.com/nuxt-community/pwa-module/commit/5fc3d66))
* **workbox:** preCaching option ([67f1c3d](https://github.com/nuxt-community/pwa-module/commit/67f1c3d))
* **workbox:** upgrade workboxVersion to 4.0.0-rc.0 ([b364572](https://github.com/nuxt-community/pwa-module/commit/b364572))





# [3.0.0-beta.5](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.3...v3.0.0-beta.5) (2019-02-08)


### Bug Fixes

* add workboxExtensions to defaults ([#138](https://github.com/nuxt-community/pwa-module/issues/138)) ([ac8ba74](https://github.com/nuxt-community/pwa-module/commit/ac8ba74))





# [3.0.0-beta.3](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.2...v3.0.0-beta.3) (2019-02-07)


### Bug Fixes

* **onesignal:** add cache query to sw.js ([33f8f61](https://github.com/nuxt-community/pwa-module/commit/33f8f61))
* **pwa-utils:** ensure joinUrl not modifying scheme part ([09a465a](https://github.com/nuxt-community/pwa-module/commit/09a465a))


### Features

* options.dev ([fb0d38c](https://github.com/nuxt-community/pwa-module/commit/fb0d38c))





# [3.0.0-beta.2](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.1...v3.0.0-beta.2) (2019-02-07)


### Features

* offlineAnalytics ([#55](https://github.com/nuxt-community/pwa-module/issues/55)) ([4c4d3ff](https://github.com/nuxt-community/pwa-module/commit/4c4d3ff))
* workboxExtensions and extension reading fixes ([5c56484](https://github.com/nuxt-community/pwa-module/commit/5c56484))





# [3.0.0-beta.1](https://github.com/nuxt-community/pwa-module/compare/v3.0.0-beta.0...v3.0.0-beta.1) (2019-02-07)


### Features

* **icon:** allow reading icon from assetc/icon.png ([#29](https://github.com/nuxt-community/pwa-module/issues/29)) ([9e0fde3](https://github.com/nuxt-community/pwa-module/commit/9e0fde3))
* add HMR test suit ([ff3d502](https://github.com/nuxt-community/pwa-module/commit/ff3d502))
* use better regexes ([318228e](https://github.com/nuxt-community/pwa-module/commit/318228e))





# [3.0.0-beta.0](https://github.com/nuxt-community/pwa-module/compare/v2.6.0...v3.0.0-beta.0) (2019-02-04)


### Bug Fixes

* Handle `ogImage` as url ([#121](https://github.com/nuxt-community/pwa-module/issues/121)) ([d6dc82b](https://github.com/nuxt-community/pwa-module/commit/d6dc82b))
* Routing order for default offline route `/.*` must be last ([#100](https://github.com/nuxt-community/pwa-module/issues/100)) ([1c829d0](https://github.com/nuxt-community/pwa-module/commit/1c829d0))


### Code Refactoring

* Use tapable hooks ([#103](https://github.com/nuxt-community/pwa-module/issues/103)) ([9f27d5c](https://github.com/nuxt-community/pwa-module/commit/9f27d5c))
* Remove debug ([92ba73e](https://github.com/nuxt-community/pwa-module/commit/92ba73e))

### Features

* **onesignal:** Use CDN by default ([7c78c67](https://github.com/nuxt-community/pwa-module/commit/7c78c67))
* **workbox:** Rewrite workbox ([#122](https://github.com/nuxt-community/pwa-module/issues/122)) ([9e49896](https://github.com/nuxt-community/pwa-module/commit/9e49896))
* **icon:** new options ([#126](https://github.com/nuxt-community/pwa-module/issues/126)) ([12e6576](https://github.com/nuxt-community/pwa-module/commit/12e6576))
* **workbox:** change the order of default `runtimeCache` ([#106](https://github.com/nuxt-community/pwa-module/issues/106)) ([033b504](https://github.com/nuxt-community/pwa-module/commit/033b504))


### BREAKING CHANGES

* Only nuxt 2+ supported ([854d826](https://github.com/nuxt-community/pwa-module/commit/854d826))
* webpack >= 4 is required


<a name="2.6.0"></a>
# [2.6.0](https://github.com/nuxt-community/pwa-module/compare/v2.5.0...v2.6.0) (2018-09-21)


### Bug Fixes

* **workbox:** add missing lodash dependency ([#91](https://github.com/nuxt-community/pwa-module/issues/91)) ([da2c36f](https://github.com/nuxt-community/pwa-module/commit/da2c36f))


### Features

* **icon:** update to jimp 0.5.0 ([b071c4b](https://github.com/nuxt-community/pwa-module/commit/b071c4b))
* **workbox:** support pass config object to `workbox.setConfig` ([#95](https://github.com/nuxt-community/pwa-module/issues/95)) ([b5dab8a](https://github.com/nuxt-community/pwa-module/commit/b5dab8a))





<a name="2.5.0"></a>
# [2.5.0](https://github.com/nuxt-community/pwa-module/compare/v2.4.0...v2.5.0) (2018-09-02)


### Features

* **icon:** make icons accessible ([#51](https://github.com/nuxt-community/pwa-module/issues/51)) ([92bccd3](https://github.com/nuxt-community/pwa-module/commit/92bccd3))





<a name="2.4.0"></a>
# [2.4.0](https://github.com/nuxt-community/pwa-module/compare/v2.3.2...v2.4.0) (2018-08-28)


### Bug Fixes

* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/nuxt-community/pwa-module/issues/84)) ([3f0e718](https://github.com/nuxt-community/pwa-module/commit/3f0e718))
* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/nuxt-community/pwa-module/issues/83). ([c7102fd](https://github.com/nuxt-community/pwa-module/commit/c7102fd))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/nuxt-community/pwa-module/issues/83). ([7a8bb3b](https://github.com/nuxt-community/pwa-module/commit/7a8bb3b))


### Features

* **worbox:** offlineAssets ([#86](https://github.com/nuxt-community/pwa-module/issues/86)) ([27c8fa1](https://github.com/nuxt-community/pwa-module/commit/27c8fa1))
* **workbox:** offline page assets ([#85](https://github.com/nuxt-community/pwa-module/issues/85)) ([8bc4a3b](https://github.com/nuxt-community/pwa-module/commit/8bc4a3b))





<a name="2.3.2"></a>
# 2.3.2 (2018-08-24)

### Bug Fixes

* **workbox:** `staleWhileRevalidate()` -> `networkOnly()` for offline pages ([832d60f](https://github.com/nuxt-community/pwa-module/commit/832d60f))


<a name="2.3.1"></a>
# 2.3.1 (2018-08-24)

### Bug Fixes

* **workbox:** `offlinePage` syntax error ([af21d74](https://github.com/nuxt-community/pwa-module/commit/af21d74))

<a name="2.3.0"></a>
# 2.3.0 (2018-08-24)

### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa/commit/49b7c49))
* **icon:** await on build ([e3c1be2](https://github.com/nuxt-community/pwa/commit/e3c1be2))
* **icon:** generate only on build ([9d68d70](https://github.com/nuxt-community/pwa/commit/9d68d70))
* **manifest:** run only on build ([ecaa835](https://github.com/nuxt-community/pwa/commit/ecaa835))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/nuxt-community/pwa/issues/23)) ([76a1f89](https://github.com/nuxt-community/pwa/commit/76a1f89))
* **meta:** generate only on build ([1cace26](https://github.com/nuxt-community/pwa/commit/1cace26))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/nuxt-community/pwa/issues/44)) ([354f818](https://github.com/nuxt-community/pwa/commit/354f818))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/nuxt-community/pwa/commit/cf48b3f)), closes [#10](https://github.com/nuxt-community/pwa/issues/10)
* **pwa:** no more optimize dependency ([a1c149f](https://github.com/nuxt-community/pwa/commit/a1c149f))
* **workbox:** faster service worker register ([07524a2](https://github.com/nuxt-community/pwa/commit/07524a2))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/nuxt-community/pwa/issues/73)) ([6d241ec](https://github.com/nuxt-community/pwa/commit/6d241ec))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/nuxt-community/pwa/commit/b744a27))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/nuxt-community/pwa/issues/14). ([f384103](https://github.com/nuxt-community/pwa/commit/f384103))
* don't override title when titleTemplate is provided  ([#48](https://github.com/nuxt-community/pwa/issues/48)) ([8c3f319](https://github.com/nuxt-community/pwa/commit/8c3f319))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa/commit/a0fb908))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa/commit/c0efb1d))
* add og:image support ([#30](https://github.com/nuxt-community/pwa/issues/30)) ([afebd96](https://github.com/nuxt-community/pwa/commit/afebd96))
* add oneSignal module ([bbc7b72](https://github.com/nuxt-community/pwa/commit/bbc7b72))
* **manifest:** allow overriding publicPath ([#19](https://github.com/nuxt-community/pwa/issues/19)) ([4e6782e](https://github.com/nuxt-community/pwa/commit/4e6782e))
* add option to register third-party sw ([#12](https://github.com/nuxt-community/pwa/issues/12)) ([9c0b61e](https://github.com/nuxt-community/pwa/commit/9c0b61e))
* **icon:** add combined option sources ([539430f](https://github.com/nuxt-community/pwa/commit/539430f))
* **manifest:** support crossorigin option ([#71](https://github.com/nuxt-community/pwa/issues/71)) ([ccb2c33](https://github.com/nuxt-community/pwa/commit/ccb2c33))
* **meta:** add author property ([#41](https://github.com/nuxt-community/pwa/issues/41)) ([cafcfc4](https://github.com/nuxt-community/pwa/commit/cafcfc4))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/nuxt-community/pwa/commit/3c7aa7d)), closes [#10](https://github.com/nuxt-community/pwa/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/nuxt-community/pwa/issues/42)) ([3990ddf](https://github.com/nuxt-community/pwa/commit/3990ddf))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/nuxt-community/pwa/commit/dc39fcb))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/nuxt-community/pwa/issues/43)) ([fe11c76](https://github.com/nuxt-community/pwa/commit/fe11c76))
* **onesignal:** move init options under init ([dd61c18](https://github.com/nuxt-community/pwa/commit/dd61c18))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/nuxt-community/pwa/commit/fdcda0f))
* **worbox:** add offline option for making it optional ([#59](https://github.com/nuxt-community/pwa/issues/59)) ([76de33c](https://github.com/nuxt-community/pwa/commit/76de33c)), closes [#24](https://github.com/nuxt-community/pwa/issues/24)
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/nuxt-community/pwa/commit/f1e1fe1))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/nuxt-community/pwa/commit/e7677d8))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/nuxt-community/pwa/commit/a5ddf59))
* **workbox:** importScripts option ([7c8644c](https://github.com/nuxt-community/pwa/commit/7c8644c))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/nuxt-community/pwa/issues/80)) ([88cc602](https://github.com/nuxt-community/pwa/commit/88cc602))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/nuxt-community/pwa/commit/b0af84e))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/nuxt-community/pwa/issues/60)) ([0fef874](https://github.com/nuxt-community/pwa/commit/0fef874))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/nuxt-community/pwa/commit/5ac89cf))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/nuxt-community/pwa/commit/b17bbd0))
* ogSiteName ([#50](https://github.com/nuxt-community/pwa/issues/50)) ([0c99ab9](https://github.com/nuxt-community/pwa/commit/0c99ab9))

# Older changelogs

## Icon

<a name="2.5.0"></a>
# [2.5.0](https://github.com/nuxt-community/pwa-module/compare/v2.4.0...v2.5.0) (2018-09-02)


### Features

* **icon:** make icons accessible ([#51](https://github.com/nuxt-community/pwa-module/issues/51)) ([92bccd3](https://github.com/nuxt-community/pwa-module/commit/92bccd3))





<a name="2.4.0"></a>
# [2.4.0](https://github.com/nuxt-community/pwa-module/compare/v2.3.2...v2.4.0) (2018-08-28)


### Bug Fixes

* **icon:** temporary use jimp@0.3.4 ([#84](https://github.com/nuxt-community/pwa-module/issues/84)) ([3f0e718](https://github.com/nuxt-community/pwa-module/commit/3f0e718))





<a name="2.3.0"></a>
# 2.3.0 (2018-08-24)


### Bug Fixes

* **icon:** await on build ([e3c1be2](https://github.com/nuxt-community/pwa-module/commit/e3c1be2))
* **icon:** generate only on build ([9d68d70](https://github.com/nuxt-community/pwa-module/commit/9d68d70))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa-module/commit/a0fb908))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))
* **icon:** add combined option sources ([539430f](https://github.com/nuxt-community/pwa-module/commit/539430f))





<a name="2.1.0"></a>
# [2.1.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/icon@2.0.2...@nuxtjs/icon@2.1.0) (2018-03-05)


### Features

* **icon:** add combined option sources ([539430f](https://github.com/nuxt-community/pwa-module/commit/539430f))





<a name="2.0.2"></a>
## [2.0.2](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/icon@2.0.1...@nuxtjs/icon@2.0.2) (2017-12-29)




**Note:** Version bump only for package @nuxtjs/icon

<a name="2.0.1"></a>
## [2.0.1](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/icon@2.0.0...@nuxtjs/icon@2.0.1) (2017-11-17)


### Bug Fixes

* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa-module/commit/a0fb908))




<a name="2.0.0"></a>
# [2.0.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/icon@1.1.2...@nuxtjs/icon@2.0.0) (2017-11-16)


### Bug Fixes

* **icon:** await on build ([e3c1be2](https://github.com/nuxt-community/pwa-module/commit/e3c1be2))
* **icon:** generate only on build ([9d68d70](https://github.com/nuxt-community/pwa-module/commit/9d68d70))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))




<a name="1.1.2"></a>
## 1.1.2 (2017-10-04)




**Note:** Version bump only for package @nuxtjs/icon

<a name="1.1.1"></a>
## 1.1.1 (2017-10-04)




**Note:** Version bump only for package @nuxtjs/icon

<a name="1.1.0"></a>
# [1.1.0](https://github.com/nuxt/modules/compare/@nuxtjs/icon@1.0.1...@nuxtjs/icon@1.1.0) (2017-09-21)


### Features

* **icon:** set minimum size to 64 ([5bd9460](https://github.com/nuxt/modules/commit/5bd9460))




<a name="1.0.1"></a>
## [1.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/icon@1.0.0...@nuxtjs/icon@1.0.1) (2017-08-02)




<a name="0.1.0"></a>
# 0.1.0 (2017-06-06)


### Bug Fixes

* **icon:** fix iconSrc type ([9aaaba7](https://github.com/nuxt/modules/commit/9aaaba7))


### Features

* 🖼️ icon module ([6201d2a](https://github.com/nuxt/modules/commit/6201d2a))

## Manifest

<a name="2.4.0"></a>
# [2.4.0](https://github.com/nuxt-community/pwa-module/compare/v2.3.2...v2.4.0) (2018-08-28)

**Note:** Version bump only for package @nuxtjs/manifest





<a name="2.3.0"></a>
# 2.3.0 (2018-08-24)


### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa-module/commit/49b7c49))
* **manifest:** run only on build ([ecaa835](https://github.com/nuxt-community/pwa-module/commit/ecaa835))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa-module/commit/a0fb908))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))
* **manifest:** allow overriding publicPath ([#19](https://github.com/nuxt-community/pwa-module/issues/19)) ([4e6782e](https://github.com/nuxt-community/pwa-module/commit/4e6782e))
* **manifest:** support crossorigin option ([#71](https://github.com/nuxt-community/pwa-module/issues/71)) ([ccb2c33](https://github.com/nuxt-community/pwa-module/commit/ccb2c33))





<a name="2.1.0"></a>
# [2.1.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/manifest@2.0.1...@nuxtjs/manifest@2.1.0) (2017-12-07)


### Features

* **manifest:** allow overriding publicPath ([#19](https://github.com/nuxt-community/pwa-module/issues/19)) ([4e6782e](https://github.com/nuxt-community/pwa-module/commit/4e6782e))




<a name="2.0.1"></a>
## [2.0.1](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/manifest@2.0.0...@nuxtjs/manifest@2.0.1) (2017-11-17)


### Bug Fixes

* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa-module/commit/a0fb908))




<a name="2.0.0"></a>
# [2.0.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/manifest@1.7.2...@nuxtjs/manifest@2.0.0) (2017-11-16)


### Bug Fixes

* **manifest:** run only on build ([ecaa835](https://github.com/nuxt-community/pwa-module/commit/ecaa835))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))




<a name="1.7.2"></a>
## 1.7.2 (2017-10-04)


### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa/commit/49b7c49))




<a name="1.7.1"></a>
## 1.7.1 (2017-10-04)




**Note:** Version bump only for package @nuxtjs/manifest

<a name="1.7.0"></a>
# [1.7.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.6.1...@nuxtjs/manifest@1.7.0) (2017-09-22)


### Features

* **manifest:** add standalone to start_url ([81dbe9c](https://github.com/nuxt/modules/commit/81dbe9c))




<a name="1.6.0"></a>
# [1.6.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.5.0...@nuxtjs/manifest@1.6.0) (2017-06-06)


### Bug Fixes

* **manifest:** correctly omit internal options ([47559b0](https://github.com/nuxt/modules/commit/47559b0))


### Features

* **manifest:** meta module compatibility ([8a41fda](https://github.com/nuxt/modules/commit/8a41fda))
* **manifest:** refactor & openGraph support ([0768246](https://github.com/nuxt/modules/commit/0768246))
* **manifest:** rewrite module ([352b4bf](https://github.com/nuxt/modules/commit/352b4bf))




<a name="1.5.0"></a>
# [1.5.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.4.2...@nuxtjs/manifest@1.5.0) (2017-06-05)


### Features

* **manifest:** defaultIcon option ([1086962](https://github.com/nuxt/modules/commit/1086962))




<a name="1.4.2"></a>
## [1.4.2](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.4.1...@nuxtjs/manifest@1.4.2) (2017-06-04)


### Bug Fixes

* prevent invalid url when router base is / ([f0fd863](https://github.com/nuxt/modules/commit/f0fd863))




<a name="1.4.1"></a>
## [1.4.1](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.4.0...@nuxtjs/manifest@1.4.1) (2017-06-04)


### Bug Fixes

* **manifest:** sanetize options ([b8497a0](https://github.com/nuxt/modules/commit/b8497a0))
* **manifest:** typo in manifest.json filename ([c2cabb6](https://github.com/nuxt/modules/commit/c2cabb6))




<a name="1.4.0"></a>
# [1.4.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.3.1...@nuxtjs/manifest@1.4.0) (2017-06-04)


### Features

* **manifest:** improvements ([cac9b4e](https://github.com/nuxt/modules/commit/cac9b4e))




<a name="1.3.1"></a>
## [1.3.1](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.3.0...@nuxtjs/manifest@1.3.1) (2017-06-02)


### Bug Fixes

* **manifest:** write manifest file once ([18aa015](https://github.com/nuxt/modules/commit/18aa015))




<a name="1.3.0"></a>
# [1.3.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.2.0...@nuxtjs/manifest@1.3.0) (2017-06-02)


### Features

* **manifest:** add lang ([bfdb96e](https://github.com/nuxt/modules/commit/bfdb96e))
* **manifest:** improve default short_name ([45b2bb2](https://github.com/nuxt/modules/commit/45b2bb2))




<a name="1.2.0"></a>
# [1.2.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.1.1...@nuxtjs/manifest@1.2.0) (2017-06-02)


### Features

* **meta:** add apple-touch-icon ([c74ffa4](https://github.com/nuxt/modules/commit/c74ffa4))




<a name="1.1.1"></a>
## [1.1.1](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.1.0...@nuxtjs/manifest@1.1.1) (2017-05-31)




<a name="1.1.0"></a>
# [1.1.0](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.0.1...@nuxtjs/manifest@1.1.0) (2017-05-30)


### Features

* **manifest:** Use loading as theme color as default ([cae4329](https://github.com/nuxt/modules/commit/cae4329))




<a name="1.0.1"></a>
## [1.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/manifest@1.0.0...@nuxtjs/manifest@1.0.1) (2017-05-29)




<a name="1.0.0"></a>
# 1.0.0 (2017-05-26)


### Features

* initial migration to 1.0.0-alpha1 ([05c1b7a](https://github.com/nuxt/modules/commit/05c1b7a))


### BREAKING CHANGES

* New modules system is backward incompatible with nuxt-helpers style modules




<a name="0.0.1"></a>
## 0.0.1 (2017-05-10)


## Meta

<a name="2.4.0"></a>
# [2.4.0](https://github.com/nuxt-community/pwa-module/compare/v2.3.2...v2.4.0) (2018-08-28)

**Note:** Version bump only for package @nuxtjs/meta





<a name="2.3.0"></a>
# 2.3.0 (2018-08-24)


### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa-module/commit/49b7c49))
* **meta:** add unique identifiers to meta fields ([#23](https://github.com/nuxt-community/pwa-module/issues/23)) ([76a1f89](https://github.com/nuxt-community/pwa-module/commit/76a1f89))
* **meta:** generate only on build ([1cace26](https://github.com/nuxt-community/pwa-module/commit/1cace26))
* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/nuxt-community/pwa-module/issues/44)) ([354f818](https://github.com/nuxt-community/pwa-module/commit/354f818))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/nuxt-community/pwa-module/commit/cf48b3f)), closes [#10](https://github.com/nuxt-community/pwa-module/issues/10)
* don't override title when titleTemplate is provided  ([#48](https://github.com/nuxt-community/pwa-module/issues/48)) ([8c3f319](https://github.com/nuxt-community/pwa-module/commit/8c3f319))
* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa-module/commit/a0fb908))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))
* add og:image support ([#30](https://github.com/nuxt-community/pwa-module/issues/30)) ([afebd96](https://github.com/nuxt-community/pwa-module/commit/afebd96))
* **meta:** add author property ([#41](https://github.com/nuxt-community/pwa-module/issues/41)) ([cafcfc4](https://github.com/nuxt-community/pwa-module/commit/cafcfc4))
* **meta:** add nativeUI option ([3c7aa7d](https://github.com/nuxt-community/pwa-module/commit/3c7aa7d)), closes [#10](https://github.com/nuxt-community/pwa-module/issues/10)
* **meta:** add ogUrl url property ([#42](https://github.com/nuxt-community/pwa-module/issues/42)) ([3990ddf](https://github.com/nuxt-community/pwa-module/commit/3990ddf))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/nuxt-community/pwa-module/commit/dc39fcb))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/nuxt-community/pwa-module/issues/43)) ([fe11c76](https://github.com/nuxt-community/pwa-module/commit/fe11c76))
* ogSiteName ([#50](https://github.com/nuxt-community/pwa-module/issues/50)) ([0c99ab9](https://github.com/nuxt-community/pwa-module/commit/0c99ab9))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/nuxt-community/pwa-module/issues/60)) ([0fef874](https://github.com/nuxt-community/pwa-module/commit/0fef874))





<a name="2.2.1"></a>
## [2.2.1](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/meta@2.2.0...@nuxtjs/meta@2.2.1) (2018-03-08)


### Bug Fixes

* **meta:** only set og:url when it has been defined through ogHost or options ([#44](https://github.com/nuxt-community/pwa-module/issues/44)) ([354f818](https://github.com/nuxt-community/pwa-module/commit/354f818))





<a name="2.2.0"></a>
# [2.2.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/meta@2.1.0...@nuxtjs/meta@2.2.0) (2018-03-08)


### Features

* **meta:** add author property ([#41](https://github.com/nuxt-community/pwa-module/issues/41)) ([cafcfc4](https://github.com/nuxt-community/pwa-module/commit/cafcfc4))
* **meta:** add ogUrl url property ([#42](https://github.com/nuxt-community/pwa-module/issues/42)) ([3990ddf](https://github.com/nuxt-community/pwa-module/commit/3990ddf))
* **meta:** add twitter card, site and creator properties ([#43](https://github.com/nuxt-community/pwa-module/issues/43)) ([fe11c76](https://github.com/nuxt-community/pwa-module/commit/fe11c76))





<a name="2.1.0"></a>
# [2.1.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/meta@2.0.2...@nuxtjs/meta@2.1.0) (2018-03-05)


### Features

* add og:image support ([#30](https://github.com/nuxt-community/pwa-module/issues/30)) ([afebd96](https://github.com/nuxt-community/pwa-module/commit/afebd96))





<a name="2.0.2"></a>
## [2.0.2](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/meta@2.0.1...@nuxtjs/meta@2.0.2) (2017-12-29)


### Bug Fixes

* **meta:** add unique identifiers to meta fields ([#23](https://github.com/nuxt-community/pwa-module/issues/23)) ([76a1f89](https://github.com/nuxt-community/pwa-module/commit/76a1f89))




<a name="2.0.1"></a>
## [2.0.1](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/meta@2.0.0...@nuxtjs/meta@2.0.1) (2017-11-17)


### Bug Fixes

* workaround to fill meta with SPA and nuxt start ([a0fb908](https://github.com/nuxt-community/pwa-module/commit/a0fb908))




<a name="2.0.0"></a>
# [2.0.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/meta@1.5.3...@nuxtjs/meta@2.0.0) (2017-11-16)


### Bug Fixes

* **meta:** generate only on build ([1cace26](https://github.com/nuxt-community/pwa-module/commit/1cace26))
* **meta:** remove minimal-ui from default viewport ([cf48b3f](https://github.com/nuxt-community/pwa-module/commit/cf48b3f))


### Features

* **meta:** add nativeUI option ([3c7aa7d](https://github.com/nuxt-community/pwa-module/commit/3c7aa7d))
* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))
* **meta:** add property attribiture for og tags ([dc39fcb](https://github.com/nuxt-community/pwa-module/commit/dc39fcb))




<a name="1.5.3"></a>
## 1.5.3 (2017-10-04)


### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa/commit/49b7c49))




<a name="1.5.2"></a>
## 1.5.2 (2017-10-04)




**Note:** Version bump only for package @nuxtjs/meta

<a name="1.5.1"></a>
## [1.5.1](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.5.0...@nuxtjs/meta@1.5.1) (2017-09-22)


### Bug Fixes

* **meta:** default apple-mobile-web-app-status-bar-style to default ([2535e08](https://github.com/nuxt/modules/commit/2535e08))




<a name="1.5.0"></a>
# [1.5.0](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.4.0...@nuxtjs/meta@1.5.0) (2017-09-21)


### Bug Fixes

* **meta:** default appleStatusBarStyle to black ([756d5cb](https://github.com/nuxt/modules/commit/756d5cb))


### Features

* **meta:** apple-touch-startup-image ([b98106c](https://github.com/nuxt/modules/commit/b98106c))
* **meta:** better IOS icons ([d76db2d](https://github.com/nuxt/modules/commit/d76db2d))
* **meta:** ios launch icon title ([e94e011](https://github.com/nuxt/modules/commit/e94e011))




<a name="1.4.0"></a>
# [1.4.0](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.3.0...@nuxtjs/meta@1.4.0) (2017-09-21)


### Features

* **meta:** ios specific options ([54a1435](https://github.com/nuxt/modules/commit/54a1435))




<a name="1.3.0"></a>
# [1.3.0](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.2.1...@nuxtjs/meta@1.3.0) (2017-07-20)


### Features

* **icon:** applefavicon option (#76) ([280b416](https://github.com/nuxt/modules/commit/280b416))




<a name="1.2.0"></a>
# [1.2.0](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.1.0...@nuxtjs/meta@1.2.0) (2017-06-06)


### Features

* **meta:** Support manifest meta & openGraph ([17b7db1](https://github.com/nuxt/modules/commit/17b7db1))




<a name="1.1.0"></a>
# [1.1.0](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.0.1...@nuxtjs/meta@1.1.0) (2017-06-02)


### Features

* **meta:** more meta tags ([a4e3a04](https://github.com/nuxt/modules/commit/a4e3a04))




<a name="1.0.1"></a>
## [1.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/meta@1.0.0...@nuxtjs/meta@1.0.1) (2017-05-29)


### Bug Fixes

* **meta:** add missing head keyword ([758cccd](https://github.com/nuxt/modules/commit/758cccd))
* **meta:** fix package.json ([4e395cf](https://github.com/nuxt/modules/commit/4e395cf))




<a name="1.0.0"></a>
# 1.0.0 (2017-05-26)


### Features

* initial migration to 1.0.0-alpha1 ([05c1b7a](https://github.com/nuxt/modules/commit/05c1b7a))


### BREAKING CHANGES

* New modules system is backward incompatible with nuxt-helpers style modules




<a name="0.0.1"></a>
## 0.0.1 (2017-05-10)

## One signal

<a name="2.4.0"></a>
# [2.4.0](https://github.com/nuxt-community/pwa-module/compare/v2.3.2...v2.4.0) (2018-08-28)

**Note:** Version bump only for package @nuxtjs/onesignal





<a name="2.0.0"></a>
# 2.0.0 (2017-11-17)


### Features

* add oneSignal module ([bbc7b72](https://github.com/nuxt-community/pwa-module/commit/bbc7b72))
* **onesignal:** move init options under init ([dd61c18](https://github.com/nuxt-community/pwa-module/commit/dd61c18))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/nuxt-community/pwa-module/commit/5ac89cf))

## Workbox

<a name="2.4.0"></a>
# [2.4.0](https://github.com/nuxt-community/pwa-module/compare/v2.3.2...v2.4.0) (2018-08-28)


### Bug Fixes

* **workbox:** infer default value of globDirectory from webpack config. fixes [#83](https://github.com/nuxt-community/pwa-module/issues/83). ([c7102fd](https://github.com/nuxt-community/pwa-module/commit/c7102fd))
* **workbox:** more fixes regarding nuxt 2 dist directory changes. fixes [#83](https://github.com/nuxt-community/pwa-module/issues/83). ([7a8bb3b](https://github.com/nuxt-community/pwa-module/commit/7a8bb3b))


### Features

* **worbox:** offlineAssets ([#86](https://github.com/nuxt-community/pwa-module/issues/86)) ([27c8fa1](https://github.com/nuxt-community/pwa-module/commit/27c8fa1))
* **workbox:** offline page assets ([#85](https://github.com/nuxt-community/pwa-module/issues/85)) ([8bc4a3b](https://github.com/nuxt-community/pwa-module/commit/8bc4a3b))





<a name="2.3.2"></a>
# 2.3.2 (2018-08-24)

### Bug Fixes

* **workbox:** `staleWhileRevalidate()` -> `networkOnly()` for offline pages ([832d60f](https://github.com/nuxt-community/pwa-module/commit/832d60f))


<a name="2.3.1"></a>
# 2.3.1 (2018-08-24)

### Bug Fixes

* **workbox:** `offlinePage` syntax error ([af21d74](https://github.com/nuxt-community/pwa-module/commit/af21d74))


<a name="2.3.0"></a>
# 2.3.0 (2018-08-24)


### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa-module/commit/49b7c49))
* **workbox:** faster service worker register ([07524a2](https://github.com/nuxt-community/pwa-module/commit/07524a2))
* **workbox:** hardcoded `static` dir ([#73](https://github.com/nuxt-community/pwa-module/issues/73)) ([6d241ec](https://github.com/nuxt-community/pwa-module/commit/6d241ec))
* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/nuxt-community/pwa-module/commit/b744a27))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/nuxt-community/pwa-module/issues/14). ([f384103](https://github.com/nuxt-community/pwa-module/commit/f384103))


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/nuxt-community/pwa-module/commit/5ac89cf))
* add option to register third-party sw ([#12](https://github.com/nuxt-community/pwa-module/issues/12)) ([9c0b61e](https://github.com/nuxt-community/pwa-module/commit/9c0b61e))
* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/nuxt-community/pwa-module/commit/fdcda0f))
* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/nuxt-community/pwa-module/commit/b17bbd0))
* **worbox:** add offline option for making it optional ([#59](https://github.com/nuxt-community/pwa-module/issues/59)) ([76de33c](https://github.com/nuxt-community/pwa-module/commit/76de33c)), closes [#24](https://github.com/nuxt-community/pwa-module/issues/24)
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/nuxt-community/pwa-module/commit/f1e1fe1))
* **workbox:** disable caching for sw.js by default ([e7677d8](https://github.com/nuxt-community/pwa-module/commit/e7677d8))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/nuxt-community/pwa-module/commit/a5ddf59))
* **workbox:** importScripts option ([7c8644c](https://github.com/nuxt-community/pwa-module/commit/7c8644c))
* **workbox:** option to enable `skipWaiting` ([#80](https://github.com/nuxt-community/pwa-module/issues/80)) ([88cc602](https://github.com/nuxt-community/pwa-module/commit/88cc602))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/nuxt-community/pwa-module/commit/b0af84e))
* **workbox:** workbox 3 + offlinePage ([#60](https://github.com/nuxt-community/pwa-module/issues/60)) ([0fef874](https://github.com/nuxt-community/pwa-module/commit/0fef874))





<a name="2.2.0"></a>
# [2.2.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/workbox@2.1.1...@nuxtjs/workbox@2.2.0) (2018-03-05)


### Features

* Add support of StrategyOptions to cache ([b17bbd0](https://github.com/nuxt-community/pwa-module/commit/b17bbd0))





<a name="2.1.1"></a>
## [2.1.1](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/workbox@2.1.0...@nuxtjs/workbox@2.1.1) (2017-11-27)




**Note:** Version bump only for package @nuxtjs/workbox

<a name="2.1.0"></a>
# [2.1.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/workbox@2.0.1...@nuxtjs/workbox@2.1.0) (2017-11-17)


### Bug Fixes

* **workbox:** faster service worker register ([07524a2](https://github.com/nuxt-community/pwa-module/commit/07524a2))


### Features

* **runtimeCaching:** Support runtimeCaching ([fdcda0f](https://github.com/nuxt-community/pwa-module/commit/fdcda0f))
* **workbox:** add options.autoRegister ([f1e1fe1](https://github.com/nuxt-community/pwa-module/commit/f1e1fe1))
* **workbox, onegisnal:** Use defaultsDeep for options ([5ac89cf](https://github.com/nuxt-community/pwa-module/commit/5ac89cf))




<a name="2.0.1"></a>
## [2.0.1](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/workbox@2.0.0...@nuxtjs/workbox@2.0.1) (2017-11-17)


### Bug Fixes

* **workbox:** make cacheId independent of npm package version ([b744a27](https://github.com/nuxt-community/pwa-module/commit/b744a27))
* **workbox:** use regexp for runtimeCaching. fixes [#14](https://github.com/nuxt-community/pwa-module/issues/14). ([f384103](https://github.com/nuxt-community/pwa-module/commit/f384103))




<a name="2.0.0"></a>
# [2.0.0](https://github.com/nuxt-community/pwa-module/compare/@nuxtjs/workbox@1.2.2...@nuxtjs/workbox@2.0.0) (2017-11-16)


### Features

* Add compatibility for nuxt 1.0.0 hooks ([c0efb1d](https://github.com/nuxt-community/pwa-module/commit/c0efb1d))
* add option to register third-party sw ([#12](https://github.com/nuxt-community/pwa-module/issues/12)) ([9c0b61e](https://github.com/nuxt-community/pwa-module/commit/9c0b61e))
* **workbox:** expose registration as window.$sw ([a5ddf59](https://github.com/nuxt-community/pwa-module/commit/a5ddf59))
* **workbox:** importScripts option ([7c8644c](https://github.com/nuxt-community/pwa-module/commit/7c8644c))
* **workbox:** rewrite with better template support ([b0af84e](https://github.com/nuxt-community/pwa-module/commit/b0af84e))




<a name="1.2.2"></a>
## 1.2.2 (2017-10-04)


### Bug Fixes

* **docs:** add reference to pwa module ([49b7c49](https://github.com/nuxt-community/pwa/commit/49b7c49))




<a name="1.2.1"></a>
## 1.2.1 (2017-10-04)




**Note:** Version bump only for package @nuxtjs/workbox

<a name="1.2.0"></a>
# [1.2.0](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.6...@nuxtjs/workbox@1.2.0) (2017-08-16)


### Features

* **workbox:** use nuxt tapables ([4c52955](https://github.com/nuxt/modules/commit/4c52955))




<a name="1.1.6"></a>
## [1.1.6](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.5...@nuxtjs/workbox@1.1.6) (2017-08-11)


### Bug Fixes

* **workbox:** fix globDirectory ([db6588f](https://github.com/nuxt/modules/commit/db6588f))




<a name="1.1.5"></a>
## [1.1.5](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.4...@nuxtjs/workbox@1.1.5) (2017-08-11)


### Bug Fixes

* **workbox:** explicitly provide globDirectory ([6c4f984](https://github.com/nuxt/modules/commit/6c4f984))




<a name="1.1.4"></a>
## [1.1.4](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.3...@nuxtjs/workbox@1.1.4) (2017-08-06)


### Bug Fixes

* **workbox:** correct serviceworker check (#109) ([53897f1](https://github.com/nuxt/modules/commit/53897f1))




<a name="1.1.3"></a>
## [1.1.3](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.2...@nuxtjs/workbox@1.1.3) (2017-08-02)


### Bug Fixes

* **workbox:** only cach css and js files ([42e3edb](https://github.com/nuxt/modules/commit/42e3edb))




<a name="1.1.2"></a>
## [1.1.2](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.1...@nuxtjs/workbox@1.1.2) (2017-07-31)




<a name="1.1.1"></a>
## [1.1.1](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.1.0...@nuxtjs/workbox@1.1.1) (2017-07-19)


### Bug Fixes

* **workbox:** don't use regexs ([19502d9](https://github.com/nuxt/modules/commit/19502d9))




<a name="1.1.0"></a>
# [1.1.0](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.0.1...@nuxtjs/workbox@1.1.0) (2017-07-19)


### Features

* **workbox:** enable clientsClaim by default ([f7001ad](https://github.com/nuxt/modules/commit/f7001ad))




<a name="1.0.1"></a>
## [1.0.1](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@1.0.0...@nuxtjs/workbox@1.0.1) (2017-07-19)


### Bug Fixes

* **workbox:** update modifyUrlPrefix for latest workbox (#75) ([93e3b66](https://github.com/nuxt/modules/commit/93e3b66)), closes [#75](https://github.com/nuxt/modules/issues/75)




<a name="0.4.0"></a>
# [0.4.0](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.3.4...@nuxtjs/workbox@0.4.0) (2017-06-06)


### Features

* **workbox:** simplify publicPath & routerBase ([ab1cb77](https://github.com/nuxt/modules/commit/ab1cb77))




<a name="0.3.4"></a>
## [0.3.4](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.3.3...@nuxtjs/workbox@0.3.4) (2017-06-05)


### Bug Fixes

* **workbox:** incorrect swURL when routerBase is / ([efbd90e](https://github.com/nuxt/modules/commit/efbd90e))




<a name="0.3.3"></a>
## [0.3.3](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.3.2...@nuxtjs/workbox@0.3.3) (2017-06-04)


### Performance Improvements

* **workbox:** use default options ([946546f](https://github.com/nuxt/modules/commit/946546f))




<a name="0.3.2"></a>
## [0.3.2](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.3.1...@nuxtjs/workbox@0.3.2) (2017-06-04)


### Bug Fixes

* **workbox:** empty scope ([50326e9](https://github.com/nuxt/modules/commit/50326e9))




<a name="0.3.1"></a>
## [0.3.1](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.3.0...@nuxtjs/workbox@0.3.1) (2017-06-04)


### Bug Fixes

* prevent invalid url when router base is / ([f0fd863](https://github.com/nuxt/modules/commit/f0fd863))




<a name="0.3.0"></a>
# [0.3.0](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.2.0...@nuxtjs/workbox@0.3.0) (2017-06-04)


### Features

* **workbox:** full offline support ([9ee7f8f](https://github.com/nuxt/modules/commit/9ee7f8f))




<a name="0.2.0"></a>
# [0.2.0](https://github.com/nuxt/modules/compare/@nuxtjs/workbox@0.1.0...@nuxtjs/workbox@0.2.0) (2017-06-02)


### Features

* **workbox:** improve service worker ([445a1c2](https://github.com/nuxt/modules/commit/445a1c2))




<a name="0.1.0"></a>
# 0.1.0 (2017-06-02)


### Features

* workbox ([3d919c3](https://github.com/nuxt/modules/commit/3d919c3))
