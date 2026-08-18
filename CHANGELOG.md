# Changelog

## [0.4.4](https://github.com/LukaHummel/cooklang-obsidian/compare/0.11.8...0.4.4) (2026-08-18)


### Features

* add 'Group ingredients by section' setting toggle ([#69](https://github.com/LukaHummel/cooklang-obsidian/issues/69)) ([b39238e](https://github.com/LukaHummel/cooklang-obsidian/commit/b39238e1ae02709cfa7c050c88899cf59a04ac1a))
* add buildSectionGroups helper for per-section ingredients ([#69](https://github.com/LukaHummel/cooklang-obsidian/issues/69)) ([dbf0c2d](https://github.com/LukaHummel/cooklang-obsidian/commit/dbf0c2d338f286f406be75c5633ab5bf349939c1))
* add Create Recipe option to file explorer context menu ([ff7a693](https://github.com/LukaHummel/cooklang-obsidian/commit/ff7a693045929ccb236455c9ca1a6f401d1dace9)), closes [#6](https://github.com/LukaHummel/cooklang-obsidian/issues/6)
* add Default view setting (source/preview on open) ([8d319ed](https://github.com/LukaHummel/cooklang-obsidian/commit/8d319eda72552522a03e0a299cafaf26a5314525))
* add embedSettings helper for compact cook embeds ([#73](https://github.com/LukaHummel/cooklang-obsidian/issues/73)) ([89ed9f5](https://github.com/LukaHummel/cooklang-obsidian/commit/89ed9f5c03d68a527b7ad78e51afd0d921315df6))
* add getSections view-model helper ([df5ae3a](https://github.com/LukaHummel/cooklang-obsidian/commit/df5ae3aed448b5cec290137aa6432f2e4e1508cc))
* add hero meta-pill model ([a62a4c4](https://github.com/LukaHummel/cooklang-obsidian/commit/a62a4c47317b6245b7f69c7ab8421d78253a4621))
* add interactive timer range controls ([#114](https://github.com/LukaHummel/cooklang-obsidian/issues/114)) ([140d162](https://github.com/LukaHummel/cooklang-obsidian/commit/140d1623af561f0b19c78a58cc161804fd7ca09e))
* Add markdown (.md) file support for better Obsidian integration ([fac5dc5](https://github.com/LukaHummel/cooklang-obsidian/commit/fac5dc52cbbdd83b274f93fdf68198228a7703a4))
* add MarkdownRecipeRenderer for compact cook embeds ([#73](https://github.com/LukaHummel/cooklang-obsidian/issues/73)) ([f4c9d54](https://github.com/LukaHummel/cooklang-obsidian/commit/f4c9d541dc4ff8116c49616812d197b1eebbc85e))
* add per-step image matching helpers ([eaa1729](https://github.com/LukaHummel/cooklang-obsidian/commit/eaa1729aa26b3ced08fffa5ee8592021ec982314))
* add scaler, layout, and step-tracking settings ([64850ab](https://github.com/LukaHummel/cooklang-obsidian/commit/64850ab8593d5b608f15effb56f410f47d4de748))
* add servings scaling math helpers ([9e36405](https://github.com/LukaHummel/cooklang-obsidian/commit/9e36405c0be85766fcdbe5f778b247d1f98a7beb))
* add toggle preview keyboard shortcut ([9cc923f](https://github.com/LukaHummel/cooklang-obsidian/commit/9cc923f09358a1370c65275722ed01133d1945bf))
* add toggle preview keyboard shortcut ([23b2d49](https://github.com/LukaHummel/cooklang-obsidian/commit/23b2d491a54a9074f4346440dd1e81d0be5b83a0))
* aggregate ingredient units with Math.js ([#110](https://github.com/LukaHummel/cooklang-obsidian/issues/110)) ([ae99295](https://github.com/LukaHummel/cooklang-obsidian/commit/ae9929587911bce73f1118bf55543a81a12c4c5e))
* collapsible more-details for leftover metadata ([fa6bb98](https://github.com/LukaHummel/cooklang-obsidian/commit/fa6bb985237f62799c14751395542d93fc5817ef))
* combine duplicate ingredients into one list (CookCLI-style) ([eeef5a9](https://github.com/LukaHummel/cooklang-obsidian/commit/eeef5a9f07c3ed2668f35bfa0792afc627f8d4a7))
* combine same-name ingredients and link recipe references ([8fef167](https://github.com/LukaHummel/cooklang-obsidian/commit/8fef16754693bfb528031763d601c5c1f2d56d0a))
* hero renderer with meta pills and title image ([b2ea5a4](https://github.com/LukaHummel/cooklang-obsidian/commit/b2ea5a42c5fb67fb6b49fdbe3082b24bf8cb4ae9))
* migrate recipe UI to Svelte 5 ([#109](https://github.com/LukaHummel/cooklang-obsidian/issues/109)) ([c14328b](https://github.com/LukaHummel/cooklang-obsidian/commit/c14328b232f8091ae12f1ad6a27e0e779f06e55f))
* render cook/cooklang code blocks in markdown notes ([#73](https://github.com/LukaHummel/cooklang-obsidian/issues/73)) ([cbcfe9c](https://github.com/LukaHummel/cooklang-obsidian/commit/cbcfe9cca370bcb8e0e243c5a6528335995d71bd))
* render ingredients grouped by section when enabled ([#69](https://github.com/LukaHummel/cooklang-obsidian/issues/69)) ([daf409d](https://github.com/LukaHummel/cooklang-obsidian/commit/daf409dff2a11c103e6c15f51c136f238cb21658))
* resolve markdown recipe references ([8f14ec1](https://github.com/LukaHummel/cooklang-obsidian/commit/8f14ec17e1affe72578a47dc8e880c8e8b5f1c64))
* rich method steps with sections, notes, images, step tracking ([03b7a15](https://github.com/LukaHummel/cooklang-obsidian/commit/03b7a15a6dedd403f3874f45220d8ecaad9365a8))
* rich preview layout shell + render contract + cookview state ([8abbe3c](https://github.com/LukaHummel/cooklang-obsidian/commit/8abbe3c616bd42acce0192377394caf1f9c2d872))
* rich preview styles using Obsidian theme variables ([79e4b56](https://github.com/LukaHummel/cooklang-obsidian/commit/79e4b567a45a7a064b7af03ed406e52c7179fcfc))
* section-grouped ingredient checklist with scaled quantities ([6414ea7](https://github.com/LukaHummel/cooklang-obsidian/commit/6414ea70b85d583beedcb08558e54529785f5aee))
* show changelog after plugin updates ([#115](https://github.com/LukaHummel/cooklang-obsidian/issues/115)) ([53b331c](https://github.com/LukaHummel/cooklang-obsidian/commit/53b331c165c586b480066cf5f8d078375adca88d))
* sticky scaler bar with servings stepper and nav links ([562b2d2](https://github.com/LukaHummel/cooklang-obsidian/commit/562b2d2f9f5956b0cca134cc755b20812ed5058e))
* support markdown recipe references ([a8fc3c8](https://github.com/LukaHummel/cooklang-obsidian/commit/a8fc3c88fb622c358931c2c5bfff410f0666ae9b))
* switches to @cooklang/cooklang-ts ([15941c4](https://github.com/LukaHummel/cooklang-obsidian/commit/15941c4395cb961de37259335311d1fe86a4f47c))
* switches to @cooklang/cooklang-ts ([5396931](https://github.com/LukaHummel/cooklang-obsidian/commit/53969312d323bf4b9dc9598c4b5dbc8edfb70804))
* use library display functions and helper utilities ([b941c88](https://github.com/LukaHummel/cooklang-obsidian/commit/b941c88ba84749e7f5ea50cc1a2483c074eedc01))


### Bug Fixes

* add index signature for unitMap ([cafd9f8](https://github.com/LukaHummel/cooklang-obsidian/commit/cafd9f8c57d273802bcca8c2b26354f2953a94b1))
* address code review — timer countdown selector, ingredient unit dup, author pill, dead code ([ca6bf8b](https://github.com/LukaHummel/cooklang-obsidian/commit/ca6bf8b8f4fa326aafa3087e634f7a36f3176ab0))
* build release assets from tagged commit ([#107](https://github.com/LukaHummel/cooklang-obsidian/issues/107)) ([3a90446](https://github.com/LukaHummel/cooklang-obsidian/commit/3a90446069ebd1a4b0077cec8b5cbd578abdad39))
* clean up debug logging and add TypeScript cast for WASM instance ([c3ed4ba](https://github.com/LukaHummel/cooklang-obsidian/commit/c3ed4baeac49dba362bae296773e80ef6e3f78a2))
* cleanup ([550df87](https://github.com/LukaHummel/cooklang-obsidian/commit/550df870cdfcd7ba40a3e809680774bebddfdbfa))
* contain wrapped text within recipe pills ([#112](https://github.com/LukaHummel/cooklang-obsidian/issues/112)) ([31d4a94](https://github.com/LukaHummel/cooklang-obsidian/commit/31d4a948062244acca9b6913ecf2b4ef46d604fa))
* Cookware changed `ingredient` -&gt; `cookware` ([ede64b7](https://github.com/LukaHummel/cooklang-obsidian/commit/ede64b79cc7ddbd3b53c90d6f78f15afb10a9bae))
* Cookware changed `ingredient` -&gt; `cookware` ([4f8404a](https://github.com/LukaHummel/cooklang-obsidian/commit/4f8404a187c3c0dee9d8a727b6b65f2b8629767f))
* correct servings scaling factor and reachable targets ([#83](https://github.com/LukaHummel/cooklang-obsidian/issues/83)) ([405d72c](https://github.com/LukaHummel/cooklang-obsidian/commit/405d72c5882c6f39afd03643dcdce1a5bd9c2efe))
* correct servings scaling factor and reachable targets ([#83](https://github.com/LukaHummel/cooklang-obsidian/issues/83)) ([61b0227](https://github.com/LukaHummel/cooklang-obsidian/commit/61b022709fa09b60220a3b449573417072876ce1))
* end note highlighting at line end in cooklang mode ([47f52a6](https://github.com/LukaHummel/cooklang-obsidian/commit/47f52a6ee2a63de3f17d133f072e0e09610d0ed5))
* fall back to filename for hero title when no title metadata ([c4dba53](https://github.com/LukaHummel/cooklang-obsidian/commit/c4dba53269b8636c0b260ead746a9b9d0de9eb9c))
* handle fraction quantities (NaN) and use author's unit in combined list ([5f6a223](https://github.com/LukaHummel/cooklang-obsidian/commit/5f6a223d91b64da9887f7064c93d7c57e6a71e20))
* import Parser directly from WASM bindings to bypass broken auto-initialization ([ceeb4b7](https://github.com/LukaHummel/cooklang-obsidian/commit/ceeb4b706681b96106ac329a6ce712fcc04a80dc))
* improve mobile WebView compatibility ([#119](https://github.com/LukaHummel/cooklang-obsidian/issues/119)) ([65f56a5](https://github.com/LukaHummel/cooklang-obsidian/commit/65f56a5b88369f6af66e7760c915f65cfb3d1ff9))
* ingredients, timers and cookwares are now displayed correctly ([8ef4e75](https://github.com/LukaHummel/cooklang-obsidian/commit/8ef4e75bd88b74c547ef49f2616b4cf29f7439a6))
* initialize timer range sliders at midpoint ([#121](https://github.com/LukaHummel/cooklang-obsidian/issues/121)) ([d8634e1](https://github.com/LukaHummel/cooklang-obsidian/commit/d8634e1f26511265ddd0c6263db90198c92791a5))
* isolate timer slider gestures from navigation ([#123](https://github.com/LukaHummel/cooklang-obsidian/issues/123)) ([9ea217e](https://github.com/LukaHummel/cooklang-obsidian/commit/9ea217e3900873f67e17613908fe46786553fc4c))
* keep code editor visible above mobile keyboard ([#127](https://github.com/LukaHummel/cooklang-obsidian/issues/127)) ([f51dcd0](https://github.com/LukaHummel/cooklang-obsidian/commit/f51dcd04780a70eca703ea06813976f5e5db63e0))
* lazy-initialize parser to avoid WASM timing issues ([594d923](https://github.com/LukaHummel/cooklang-obsidian/commit/594d923762173ba5f977da2ac23391ae43dabdfd))
* make it work ([726d9dd](https://github.com/LukaHummel/cooklang-obsidian/commit/726d9dd6cfdaed02acee1a887bc3069a56a33a7f))
* manually initialize WASM to work with Rollup bundler ([ca0af10](https://github.com/LukaHummel/cooklang-obsidian/commit/ca0af10e0629e2409a2663ea2b1ff1b39859213d))
* manually instantiate WASM Module to get exports ([9fbd438](https://github.com/LukaHummel/cooklang-obsidian/commit/9fbd43863c19f7e903d0e87b707ed6746f03e32c))
* migrate parser to published @cooklang/cooklang package ([3e7618d](https://github.com/LukaHummel/cooklang-obsidian/commit/3e7618d6a30512a56f1020883b86f971bdecb4a2))
* mirror non-exported Servings/RecipeTime types locally ([5072a07](https://github.com/LukaHummel/cooklang-obsidian/commit/5072a07f8d9de91581cd125457fa9977d218289f))
* numbers display ([ad04a0e](https://github.com/LukaHummel/cooklang-obsidian/commit/ad04a0e516de150827440e4e4517f66d7b02f26c))
* obsidian edit mode ([6e2062a](https://github.com/LukaHummel/cooklang-obsidian/commit/6e2062af4f8dd403d83edefd81a2b98b1c5d3830))
* pass WASM instance exports to __wbg_set_wasm ([cd2ca8b](https://github.com/LukaHummel/cooklang-obsidian/commit/cd2ca8b0aa3becb0f0b401659c4998a7aa2b98b4))
* pause timers and space labels ([f7dbc43](https://github.com/LukaHummel/cooklang-obsidian/commit/f7dbc43279a6fae2ee467a8cb302ba54b95f59f0))
* preserve adjacent note line breaks ([19b870d](https://github.com/LukaHummel/cooklang-obsidian/commit/19b870ddb3e8b8b4c2028047be1d093c16a9ad49))
* preserve back navigation for markdown recipes ([bef9aa6](https://github.com/LukaHummel/cooklang-obsidian/commit/bef9aa629c2a18c75ad5a69a9c4b4aca5c2b86ed))
* preserve back navigation for Markdown recipes ([7eb21fd](https://github.com/LukaHummel/cooklang-obsidian/commit/7eb21fda0eb3b71f578e7ba5c9b41638bd1278a9))
* preserve inline Cooklang note order ([699f20e](https://github.com/LukaHummel/cooklang-obsidian/commit/699f20e5c3d18ad0943d2f29e0805ca4e2f5cba7))
* preserve inline Cooklang note order ([e134c2f](https://github.com/LukaHummel/cooklang-obsidian/commit/e134c2f94efb55b44329fd33fe5806e24a861c83))
* preserve line breaks in cook note text ([7491efe](https://github.com/LukaHummel/cooklang-obsidian/commit/7491efea7aa587d389569feb78a879efa900e340))
* preserve note block line breaks ([83d4290](https://github.com/LukaHummel/cooklang-obsidian/commit/83d42907f6db49eb118f8393fb751736f7fd1ecb))
* refine timer range slider UI ([#117](https://github.com/LukaHummel/cooklang-obsidian/issues/117)) ([fcdc9c0](https://github.com/LukaHummel/cooklang-obsidian/commit/fcdc9c06b9ba73a565bbf1fd89206a14ae1b04bb))
* remove unused files ([1a57787](https://github.com/LukaHummel/cooklang-obsidian/commit/1a57787b3cdee6572d5ff52bcfc49daebe9771a6))
* render inline quantities in recipe steps ([1101248](https://github.com/LukaHummel/cooklang-obsidian/commit/1101248c21aea0c413ccab7265bf084c40a1a71c))
* restore TypeScript build after SectionView migration ([5cfb17a](https://github.com/LukaHummel/cooklang-obsidian/commit/5cfb17a28c39dbe2eb2e9cf29973c37751de619a))
* reveal mobile caret after keyboard resize ([#129](https://github.com/LukaHummel/cooklang-obsidian/issues/129)) ([ae032bb](https://github.com/LukaHummel/cooklang-obsidian/commit/ae032bbf20bf88b6ecfbbc6d4323b49420bb5a8d))
* specify repository for release upload ([20803c5](https://github.com/LukaHummel/cooklang-obsidian/commit/20803c56445260a52e3ccbc57053f160e4062a10))
* stop note syntax highlighting at line end ([261a0f1](https://github.com/LukaHummel/cooklang-obsidian/commit/261a0f1dbd7758f3d0853aace2247433020d7b4e))
* stop timer click from bubbling to step-tracking handler ([cba8add](https://github.com/LukaHummel/cooklang-obsidian/commit/cba8add5ec3eca20dffaba49e18de3129cc4e77a))
* strip repeated note marker in section notes ([51d51dd](https://github.com/LukaHummel/cooklang-obsidian/commit/51d51ddc082f234ce383e3d4ba8a8ca558f12697))
* suppress Math.js dependency cycle warnings ([#113](https://github.com/LukaHummel/cooklang-obsidian/issues/113)) ([e14c7bd](https://github.com/LukaHummel/cooklang-obsidian/commit/e14c7bd16973477ba06c09344189c2bf06f1115d))
* timer double-click ([#74](https://github.com/LukaHummel/cooklang-obsidian/issues/74)) and unicode ingredient highlighting ([#29](https://github.com/LukaHummel/cooklang-obsidian/issues/29)) ([f45e19e](https://github.com/LukaHummel/cooklang-obsidian/commit/f45e19e5c1edb013eb5646bb9a9d02eb77c86875))
* ts warnings ([27e1389](https://github.com/LukaHummel/cooklang-obsidian/commit/27e1389f4b1e13eb8ab7897a4e85229d9a880612))
* Unused setting `lineWrap` ([5251b13](https://github.com/LukaHummel/cooklang-obsidian/commit/5251b13d7155e1303d236486dff20202065b4c68))
* Unused setting `showQuantitiesInline` ([935fcdb](https://github.com/LukaHummel/cooklang-obsidian/commit/935fcdb3f8a8f633637d5a3c7cfbb75223485db4))
* Unused setting `showTimersInline` ([042b081](https://github.com/LukaHummel/cooklang-obsidian/commit/042b08163ea9b86a5b176e5350990537ddbb6e31))
* Unused settings `timersTick` and `timersRing` ([536af73](https://github.com/LukaHummel/cooklang-obsidian/commit/536af73ec960fc08cde309dc845618dff0a9b777))
* use 1-based step image numbering to match cookcli ([dbcb806](https://github.com/LukaHummel/cooklang-obsidian/commit/dbcb8063ff902d6105c4a0198ee33d3f59e4c878)), closes [#80](https://github.com/LukaHummel/cooklang-obsidian/issues/80)
* use global WASM singleton to prevent memory corruption with multiple views ([465e95d](https://github.com/LukaHummel/cooklang-obsidian/commit/465e95dc9609bce484e71a9c8d55ef063458b781))
* use local package and add WASM initialization delay ([b9aef77](https://github.com/LukaHummel/cooklang-obsidian/commit/b9aef779ccb76f578d07346331bec12dc47a109b))
* use native mobile editor layout ([#132](https://github.com/LukaHummel/cooklang-obsidian/issues/132)) ([0411507](https://github.com/LukaHummel/cooklang-obsidian/commit/0411507277b2feb4bc693c9199b039e51f8b8dc2))
* use Obsidian colors for Cooklang editor ([#125](https://github.com/LukaHummel/cooklang-obsidian/issues/125)) ([3966389](https://github.com/LukaHummel/cooklang-obsidian/commit/39663898e16ba93f8019afe3a8ae2e6413ffb782))
* wrap long cookware names ([694c4ba](https://github.com/LukaHummel/cooklang-obsidian/commit/694c4ba2c3f641cd3a9446323df39ea9e3f7cf04))


### Miscellaneous Chores

* release 0.4.4 ([ecc0868](https://github.com/LukaHummel/cooklang-obsidian/commit/ecc086826834442511a61211592360421c53f24e))

## [0.11.8](https://github.com/cooklang/cooklang-obsidian/compare/0.11.7...0.11.8) (2026-08-18)


### Bug Fixes

* use native mobile editor layout ([#132](https://github.com/cooklang/cooklang-obsidian/issues/132)) ([0411507](https://github.com/cooklang/cooklang-obsidian/commit/0411507277b2feb4bc693c9199b039e51f8b8dc2))

## [0.11.7](https://github.com/cooklang/cooklang-obsidian/compare/0.11.6...0.11.7) (2026-08-18)


### Bug Fixes

* reveal mobile caret after keyboard resize ([#129](https://github.com/cooklang/cooklang-obsidian/issues/129)) ([ae032bb](https://github.com/cooklang/cooklang-obsidian/commit/ae032bbf20bf88b6ecfbbc6d4323b49420bb5a8d))

## [0.11.6](https://github.com/cooklang/cooklang-obsidian/compare/0.11.5...0.11.6) (2026-08-17)


### Bug Fixes

* keep code editor visible above mobile keyboard ([#127](https://github.com/cooklang/cooklang-obsidian/issues/127)) ([f51dcd0](https://github.com/cooklang/cooklang-obsidian/commit/f51dcd04780a70eca703ea06813976f5e5db63e0))

## [0.11.5](https://github.com/cooklang/cooklang-obsidian/compare/0.11.4...0.11.5) (2026-08-17)


### Bug Fixes

* use Obsidian colors for Cooklang editor ([#125](https://github.com/cooklang/cooklang-obsidian/issues/125)) ([3966389](https://github.com/cooklang/cooklang-obsidian/commit/39663898e16ba93f8019afe3a8ae2e6413ffb782))

## [0.11.4](https://github.com/cooklang/cooklang-obsidian/compare/0.11.3...0.11.4) (2026-08-13)


### Bug Fixes

* isolate timer slider gestures from navigation ([#123](https://github.com/cooklang/cooklang-obsidian/issues/123)) ([9ea217e](https://github.com/cooklang/cooklang-obsidian/commit/9ea217e3900873f67e17613908fe46786553fc4c))

## [0.11.3](https://github.com/cooklang/cooklang-obsidian/compare/0.11.2...0.11.3) (2026-08-12)


### Bug Fixes

* initialize timer range sliders at midpoint ([#121](https://github.com/cooklang/cooklang-obsidian/issues/121)) ([d8634e1](https://github.com/cooklang/cooklang-obsidian/commit/d8634e1f26511265ddd0c6263db90198c92791a5))

## [0.11.2](https://github.com/cooklang/cooklang-obsidian/compare/0.11.1...0.11.2) (2026-08-11)


### Bug Fixes

* improve mobile WebView compatibility ([#119](https://github.com/cooklang/cooklang-obsidian/issues/119)) ([65f56a5](https://github.com/cooklang/cooklang-obsidian/commit/65f56a5b88369f6af66e7760c915f65cfb3d1ff9))

## [0.11.1](https://github.com/cooklang/cooklang-obsidian/compare/0.11.0...0.11.1) (2026-08-10)


### Bug Fixes

* refine timer range slider UI ([#117](https://github.com/cooklang/cooklang-obsidian/issues/117)) ([fcdc9c0](https://github.com/cooklang/cooklang-obsidian/commit/fcdc9c06b9ba73a565bbf1fd89206a14ae1b04bb))

## [0.11.0](https://github.com/cooklang/cooklang-obsidian/compare/0.10.0...0.11.0) (2026-08-10)


### Features

* add interactive timer range controls ([#114](https://github.com/cooklang/cooklang-obsidian/issues/114)) ([140d162](https://github.com/cooklang/cooklang-obsidian/commit/140d1623af561f0b19c78a58cc161804fd7ca09e))
* show changelog after plugin updates ([#115](https://github.com/cooklang/cooklang-obsidian/issues/115)) ([53b331c](https://github.com/cooklang/cooklang-obsidian/commit/53b331c165c586b480066cf5f8d078375adca88d))


### Bug Fixes

* contain wrapped text within recipe pills ([#112](https://github.com/cooklang/cooklang-obsidian/issues/112)) ([31d4a94](https://github.com/cooklang/cooklang-obsidian/commit/31d4a948062244acca9b6913ecf2b4ef46d604fa))
* suppress Math.js dependency cycle warnings ([#113](https://github.com/cooklang/cooklang-obsidian/issues/113)) ([e14c7bd](https://github.com/cooklang/cooklang-obsidian/commit/e14c7bd16973477ba06c09344189c2bf06f1115d))

## [0.10.0](https://github.com/cooklang/cooklang-obsidian/compare/0.9.4...0.10.0) (2026-08-09)


### Features

* aggregate ingredient units with Math.js ([#110](https://github.com/cooklang/cooklang-obsidian/issues/110)) ([ae99295](https://github.com/cooklang/cooklang-obsidian/commit/ae9929587911bce73f1118bf55543a81a12c4c5e))
* migrate recipe UI to Svelte 5 ([#109](https://github.com/cooklang/cooklang-obsidian/issues/109)) ([c14328b](https://github.com/cooklang/cooklang-obsidian/commit/c14328b232f8091ae12f1ad6a27e0e779f06e55f))

## [0.9.4](https://github.com/cooklang/cooklang-obsidian/compare/0.9.3...0.9.4) (2026-08-05)


### Bug Fixes

* build release assets from tagged commit ([#107](https://github.com/cooklang/cooklang-obsidian/issues/107)) ([3a90446](https://github.com/cooklang/cooklang-obsidian/commit/3a90446069ebd1a4b0077cec8b5cbd578abdad39))

## [0.9.3](https://github.com/cooklang/cooklang-obsidian/compare/0.9.2...0.9.3) (2026-08-04)


### Bug Fixes

* render inline quantities in recipe steps ([1101248](https://github.com/cooklang/cooklang-obsidian/commit/1101248c21aea0c413ccab7265bf084c40a1a71c))
* wrap long cookware names ([694c4ba](https://github.com/cooklang/cooklang-obsidian/commit/694c4ba2c3f641cd3a9446323df39ea9e3f7cf04))

## [0.9.2](https://github.com/cooklang/cooklang-obsidian/compare/0.9.1...0.9.2) (2026-08-03)


### Bug Fixes

* specify repository for release upload ([20803c5](https://github.com/cooklang/cooklang-obsidian/commit/20803c56445260a52e3ccbc57053f160e4062a10))

## [0.9.1](https://github.com/cooklang/cooklang-obsidian/compare/0.9.0...0.9.1) (2026-08-03)


### Bug Fixes

* restore TypeScript build after SectionView migration ([5cfb17a](https://github.com/cooklang/cooklang-obsidian/commit/5cfb17a28c39dbe2eb2e9cf29973c37751de619a))

## [0.9.0](https://github.com/cooklang/cooklang-obsidian/compare/0.8.1...0.9.0) (2026-08-02)


### Features

* resolve markdown recipe references ([8f14ec1](https://github.com/cooklang/cooklang-obsidian/commit/8f14ec17e1affe72578a47dc8e880c8e8b5f1c64))
* support markdown recipe references ([a8fc3c8](https://github.com/cooklang/cooklang-obsidian/commit/a8fc3c88fb622c358931c2c5bfff410f0666ae9b))


### Bug Fixes

* end note highlighting at line end in cooklang mode ([47f52a6](https://github.com/cooklang/cooklang-obsidian/commit/47f52a6ee2a63de3f17d133f072e0e09610d0ed5))
* preserve adjacent note line breaks ([19b870d](https://github.com/cooklang/cooklang-obsidian/commit/19b870ddb3e8b8b4c2028047be1d093c16a9ad49))
* preserve back navigation for markdown recipes ([bef9aa6](https://github.com/cooklang/cooklang-obsidian/commit/bef9aa629c2a18c75ad5a69a9c4b4aca5c2b86ed))
* preserve back navigation for Markdown recipes ([7eb21fd](https://github.com/cooklang/cooklang-obsidian/commit/7eb21fda0eb3b71f578e7ba5c9b41638bd1278a9))
* preserve inline Cooklang note order ([699f20e](https://github.com/cooklang/cooklang-obsidian/commit/699f20e5c3d18ad0943d2f29e0805ca4e2f5cba7))
* preserve inline Cooklang note order ([e134c2f](https://github.com/cooklang/cooklang-obsidian/commit/e134c2f94efb55b44329fd33fe5806e24a861c83))
* preserve line breaks in cook note text ([7491efe](https://github.com/cooklang/cooklang-obsidian/commit/7491efea7aa587d389569feb78a879efa900e340))
* preserve note block line breaks ([83d4290](https://github.com/cooklang/cooklang-obsidian/commit/83d42907f6db49eb118f8393fb751736f7fd1ecb))
* stop note syntax highlighting at line end ([261a0f1](https://github.com/cooklang/cooklang-obsidian/commit/261a0f1dbd7758f3d0853aace2247433020d7b4e))
* strip repeated note marker in section notes ([51d51dd](https://github.com/cooklang/cooklang-obsidian/commit/51d51ddc082f234ce383e3d4ba8a8ca558f12697))

## [0.8.1](https://github.com/cooklang/cooklang-obsidian/compare/0.8.0...0.8.1) (2026-06-29)


### Bug Fixes

* correct servings scaling factor and reachable targets ([#83](https://github.com/cooklang/cooklang-obsidian/issues/83)) ([405d72c](https://github.com/cooklang/cooklang-obsidian/commit/405d72c5882c6f39afd03643dcdce1a5bd9c2efe))
* correct servings scaling factor and reachable targets ([#83](https://github.com/cooklang/cooklang-obsidian/issues/83)) ([61b0227](https://github.com/cooklang/cooklang-obsidian/commit/61b022709fa09b60220a3b449573417072876ce1))
* use 1-based step image numbering to match cookcli ([dbcb806](https://github.com/cooklang/cooklang-obsidian/commit/dbcb8063ff902d6105c4a0198ee33d3f59e4c878)), closes [#80](https://github.com/cooklang/cooklang-obsidian/issues/80)

## 0.8.0

### Added
- ` ```cook ` (and ` ```cooklang `) fenced code blocks inside markdown notes now
  render as a compact, read-only recipe — ingredients list plus numbered steps —
  in reading mode (#73).
- New **Group ingredients by section** setting (off by default): when a recipe
  uses `= Section` headers, the ingredient list is split under each section's
  title, with quantities aggregated within each section (#69).

### Fixed
- Clicking a running timer in the recipe preview no longer starts a second
  countdown; repeat clicks while a timer is counting down are ignored, fixing the
  erratic display caused by overlapping intervals (#74).
- Ingredient, cookware, and timer names with umlauts or accents (e.g. `@Möhre`,
  `#Schäler`) are now fully highlighted in the editor instead of being cut off at
  the first non-ASCII letter (#29).

## 0.7.1

### Added
- Ingredient list now combines the same ingredient listed multiple times into one
  row, summing quantities that share a unit (different units shown side by side;
  ranges/textual amounts listed as-is).
- Recipe references (`@./Components/Beans`) render as clickable links to the
  referenced `.cook` file — both in the ingredient list and inline in the steps —
  falling back to plain text when the target isn't found.

## 0.7.0

### Added
- Redesigned recipe preview into a single rich page: hero with title image and meta
  pills (time, servings, difficulty, source, tags), a sticky servings scaler that
  rescales quantities live, a two-column ingredients/steps layout, Cooklang section &
  note support, per-step images, and tap-to-track current step. Fully themed via
  Obsidian CSS variables, so it adapts to any theme.
- Ingredients are now a single combined list (CookCLI-style): duplicates are merged
  and their quantities summed (handles fractions and mixed units).
- New settings: **Default view** (open recipes in source or preview), **Servings
  scaler**, **Two-column layout**, **Step tracking**, and a **Servings label**.

### Changed
- Switched the parser dependency from the temporary `@cooklang/cooklang-ts` preview
  build to the published `@cooklang/cooklang` package, so the plugin builds and
  releases reproducibly.

## 0.6.3

### Fixed
- Fixed bug on mobile where all .md files appeared as cooklang recipes after opening a .cook file (#62)

## 0.6.2

## 0.6.1

### Fixed
- Fixed manifest name

## 0.6.0

### Added
- Support for .md files with `recipe: true` frontmatter
- Context menu option to open .md files as recipes
- Mark ingredients as added
