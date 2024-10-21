# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [7.0.1](https://github.com/pattern-lab/patternlab-node/compare/v7.0.0...v7.0.1) (2024-10-21)

**Note:** Version bump only for package patternlab-node





# 7.0.0 (2024-10-21)


### Bug Fixes

* .eslintrc without extension ([06f8b6a](https://github.com/pattern-lab/patternlab-node/commit/06f8b6a5545cec46938c07124fbfe8466b8b2288))
* **1049:** Treat folders like patterns only if they're subfolders of pattern groupings ([4eb79ab](https://github.com/pattern-lab/patternlab-node/commit/4eb79ab48b335a35b2e5ed3b7053974b8e8bb6b6))
* a11y fix on text contrast ([6d75b22](https://github.com/pattern-lab/patternlab-node/commit/6d75b226ce27228025b2915e5d402f7080faee31))
* a11y issue on a missing description of that complementary icon ([4f13807](https://github.com/pattern-lab/patternlab-node/commit/4f13807cb93df33435088de3a51170b9c4515889))
* actually exit build when Twig render fails ([5d28a24](https://github.com/pattern-lab/patternlab-node/commit/5d28a24a53011396289c1e29e0a715cd82470185))
* add a new method to check if PL is currently compiling + add new method to get the config PL is using ([26e886c](https://github.com/pattern-lab/patternlab-node/commit/26e886c93db5d135c91de648724f7278c4d5b3e9))
* add better pre-rendering support ([8ecd615](https://github.com/pattern-lab/patternlab-node/commit/8ecd6159a89232f42e0a9dc3c688b6e21de8fc30))
* add eslint fixes ([00d7bbe](https://github.com/pattern-lab/patternlab-node/commit/00d7bbe319ea77a6ee8cc9cd0348856feaaf13ad))
* add missing “dist” folder to array of files / folders published to NPM ([8829429](https://github.com/pattern-lab/patternlab-node/commit/88294296c438352570befd2eb6b9e1ca2ae3b750))
* add missing @babel/runtime package to address silent error getting thrown on Travis ([1918d04](https://github.com/pattern-lab/patternlab-node/commit/1918d042d7e90cc8aaa2fdfcd8649961c0a5dd50))
* add missing $ ([c95a06e](https://github.com/pattern-lab/patternlab-node/commit/c95a06ece78631b068f8721666caf33452e57a7a))
* add missing node-sass dependency ([643808b](https://github.com/pattern-lab/patternlab-node/commit/643808b0d1a3e2e65cb462bac272ceeb6e55273b))
* add missing preact-render-to-string library ([881296a](https://github.com/pattern-lab/patternlab-node/commit/881296a2c256424beac28bd560c5b1a5e1fed005))
* add missing style-loader ([0ce7470](https://github.com/pattern-lab/patternlab-node/commit/0ce74705bb2886350459d429be1624c33781e4c8))
* add PluginTab workaround for Safari ([2fa9367](https://github.com/pattern-lab/patternlab-node/commit/2fa936769be65484af52f242dca2536a3382462c))
* add repo info to root package.json so Auto knows what repo to configure for ([85142e8](https://github.com/pattern-lab/patternlab-node/commit/85142e8e94549edd7980459e5975d0639c34864d))
* add webpack-cli as a uikit-workshop dependency; update npm script to use locally installed version vs globally / temp version via npx ([812efe9](https://github.com/pattern-lab/patternlab-node/commit/812efe9a56c630cd19724eb597e4e335c9193cf5))
* address bug causing viewport width to progressively decrease in size when resizing your screen / refreshing on certain devices ([41b11af](https://github.com/pattern-lab/patternlab-node/commit/41b11af8aaaf066fcf99abd2513eae8706122d32))
* address unrelated eslint errors from PL core ([6ada00d](https://github.com/pattern-lab/patternlab-node/commit/6ada00d396eb436837f7453664bfa50522a2ec10))
* adjust how PL's viewport is sized / positioned when the sidebar layout is active so iframed content is centered properly ([3caffbf](https://github.com/pattern-lab/patternlab-node/commit/3caffbf02a487b9a5c45af816226096bf9ce9b2c))
* adjust logo sizing in readme ([94ad88f](https://github.com/pattern-lab/patternlab-node/commit/94ad88f5782b63bda6ca4de26fb7008093dca551))
* adjust UIKit Nav updates to account for the noViewAll config variation ([73eac97](https://github.com/pattern-lab/patternlab-node/commit/73eac976461f4e587b0c30668942c4895aea319f))
* **annotations:** displaying annotation tooltips correctly ([#1406](https://github.com/pattern-lab/patternlab-node/issues/1406)) ([3f33ce5](https://github.com/pattern-lab/patternlab-node/commit/3f33ce5c51f2f7a6afd86d3500b7659afd0198e6)), closes [#2](https://github.com/pattern-lab/patternlab-node/issues/2) [#1](https://github.com/pattern-lab/patternlab-node/issues/1)
* **annotations:** hiding those correctly ([#1415](https://github.com/pattern-lab/patternlab-node/issues/1415)) ([ef0a60f](https://github.com/pattern-lab/patternlab-node/commit/ef0a60fcc8656acc6d83bb0723c02a658f7ff1f3))
* **asset copy:** Resolve paths correctly. Break apart files & asyncify ([379419c](https://github.com/pattern-lab/patternlab-node/commit/379419c035fddf9789f0fa4bf05fe286666e27f7))
* **build:** improve stability of changes causing a live-server reload ([06c6123](https://github.com/pattern-lab/patternlab-node/commit/06c61237a8c197a58129846296e7b7e20b254aa3))
* **buildPatterns:** move meta processing back into function for now ([cea2c45](https://github.com/pattern-lab/patternlab-node/commit/cea2c45ba6d6f3f0ed5772027dbec2b28aba0bf1))
* change const back to var since PL's Uikit JS isn't run through Babel just yet.. update Prettier config to ignore Uikit's JavaScript for the time being ([35c5726](https://github.com/pattern-lab/patternlab-node/commit/35c5726af130b7165b08745dd45bd10a3ac3e0a4))
* **changes_hunter:** guard for incrementalRebuild while watching ([c652b9c](https://github.com/pattern-lab/patternlab-node/commit/c652b9ced3c87c80239174a50c90d2695ed1a1a3)), closes [#794](https://github.com/pattern-lab/patternlab-node/issues/794) [#802](https://github.com/pattern-lab/patternlab-node/issues/802)
* check if dependency graph file exists before trying to remove ([f9af6a9](https://github.com/pattern-lab/patternlab-node/commit/f9af6a95025a22041e7ff8a4bfb19e4727385e98))
* check to make sure the code panel-related <script> tag contains data before attempting to parse expected JSON. Partial fix to [#761](https://github.com/pattern-lab/patternlab-node/issues/761) as this should at least help prevent the current batch of JS errors from getting thrown ([9c16675](https://github.com/pattern-lab/patternlab-node/commit/9c166753d7f4df9987962497f2978928a341fb96))
* clean up and fix overflow / scrolling issues ([bc13bd2](https://github.com/pattern-lab/patternlab-node/commit/bc13bd2956454602ec25d26db3a5822361de015f))
* clean up Pattern.createEmpty conditionals to improve readability; fix typo / formatting bug causing mustache loader to not compile base UI templates as expected ([0c965cc](https://github.com/pattern-lab/patternlab-node/commit/0c965cc7f7fca2d5100f2e92438f5799bb934fe7))
* **cli:** add custom install logic to edition-node ([f04fd26](https://github.com/pattern-lab/patternlab-node/commit/f04fd266429cd806987dab747e6d69bff9b926a4))
* **cli:** allow any package to be installed as a starterkit ([d2aa1be](https://github.com/pattern-lab/patternlab-node/commit/d2aa1be810a0a7473dcc52391a2263dacfdda0b8)), closes [#1067](https://github.com/pattern-lab/patternlab-node/issues/1067)
* **cli:** change line-endings of cli entrypoint ([3fc86c2](https://github.com/pattern-lab/patternlab-node/commit/3fc86c29030189276baa655da02ff4ed68dcb80e))
* **cli:** change whitespace to spaces per standard ([4556fc7](https://github.com/pattern-lab/patternlab-node/commit/4556fc7d12a1d11b401821919ff2f3ddc5658c93))
* **cli:** do not call build before serve ([663d8e1](https://github.com/pattern-lab/patternlab-node/commit/663d8e185efd951ae67a37e3ec97f76d6cec0d5e)), closes [#917](https://github.com/pattern-lab/patternlab-node/issues/917)
* **cli:** ensure specified directory exists prior to scaffold ([cc3b696](https://github.com/pattern-lab/patternlab-node/commit/cc3b69624d486c94ee3b1f4b1bbb0334a514fa59))
* **cli:** fix test script glob ([ff18eb5](https://github.com/pattern-lab/patternlab-node/commit/ff18eb51ce24fc5423b009168e85ede366069139))
* **cli:** merge config arrays via overwrite instead of concatenate ([42e5f7b](https://github.com/pattern-lab/patternlab-node/commit/42e5f7b42a26b4fc1f262c68ee4b474b546f2eac))
* **cli:** pass watch options cleanly to core ([8bf186b](https://github.com/pattern-lab/patternlab-node/commit/8bf186b8e2ea2ea5ddcd2d6242b670275b65567f))
* **cli:** proper path resolution to helpers ([a18fe5e](https://github.com/pattern-lab/patternlab-node/commit/a18fe5ef4d1c074a5eba8bfa255ebbee2261bf74))
* **cli:** re-order and clarify engines ([e39e301](https://github.com/pattern-lab/patternlab-node/commit/e39e301a33306c6615fabf64262f1893ca682b97))
* **cli:** remove copy-source-files ([64311a1](https://github.com/pattern-lab/patternlab-node/commit/64311a155f82ddd86806087ad165b9ed880118f3)), closes [#833](https://github.com/pattern-lab/patternlab-node/issues/833)
* **cli:** run npm init -y if needed ([105e91c](https://github.com/pattern-lab/patternlab-node/commit/105e91ce08b4e8a21c5c53e95b0cd2d7287340fe))
* **cli:** set current working directory before scaffolded npm init ([6d2186d](https://github.com/pattern-lab/patternlab-node/commit/6d2186d8e8a74634198a4474ca8ae83221dd70a9))
* **cli:** set initialized to false during plugin installation ([88cce3f](https://github.com/pattern-lab/patternlab-node/commit/88cce3f9e91824f6650b1ea82eca950a480edf06))
* **cli:** support scoped plugins ([4ae13ce](https://github.com/pattern-lab/patternlab-node/commit/4ae13ce99ea17ffa0ab48a0f6370a5b70834d6d3))
* code scanning alert ([#1442](https://github.com/pattern-lab/patternlab-node/issues/1442)) ([749a3e7](https://github.com/pattern-lab/patternlab-node/commit/749a3e722249846c522e3f7de6e73b5afa8531b1))
* color tweak to nav items to match basker brand ([9fe8444](https://github.com/pattern-lab/patternlab-node/commit/9fe8444846ffba3f45b53cb3848ac6632abba5d6))
* comment out example config to disable viewAll links ([ddb3fad](https://github.com/pattern-lab/patternlab-node/commit/ddb3fad5770d1d66432c4b583ae9af09a3a47d48))
* **config:** Add npm registry to lerna config ([1473cd5](https://github.com/pattern-lab/patternlab-node/commit/1473cd554c24b4c1baa4ee5ac59958f3499b9902))
* **config:** update patch to uikit files ([5ccd0d2](https://github.com/pattern-lab/patternlab-node/commit/5ccd0d2ed89ee031f940432b3177cd29417835fa))
* configure the Logo's `altText` config option when used as an HTML attribute ([ade34a2](https://github.com/pattern-lab/patternlab-node/commit/ade34a29435f5112f0449ad020bee7e9dc2c81e1))
* **CONTRIBUTING:** Update contribution guidelines ([b7ee1b4](https://github.com/pattern-lab/patternlab-node/commit/b7ee1b4e2584a69d5765be3709b58f007f96a8d8))
* Contribution guidelines should refer to yarn ([c30cc81](https://github.com/pattern-lab/patternlab-node/commit/c30cc81a3e155072774438304b73d58b6635876d))
* **core:** allow plugin resolution to follow normal algorithm ([3f6b83b](https://github.com/pattern-lab/patternlab-node/commit/3f6b83be080c88aec1d8b73bececb76f0f57a79d))
* **core:** do not warn about uikit-polyfills ([6bb68e7](https://github.com/pattern-lab/patternlab-node/commit/6bb68e763769969546542bf7aaf6d1f4235c6622))
* **core:** find plugins from config only and with simpler args ([fe7351c](https://github.com/pattern-lab/patternlab-node/commit/fe7351cba346425512cbb2ef3a1b7728ab06ae60))
* **core:** Fix tests ([31d67a7](https://github.com/pattern-lab/patternlab-node/commit/31d67a778796c475f1a0a0c3e05477f3eaa8ecc7))
* **core:** re-add cleanPublic fix ([c100bbc](https://github.com/pattern-lab/patternlab-node/commit/c100bbca3f339e9132acb9c482e98c1c8a66b8b5))
* **core:** ReadDocumentation throw error on older node versions ([#1295](https://github.com/pattern-lab/patternlab-node/issues/1295)) ([399d0e1](https://github.com/pattern-lab/patternlab-node/commit/399d0e118ab77a414a926b078da9abbcb5347969))
* **core:** remove useless lerna-changelog ([05ca5c4](https://github.com/pattern-lab/patternlab-node/commit/05ca5c4fcf36a8ebaf7c53f7c73397ffa3049ff7))
* **core:** rename serverModule import to avoid conflict with CLI ([f3170e7](https://github.com/pattern-lab/patternlab-node/commit/f3170e7db1f004e99828884743ab74adc0ddf783))
* **core:** Subgroup cannot be hidden ([#1368](https://github.com/pattern-lab/patternlab-node/issues/1368)) ([3ce13ab](https://github.com/pattern-lab/patternlab-node/commit/3ce13abffaab2810194003aeca88be671fedd38f))
* correct typo in build logging ([96d989f](https://github.com/pattern-lab/patternlab-node/commit/96d989f8869630ba9f59705bfca66755f20e35ab))
* corrected some github urls ([#1388](https://github.com/pattern-lab/patternlab-node/issues/1388)) ([7f37e9d](https://github.com/pattern-lab/patternlab-node/commit/7f37e9d56b553dc4be53590766c0fc6251458829))
* **create:** deprecating @pattern-lab/create in favor of create-pattern-lab ([416ba0e](https://github.com/pattern-lab/patternlab-node/commit/416ba0e50fe7e9a75d2b3f4a6d41b7bcc0c2da5b))
* CSS fix to properly highlight the correct active page / link in the Nav; improve dropdown open / close animation ([ec4ab84](https://github.com/pattern-lab/patternlab-node/commit/ec4ab84ddc8007796c9012a3f493822d76f039a7))
* **data_loader:** look for exact name of the file passed in ([eb46be2](https://github.com/pattern-lab/patternlab-node/commit/eb46be232ef6ea92b02e460803ecc1ca656e7184))
* **demopage:** switched to HTTPS URLs for image placeholders ([#1289](https://github.com/pattern-lab/patternlab-node/issues/1289)) ([e09bf6a](https://github.com/pattern-lab/patternlab-node/commit/e09bf6aae9bad99365b5a01381e0df6de9ddeafe))
* **dependencies:** pin all packages marked as latest ([87347d5](https://github.com/pattern-lab/patternlab-node/commit/87347d5a9bf28be680f79e84e44863908e8f83e0))
* **deploy:** add setup command ([74dd314](https://github.com/pattern-lab/patternlab-node/commit/74dd3142bf48873a9f1ec4e8dccb8aa2fef9001d))
* **deploy:** add setup command ([7c1d8d1](https://github.com/pattern-lab/patternlab-node/commit/7c1d8d14842a467bb301e2ede2ec83074ff35ae2))
* div isn't allowed in button elements ([#1438](https://github.com/pattern-lab/patternlab-node/issues/1438)) ([e5c6950](https://github.com/pattern-lab/patternlab-node/commit/e5c6950e6218df99f9d9d35388c36a0130236f28))
* **docs:** corrected a URL ([26ede14](https://github.com/pattern-lab/patternlab-node/commit/26ede14a6eafe8649cbc6b0076d84f1d323c3e20))
* **docs:** fixed css code for custom patternstates color ([8995241](https://github.com/pattern-lab/patternlab-node/commit/89952416162c01d1e3e05221ce58a7755544131c)), closes [#1216](https://github.com/pattern-lab/patternlab-node/issues/1216)
* **docs:** google lighthouse error - bg and text contrast ratio [#1197](https://github.com/pattern-lab/patternlab-node/issues/1197) ([f43978a](https://github.com/pattern-lab/patternlab-node/commit/f43978a3a121b661cfbf763ba72bcda2c36a5d3a))
* **docs:** headlines styling breaks in edge cases [#1158](https://github.com/pattern-lab/patternlab-node/issues/1158) ([d8244a2](https://github.com/pattern-lab/patternlab-node/commit/d8244a2d307b0a81d0846491f8c5a12e0ae167a5))
* **docs:** regenerate API documentation ([830c568](https://github.com/pattern-lab/patternlab-node/commit/830c568dae28e743917a9d19860a5ec13641c8d8))
* **docs:** resolving broken link (new URL) in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([8dc020a](https://github.com/pattern-lab/patternlab-node/commit/8dc020a217b51cfafdd62ceca95fc42811a6c285))
* **docs:** resolving broken link (new URL) in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([f557fdd](https://github.com/pattern-lab/patternlab-node/commit/f557fddeda640d88c7267d9d5fba8e8cc5e07929))
* **docs:** resolving broken link (new URL) in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([0023a91](https://github.com/pattern-lab/patternlab-node/commit/0023a910126a635006c1ad468a412af0e93338fb))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([c9635ec](https://github.com/pattern-lab/patternlab-node/commit/c9635ec2d9eb700b23188d5c72b83b3d16e6deda))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([f56ad39](https://github.com/pattern-lab/patternlab-node/commit/f56ad3951ea0319a43f0b1aeabba0d3ad96c5553))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([cae9420](https://github.com/pattern-lab/patternlab-node/commit/cae94208c52e4068430e048e729f4ff97847715a))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([84138c3](https://github.com/pattern-lab/patternlab-node/commit/84138c36cdfe5b9a38b34e32b177a0416b077716))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([374c103](https://github.com/pattern-lab/patternlab-node/commit/374c103a59504ba239b16680f86a89b4d95e304f))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([cb0fcdb](https://github.com/pattern-lab/patternlab-node/commit/cb0fcdb5ad8504f9d78d4d5e040afa408aa2c356))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([48de8c2](https://github.com/pattern-lab/patternlab-node/commit/48de8c2e134a61c0b4440375254bc9590a3e2563))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([363f22c](https://github.com/pattern-lab/patternlab-node/commit/363f22c643239ef4ca48d6f5942111604fda5ead))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([487cc78](https://github.com/pattern-lab/patternlab-node/commit/487cc783388043ec16ab1e54a3bfd8490038d058))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([571017f](https://github.com/pattern-lab/patternlab-node/commit/571017ffafa2cf6e8fa01b7ea7effc88922b05d1))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([420e829](https://github.com/pattern-lab/patternlab-node/commit/420e8293c033557ede073bc13e68955a450a3c8e))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([b4eb12e](https://github.com/pattern-lab/patternlab-node/commit/b4eb12e68ceb402964a7e303610e5b0c008876ba))
* **docs:** tiles z-index to not overlay the menu anymore ([#1370](https://github.com/pattern-lab/patternlab-node/issues/1370)) ([384dc89](https://github.com/pattern-lab/patternlab-node/commit/384dc8900ee5768f5a260fd00fe03d11ae047484))
* **docs:** update event info with tab example ([0f227a3](https://github.com/pattern-lab/patternlab-node/commit/0f227a374ee0bec02d6e9d8a3ec8735d7bb55761))
* **docs:** use "UIKits" instead of "StyleguideKits" ([#1345](https://github.com/pattern-lab/patternlab-node/issues/1345)) ([a2885ea](https://github.com/pattern-lab/patternlab-node/commit/a2885ea738c2d807dd99c6749ac6e6437d8d3e7e))
* **edition-twig:** correct uikit paths in config ([5f8d616](https://github.com/pattern-lab/patternlab-node/commit/5f8d6167cdbeb201489edc05217b96b7a1339722))
* **edition:** ignore dependencyGraph.json ([19b4268](https://github.com/pattern-lab/patternlab-node/commit/19b4268087e3bbd9fccf2d43d8376a4fc2bd9e6c))
* enable partial build via option ([8aaa533](https://github.com/pattern-lab/patternlab-node/commit/8aaa53398563ade14123c481bf509f9ee0c768f5))
* enable partial build via option ([4b9dbf9](https://github.com/pattern-lab/patternlab-node/commit/4b9dbf9095bfb8bfd2360b310dd7395dbfe3cf98))
* **engine_twig_php:** Allow additional flexibility with twig namespaces. ([07bfaa3](https://github.com/pattern-lab/patternlab-node/commit/07bfaa35a00ff62fd2016cc9f34e09cf5af36559))
* **engine_twig_php:** Pseudo patterns Twig PHP ([226aa8b](https://github.com/pattern-lab/patternlab-node/commit/226aa8bbaaf5e418530ccf54a28f6c5657ee6dea)), closes [#1045](https://github.com/pattern-lab/patternlab-node/issues/1045)
* **engine_twig_php:** Twig incremental rebuilds ([5d33f24](https://github.com/pattern-lab/patternlab-node/commit/5d33f24f156ebe50900701513a855de7de608dcf)), closes [#1015](https://github.com/pattern-lab/patternlab-node/issues/1015)
* **engine_twig_php:** Twig incremental rebuilds ([1ade945](https://github.com/pattern-lab/patternlab-node/commit/1ade9451840b2645706a0b01129e2b697dc22d4b)), closes [#1015](https://github.com/pattern-lab/patternlab-node/issues/1015)
* **engine-twig-php:** twig include function syntax not matched by findPartials ([#1472](https://github.com/pattern-lab/patternlab-node/issues/1472)) ([3677539](https://github.com/pattern-lab/patternlab-node/commit/3677539409ac41dfee71d90cc429be5c92890838)), closes [#1471](https://github.com/pattern-lab/patternlab-node/issues/1471)
* **engine-twig:** Fix package name ([58f7ec1](https://github.com/pattern-lab/patternlab-node/commit/58f7ec1e87184d760d0f72a888d7167a9e6497fe))
* **engine-twig:** twig include function syntax not matched by findPartials ([#1473](https://github.com/pattern-lab/patternlab-node/issues/1473)) ([cfa792b](https://github.com/pattern-lab/patternlab-node/commit/cfa792b2753d9f9f1840e08d55983c6c051b01fd)), closes [#1471](https://github.com/pattern-lab/patternlab-node/issues/1471)
* **event emission:** Commit failing test ([12ccbd7](https://github.com/pattern-lab/patternlab-node/commit/12ccbd729d78aabbe216021a242b26b85c75dce0))
* **event emission:** Only listen once to changes ([ea6b7d3](https://github.com/pattern-lab/patternlab-node/commit/ea6b7d304e07d09b0d760700f6e27341b4e2553e))
* fall back to seeing the current pattern's query string to `all` or the defaultPattern value if undefined when the iframe page initially loads ([a368459](https://github.com/pattern-lab/patternlab-node/commit/a3684590fca02cf96b99421b87a0ad0a711893ad))
* fix broken / missing closing HTML tag ([100ea8f](https://github.com/pattern-lab/patternlab-node/commit/100ea8f418616a8896f88897605d63b8043f1110))
* fix bug with context menu not overlapping search input on smaller screen sizes ([0b175d9](https://github.com/pattern-lab/patternlab-node/commit/0b175d9bcd6d5de2075a5562b6459d11ab76c6ef))
* fix classname typo ([da3c5f1](https://github.com/pattern-lab/patternlab-node/commit/da3c5f144d22b1ac3ad99680a264433d4438ebb2))
* fix inability to previously open / close / traverse pattern lab's navigation via keyboard ([25c9366](https://github.com/pattern-lab/patternlab-node/commit/25c93662fd476156a4ea0b2dffb8f94c6913285a))
* fix incorrect Webpack version in package.json ([9788e89](https://github.com/pattern-lab/patternlab-node/commit/9788e8977921e31fe43f2a1ec19d4684dd4709c5))
* fix issue with viewport height exceeding the space available ([95cd1cf](https://github.com/pattern-lab/patternlab-node/commit/95cd1cfa57f086ecb84ac2e996ecda81f0c6a1a6))
* fix JS paths imported ([1d7dec8](https://github.com/pattern-lab/patternlab-node/commit/1d7dec800f0c48fc06dc4e4b4acaa3d46e11a6e7))
* fix Prism.js typo so languages not found / supported don't throw a JS error ([a8c19f9](https://github.com/pattern-lab/patternlab-node/commit/a8c19f9f9b11d4abbdcd9e573fb0cb418d665660))
* fix scrolling issues with sidebar layout when nested nav sections are open; update sidebar layout to ensure viewport tools are still available on larger screens ([c7d1cda](https://github.com/pattern-lab/patternlab-node/commit/c7d1cda1bf0909db3fb2b4e4d2ba253325c8c041))
* fix Twig Edition examples by adding missing Twig namespaces to config ([b4c20ef](https://github.com/pattern-lab/patternlab-node/commit/b4c20ef88ee0d3010760584c6f05ff7f92b711a6))
* fix typo with CSS var in mixin ([fd7f2ea](https://github.com/pattern-lab/patternlab-node/commit/fd7f2eaab875199b71a4786b5b81fad27367aee3))
* fixing bug with dropdown offset since original Typeahead styles are no longer inlined ([f3e5467](https://github.com/pattern-lab/patternlab-node/commit/f3e54678448d451a9e8a219dc468d419e12e87ba))
* **get:** add internal ability to omit missing pattern warning ([e3dddc6](https://github.com/pattern-lab/patternlab-node/commit/e3dddc66a648f01987847320dd887c47eb7bc592)), closes [#786](https://github.com/pattern-lab/patternlab-node/issues/786)
* **get:** Attempt to sanitize verbosePartial into posix format ([47c9eee](https://github.com/pattern-lab/patternlab-node/commit/47c9eeeb081615835cd2a6cf69883cb1db0edd2c))
* **gulp:** remove help command ([71575db](https://github.com/pattern-lab/patternlab-node/commit/71575dbc884bbfcfeb7f8882c3affa91055996b2))
* **handlebars-demo:** move and modify the icon files ([#1377](https://github.com/pattern-lab/patternlab-node/issues/1377)) ([7c66f8a](https://github.com/pattern-lab/patternlab-node/commit/7c66f8ad4cd15e0a814f9808d0fbca727903aeb5))
* hide borders on action menu when sidebar is visible ([a2e5720](https://github.com/pattern-lab/patternlab-node/commit/a2e5720a55ea94b6977298fa613cf4e94d485082))
* hogan to handlebars migration leftovers ([#1461](https://github.com/pattern-lab/patternlab-node/issues/1461)) ([566485a](https://github.com/pattern-lab/patternlab-node/commit/566485a5c20d739bfe9c77c11b8ddfa09e292481))
* HTML structure ([#1450](https://github.com/pattern-lab/patternlab-node/issues/1450)) ([8567e2b](https://github.com/pattern-lab/patternlab-node/commit/8567e2b218a4ef9df0e359ca77229dda54712200))
* ie 11 cross browser fixes ([b3abb20](https://github.com/pattern-lab/patternlab-node/commit/b3abb202c99eba5d8dad0412fd5106cc3ffa58fc))
* **initialize:** updating no-emit-webpack-plugin dependency [#1348](https://github.com/pattern-lab/patternlab-node/issues/1348) ([#1349](https://github.com/pattern-lab/patternlab-node/issues/1349)) ([a884897](https://github.com/pattern-lab/patternlab-node/commit/a884897cf9f98b61c9bdd20acf7e079de0782f10))
* **install:** add break statements to install edition command ([3b1813c](https://github.com/pattern-lab/patternlab-node/commit/3b1813c53b65c64eb135dfb35b54ab513992521c))
* **install:** copy dependencies ([1acef87](https://github.com/pattern-lab/patternlab-node/commit/1acef874765d21e75a65a9b6cad0a0291822f804))
* **install:** use process to find package.json ([200c7cb](https://github.com/pattern-lab/patternlab-node/commit/200c7cb4f5e909d7ac88070f7ab6a07563b35f22))
* js error ([#1475](https://github.com/pattern-lab/patternlab-node/issues/1475)) ([209b9a1](https://github.com/pattern-lab/patternlab-node/commit/209b9a15871354ac4ae982d93d6be03272799005)), closes [/github.com/pattern-lab/patternlab-node/pull/1102/files#diff-9111c2e0138c935342632437be7178f25322b8f5c86431f2b85f4fe760d32980L96-R111](https://github.com//github.com/pattern-lab/patternlab-node/pull/1102/files/issues/diff-9111c2e0138c935342632437be7178f25322b8f5c86431f2b85f4fe760d32980L96-R111)
* **json_copy:** Warn on error and rethrow to caller. They may be able to recover ([4a681a4](https://github.com/pattern-lab/patternlab-node/commit/4a681a49b7d73e43f193e0e8176dacbdcedb159d))
* **lerna:** typo in config ([525a47b](https://github.com/pattern-lab/patternlab-node/commit/525a47b51fba91c1bf5b7439735f48eb7dfa073e))
* **lint:** Manually resolve final lint issues ([7cad1f1](https://github.com/pattern-lab/patternlab-node/commit/7cad1f17550391b9f49acdb18dcfa7caa643dedf))
* **lint:** Resolve lint issues ([38b96ca](https://github.com/pattern-lab/patternlab-node/commit/38b96ca863496368023edfa5c57a7bc3d261af39))
* **lint:** run code through prettier ([ca52fde](https://github.com/pattern-lab/patternlab-node/commit/ca52fded2a3cebe294aa0bfa2ea09d8694abd85e)), closes [#825](https://github.com/pattern-lab/patternlab-node/issues/825)
* **lint:** Use const instead of var ([ad1e782](https://github.com/pattern-lab/patternlab-node/commit/ad1e782ef71295eb610f56d019eaa35499fb3f85))
* **list_item_hunter:** Add async support and fix tests  ([ea69bdc](https://github.com/pattern-lab/patternlab-node/commit/ea69bdc44678ae70aeaa0cfffc2389bac386279e))
* **live-server:** testing ([#1331](https://github.com/pattern-lab/patternlab-node/issues/1331)) ([2b2e1b1](https://github.com/pattern-lab/patternlab-node/commit/2b2e1b1c2426ab578dc014ea99df520d17a7db92))
* **loadPattern:** Check proper data file paths for modification ([b7ba5b0](https://github.com/pattern-lab/patternlab-node/commit/b7ba5b0fabb137da2003f7e6fa292ed66ae5e80c))
* **logs:** Change to logLevel instead of debug ([0104deb](https://github.com/pattern-lab/patternlab-node/commit/0104debea59860ef911254da8021aa78a86e5dd4))
* **logs:** Change to logLevel instead of debug ([bbacfca](https://github.com/pattern-lab/patternlab-node/commit/bbacfcaab43a1e856834ed8a9b53e64c8716c0a7))
* **logs:** Change to logLevel instead of debug ([63fbede](https://github.com/pattern-lab/patternlab-node/commit/63fbede06483dad8a3eee06a8f09a4bdb911b5f7))
* **logs:** Trim up our logic ([fc75807](https://github.com/pattern-lab/patternlab-node/commit/fc758075be8a3c8a168d5684152704c09ebbd420))
* make sure the top-level Dropdown menus always open/close ([7a8b418](https://github.com/pattern-lab/patternlab-node/commit/7a8b418bfcbd200ef8b2802b1a07964a9995bf9f))
* manually bump package.json versions of packages published in September but with mismatched package.json versions ([98dfadf](https://github.com/pattern-lab/patternlab-node/commit/98dfadf083eacc6741a8a8d4a79ef0cf869360d2))
* minor CSS fixes + fresh prod build ([8ac2c1f](https://github.com/pattern-lab/patternlab-node/commit/8ac2c1fa1c7558ed2ac50755f599a438d682ee2a))
* misc firefox-related bug fixes and quirks, including requiring the modal-viewer JS to get further delayed to prevent JS binding issues ([62f8bdb](https://github.com/pattern-lab/patternlab-node/commit/62f8bdb599d99eea7e181bc4e07076118f535aa1))
* misc IE 11-specific UI and layout bugs ([930b619](https://github.com/pattern-lab/patternlab-node/commit/930b619dbf748cee46c2d4be5118716dd5834ed8))
* move hoist and packages config settings over to the correct JSON file; add publish config to lerna.json ([7634079](https://github.com/pattern-lab/patternlab-node/commit/7634079e6c3c6f4e7c2fd5eaa481efbd2dfada18))
* move hoist config over to the right JSON file ([7a3ee56](https://github.com/pattern-lab/patternlab-node/commit/7a3ee56d9553459912f46b343942815f51ea596f))
* move html cleaner to a more apropriate place ([8467b20](https://github.com/pattern-lab/patternlab-node/commit/8467b203c048f491b7820480820f4c55342ecaa1))
* **node16:** prevent warning on installation process ([#1352](https://github.com/pattern-lab/patternlab-node/issues/1352)) ([d58e4c6](https://github.com/pattern-lab/patternlab-node/commit/d58e4c6f2979f5e0bba9a14e17e0dbc4afc64f75))
* **nvmrc:** bump Node version ([36a917f](https://github.com/pattern-lab/patternlab-node/commit/36a917ff9cd75ff7645e054ff8ceba67371b927a))
* only allow one top level nav item to be open at a time while rendering as a dropdown menu ([409bef3](https://github.com/pattern-lab/patternlab-node/commit/409bef37165260d9b728013ac33e7aa67541c832))
* package.json to reduce vulnerabilities ([367d38f](https://github.com/pattern-lab/patternlab-node/commit/367d38fb33bf193f1955e5e70c5b5edef0af663a))
* **package:** Allow .json extension on annotations file (issue [#836](https://github.com/pattern-lab/patternlab-node/issues/836)) ([b92e62b](https://github.com/pattern-lab/patternlab-node/commit/b92e62b6d258a46487a9d6a6e1d1b123fd495ab7))
* **package:** clarify description of package ([c65611e](https://github.com/pattern-lab/patternlab-node/commit/c65611e0a94ccfa175a3ad38ba2065e3638889e6))
* **package:** fix fat-fingered dependency ([e439f4e](https://github.com/pattern-lab/patternlab-node/commit/e439f4e60d9e28ccb821efa85f69d030665e23a3))
* **package:** fix pathing and naming issues ([45583f8](https://github.com/pattern-lab/patternlab-node/commit/45583f85396a573efc3ac0cfa456826f2ea77a97))
* **package:** fix scoped package name ([6e30e6e](https://github.com/pattern-lab/patternlab-node/commit/6e30e6e93fcc6842edab0d739432e506c972a46c))
* **package:** Regenerate package.lock and upgrade patternlab-node ([93ec49e](https://github.com/pattern-lab/patternlab-node/commit/93ec49edd6b88b9a3d7322ec76034a8d407485f0))
* **package:** remove files obsoleted by monorepo ([9abb8ac](https://github.com/pattern-lab/patternlab-node/commit/9abb8ac472ca4921c81e2d8444435b4ffcc37d76))
* **package:** remove jshint ([7254a2d](https://github.com/pattern-lab/patternlab-node/commit/7254a2de36b0ad195d4fcf8ef9b2c6c0c830beac))
* **package:** remove package-lock.json ([33d25e1](https://github.com/pattern-lab/patternlab-node/commit/33d25e1a20cdbf31f06586a97a2a523b7eda317a)), closes [#897](https://github.com/pattern-lab/patternlab-node/issues/897)
* **package:** Remove two unneeded dependencies ([31d584b](https://github.com/pattern-lab/patternlab-node/commit/31d584be9dec68b7de09e30d62185da907db0987))
* **package:** Remove unneeded dependency ([438c6b1](https://github.com/pattern-lab/patternlab-node/commit/438c6b1865739ad4b234aa09c1ff145bd0e7d593))
* **packages:** Allow scoped publishing ([58beeb6](https://github.com/pattern-lab/patternlab-node/commit/58beeb6ee8a111d0caa4e2da6af138d634dc5355))
* **package:** Update gitignore and npmignore with current files ([581b3c4](https://github.com/pattern-lab/patternlab-node/commit/581b3c4f4bc2b771b8c45fdffd46898489bc3730))
* **package:** update LICENSE ([337aa32](https://github.com/pattern-lab/patternlab-node/commit/337aa32a22eab42641c087b0909d6c3bf5525399))
* **package:** update mustache dependency ([27bd4cd](https://github.com/pattern-lab/patternlab-node/commit/27bd4cd0d6b1025f32a5affc0964b02d2fffc5e8))
* **package:** update publish config and installation target ([27d2c8f](https://github.com/pattern-lab/patternlab-node/commit/27d2c8f5cdcf2c6497af5016517c0a9c66b9972c))
* **package:** update tap dependency ([2b70ff4](https://github.com/pattern-lab/patternlab-node/commit/2b70ff4f2766d6dd8189c2db1f00d31a8d28e333))
* **package:** Use [@pattern-lab](https://github.com/pattern-lab) npm org scoped live-server module ([7316d37](https://github.com/pattern-lab/patternlab-node/commit/7316d37c9556632f016194b1757da903149a722a))
* **parameter_hunter:** Consume styleModifiers again ([2f84d9c](https://github.com/pattern-lab/patternlab-node/commit/2f84d9cf4e909a1a14aab4d49f2f4ace960ee8a0))
* **parameter_hunter:** Replace algorithm ([f0be039](https://github.com/pattern-lab/patternlab-node/commit/f0be0396cc05b65347b721c0dd0e9c2892744dc5))
* **pattern graph:** move support and coverage of graph file to root ([bb9ef3c](https://github.com/pattern-lab/patternlab-node/commit/bb9ef3c4ffa12813b9580bed6308ad2790e6583e))
* **pattern watch:** Defensively add change listeners ([cdbd11f](https://github.com/pattern-lab/patternlab-node/commit/cdbd11f445bb940c377ddff89e920a0510d8f5c8))
* **pattern_engines:** Support PatternEngine as a local symlink ([a45b27c](https://github.com/pattern-lab/patternlab-node/commit/a45b27c0c7e63bca11f147a025adbfdcc60292c8))
* **patternflyouts:** preventing horizontal scrollbar in pattern flyouts in Edge 18 [#1124](https://github.com/pattern-lab/patternlab-node/issues/1124) ([63300bc](https://github.com/pattern-lab/patternlab-node/commit/63300bc00ee797e38bfdb73fdc7694c188a423dc))
* **patterns:** find all patterns inlcuding pseudo patterns ([d0672f6](https://github.com/pattern-lab/patternlab-node/commit/d0672f65e7f35616621f9ebc7d703905b697a6a2)), closes [#975](https://github.com/pattern-lab/patternlab-node/issues/975)
* **patternstate:** added css color for pattern state "inprogress" [#1216](https://github.com/pattern-lab/patternlab-node/issues/1216) ([856bcda](https://github.com/pattern-lab/patternlab-node/commit/856bcda150239928bb5e8719246b97e9fa366468))
* **plugin-tab:** bump lodash from 4.17.5 to 4.17.15 in /packages/plugin-tab ([#1081](https://github.com/pattern-lab/patternlab-node/issues/1081)) ([3f89dda](https://github.com/pattern-lab/patternlab-node/commit/3f89dda1685874e251f9777f969c0943e0080881))
* **plugin-tab:** defensively call addPanels ([b82bd12](https://github.com/pattern-lab/patternlab-node/commit/b82bd129fdbe48de95b62d75fb7fe95cea896b7e))
* **plugin-tab:** handle params correctly ([d248993](https://github.com/pattern-lab/patternlab-node/commit/d2489939bb0db1a1d67b0e7f47dfb1838b88b0a0))
* **plugin:** correct spelling error and function locations ([d4abd88](https://github.com/pattern-lab/patternlab-node/commit/d4abd88cb017550002407241b5045a2ad1adb1dc))
* **plugins:** support scoped packages ([44f0f8e](https://github.com/pattern-lab/patternlab-node/commit/44f0f8e421ad7f9f5ae8f6f8ef771da2875700c5))
* **plugintabs:** enabling multiple file formats [#1163](https://github.com/pattern-lab/patternlab-node/issues/1163) ([bb5e817](https://github.com/pattern-lab/patternlab-node/commit/bb5e8179e6b8553a6e1af0bede26db412b6c0b68))
* **polyfill:** Remove classList reference ([f0978da](https://github.com/pattern-lab/patternlab-node/commit/f0978dabc56a20567e7840d6f67a1965c4939e0f))
* port over missing UIKit Sass that wasn't added in the original PR ([f7659e6](https://github.com/pattern-lab/patternlab-node/commit/f7659e64d0eee13be20921dd5afc48ac20ae93e6))
* **postinstall:** fix typo in name ([a1a9779](https://github.com/pattern-lab/patternlab-node/commit/a1a97799dea15e8ef6836f7a527e081644c73a50))
* Prettier should only format .js files ([7997a02](https://github.com/pattern-lab/patternlab-node/commit/7997a027588f1935801310f36d080e419b494d5b))
* **prettier:** add precommit and prettier commands ([aead343](https://github.com/pattern-lab/patternlab-node/commit/aead343c2ad2bf9a37ca07df58d6b2b9e73af0b3))
* **prettier:** Attempt to ignore package files ([e6c08bf](https://github.com/pattern-lab/patternlab-node/commit/e6c08bf0f3aa0afcef0a722789c82768f3fc038a))
* **prettier:** fix prettierignore paths ([a0f752c](https://github.com/pattern-lab/patternlab-node/commit/a0f752c699e6dfd2df1a24d5a2d155716256bd22))
* **processRecursive:** Fix async AND! recursive partial inclusion ([a759443](https://github.com/pattern-lab/patternlab-node/commit/a759443b2a41ab30db9a034169243666e50de8c4))
* **pseudopattern_hunter:** Copy base and variant data safely ([2c8592a](https://github.com/pattern-lab/patternlab-node/commit/2c8592ae521cdf6aea3f2894307bee2bddd65698)), closes [#711](https://github.com/pattern-lab/patternlab-node/issues/711)
* **pseudopattern)hunter:** Add failing test ([07b3f02](https://github.com/pattern-lab/patternlab-node/commit/07b3f0284ca362cad3f9c8b3d800e7a0459aac70))
* **pseudopatterns:** use the template instead of the pseudo data file for template rendering [#1308](https://github.com/pattern-lab/patternlab-node/issues/1308) ([#1312](https://github.com/pattern-lab/patternlab-node/issues/1312)) ([7ecca69](https://github.com/pattern-lab/patternlab-node/commit/7ecca69bcfed4060d17390b76562e5f468b4a897))
* re-add popstate listener ([6dbbd6a](https://github.com/pattern-lab/patternlab-node/commit/6dbbd6aae3709cc17544c12dd10588120eb9e71a))
* re-enable displaying the top level `All` link if PL isn't configured to hide this specific link in the ishControlsHide config option. Addresses [#1048](https://github.com/pattern-lab/patternlab-node/issues/1048) ([6bb4e1a](https://github.com/pattern-lab/patternlab-node/commit/6bb4e1ac6f38b47f93030c8c5bca62d5db2132e4))
* re-enable using the defaultPattern config for the initial iframe page load if defined ([d645ea1](https://github.com/pattern-lab/patternlab-node/commit/d645ea15150061d7ad13741d2dc37b12b9786411))
* re-try Netlify preview to debug local vs prod rendering differences ([6da41a1](https://github.com/pattern-lab/patternlab-node/commit/6da41a14feea034f891c745dfeb062fa3b196235))
* **README:** Add scoped package to install instructions ([f8ac828](https://github.com/pattern-lab/patternlab-node/commit/f8ac828819bb23eecd0ae08ae69f64530f9f2d99))
* **README:** Fix broken link and whitespace ([9203c16](https://github.com/pattern-lab/patternlab-node/commit/9203c16b99f92dd47e0785e4e12d6c04a8dd340c))
* **README:** Fix npm link instructions ([ce3a7f0](https://github.com/pattern-lab/patternlab-node/commit/ce3a7f0922b363a50ec5ac9894fbb21352f1cb6d))
* **README:** fix scoped package name ([a4e82de](https://github.com/pattern-lab/patternlab-node/commit/a4e82def5e9156c2cf6ce2f9d0675bf12059b699))
* **README:** Fix typos ([b3d1846](https://github.com/pattern-lab/patternlab-node/commit/b3d18463f4dc748d9c213f17171acb674af02d59))
* **README:** update content for consistency ([4edf0d4](https://github.com/pattern-lab/patternlab-node/commit/4edf0d49b914276f66fddaaa7d1cfe815d47015e)), closes [#815](https://github.com/pattern-lab/patternlab-node/issues/815)
* **README:** update installation command ([026e810](https://github.com/pattern-lab/patternlab-node/commit/026e8102a987e9f8e6985832d93167c481ed9739))
* **README:** Update npm shield to point to scoped package ([1f62617](https://github.com/pattern-lab/patternlab-node/commit/1f62617bc667e882caeed08f577528750e286a78)), closes [#760](https://github.com/pattern-lab/patternlab-node/issues/760)
* **README:** Update shield & install instructions to point to scoped pkg ([f9bc085](https://github.com/pattern-lab/patternlab-node/commit/f9bc08550def191780561fc1f3503781d40992c7))
* regenerate fresh UIKit build after fixing main JS issues ([9ea34d2](https://github.com/pattern-lab/patternlab-node/commit/9ea34d2efe43cafacb3729ac113121ba51126344))
* remove anti-pattern of removing scrollbars on accordions — prevents users from knowing content is scrollable. also fix accessibility in global PL navigation which had been preventing full keyboard navigation ([cc9bf02](https://github.com/pattern-lab/patternlab-node/commit/cc9bf0260c949267eaa98cbd363603dc552f8cda))
* Rename Handlebars and Nunjucks extension setting to "extend" ([74e5af2](https://github.com/pattern-lab/patternlab-node/commit/74e5af28c4e714fdfc1db535b94c52f3dc14a3a4))
* **render:** Defensively set extendedTemplate as a last resort ([7a37158](https://github.com/pattern-lab/patternlab-node/commit/7a371586b3b004d5a6098ac1217471660d9e38cb))
* **replaceParameter:** Support unescaped replacement ([019c6c4](https://github.com/pattern-lab/patternlab-node/commit/019c6c4276b6d713cc1fe4fb01639667c780302c))
* **resetcss:** selector in uikit-workshop [#1109](https://github.com/pattern-lab/patternlab-node/issues/1109) ([6893b7c](https://github.com/pattern-lab/patternlab-node/commit/6893b7cb5478309d4fdab0121edba3921718bd69))
* revert fixing prettier issues with annotations.js file to fix failing tests ([962020b](https://github.com/pattern-lab/patternlab-node/commit/962020b0acabfa62f8aeac964e18bef8f56ce3fe))
* revert previous uikit configurable path updates to unblock Twig renderer work getting merged in ([42bfe29](https://github.com/pattern-lab/patternlab-node/commit/42bfe29aeaa68b956110f3b7fe88d6395cf98286))
* **script:** remove quotes around starterkit ([e4897fb](https://github.com/pattern-lab/patternlab-node/commit/e4897fb6e4d4cd0985ab72397abd03ff04be514b))
* **serve:** Reference events by constants ([9f5c143](https://github.com/pattern-lab/patternlab-node/commit/9f5c143374f027092b4d585f1bdcec53250da737))
* **server:** remove setInterval hack ([a76e4a2](https://github.com/pattern-lab/patternlab-node/commit/a76e4a247f21262e90218ae0a2154cfa181b5875))
* **serve:** Throttle liveserver startup. Safely call reload ([bf8962e](https://github.com/pattern-lab/patternlab-node/commit/bf8962e4d444d5ff6f0ee182b76068454a4efccb))
* simplify overflow fix ([378cf42](https://github.com/pattern-lab/patternlab-node/commit/378cf4282a3e5b4f597287eb538270e3358c8c69))
* small tweak to capitalize nav items in the menu ([e23f081](https://github.com/pattern-lab/patternlab-node/commit/e23f081b04c6720d8421d6d18ca9145c904b59a2))
* small UI fixes for the sticky Tabs header on smaller screens + drawer content collapsing on smaller screens + better handling of Nav link cleanup when changing pages ([347e2fe](https://github.com/pattern-lab/patternlab-node/commit/347e2fe29a78a1d168005a07c656b4f9f1124c7f))
* squashing minor UI bugs ([a8a606c](https://github.com/pattern-lab/patternlab-node/commit/a8a606cfb224f7041f53ff5026a84e13fa17914c))
* **starterkit-twig-demo:** add macro Twig namespace ([8694ff3](https://github.com/pattern-lab/patternlab-node/commit/8694ff38ebb696f3b70578ac8148cfa6be4e2e69))
* **starterkit-twig-demo:** mv source dist so it can be installed ([bd0d64e](https://github.com/pattern-lab/patternlab-node/commit/bd0d64e27bdf317306f35f932b5cc9f6c64c6634))
* **starterkit-twig-demo:** pages not rendering pattern-specific data from json ([#1490](https://github.com/pattern-lab/patternlab-node/issues/1490)) ([1c878df](https://github.com/pattern-lab/patternlab-node/commit/1c878dfa35d549f23e199b3e235ff79cb471ac86)), closes [#1486](https://github.com/pattern-lab/patternlab-node/issues/1486)
* **starterkit:** add css output and build command ([ccb2d35](https://github.com/pattern-lab/patternlab-node/commit/ccb2d3569b741220324a3fa738ab3d4d2eb97ffe))
* **starterkit:** remove config file ([f90e38a](https://github.com/pattern-lab/patternlab-node/commit/f90e38aa873dcff0dd08fe4dabc3b71bf95080b6))
* **starterkit:** use handlebars meta files ([d8f5e12](https://github.com/pattern-lab/patternlab-node/commit/d8f5e12471bd783bd3755626701ecc17669fc761))
* **styleguide:** port ishConfig hotfix ([8343f18](https://github.com/pattern-lab/patternlab-node/commit/8343f1822c368d84100d266e4a509d2e371021c2))
* subitems menu height restricted only for horizontal mode ([#1492](https://github.com/pattern-lab/patternlab-node/issues/1492)) ([e65f294](https://github.com/pattern-lab/patternlab-node/commit/e65f294d9cbf032fd7fd03d9f957500949db5440))
* temp workaround to address instance where the latest version of Edge supports ES modules but NOT Custom Elements ([ada3d82](https://github.com/pattern-lab/patternlab-node/commit/ada3d829019345fd33ed949f306972efdcb4fa57))
* temp workaround to fix content exceeding the height of drawer container ([435243c](https://github.com/pattern-lab/patternlab-node/commit/435243cbfbd000a7d96a0e9fa7beff1a988ede64))
* temporarily disable Random and Disco viewport controls until the full JS logic for these is re-enabled ([14b9a19](https://github.com/pattern-lab/patternlab-node/commit/14b9a19e4dee9462f3784eae28066893cc893624))
* temporarily downgrade Preact version so tooltip used for displaying viewport sizes renders correctly ([52dcf85](https://github.com/pattern-lab/patternlab-node/commit/52dcf85e756ee171ca993288d98f5b5ef9a0a24b))
* temporarily revert using twig-based UI for certain bits of rendering PL to get the Twig renderer back up and running ([a408bbc](https://github.com/pattern-lab/patternlab-node/commit/a408bbc2cdc9c1759aa7251f858b29a5571d0d4c))
* **test configuration:** Remove vestigial configuration entries ([481fce9](https://github.com/pattern-lab/patternlab-node/commit/481fce94ddfd44d34ddf6555f4d199bf63ec8c15))
* **test:** Address another batch of tests ([8c43526](https://github.com/pattern-lab/patternlab-node/commit/8c43526173306fc5e8178f93adad5b43d5b25c9a))
* **test:** Fix all tests except what looks like a legitimate failure ([1dfa911](https://github.com/pattern-lab/patternlab-node/commit/1dfa911a336fee112e9dbb25abd50b2f03325280))
* **test:** Fix test mock ([e0b9143](https://github.com/pattern-lab/patternlab-node/commit/e0b914376755054757fcb269637b161144c440f9))
* **test:** fix the test please and thank you ([cdc6c38](https://github.com/pattern-lab/patternlab-node/commit/cdc6c3867afb5a1d746c37c0ae0af2bc8040df93))
* testing potential FF fix for https://github.com/pattern-lab/patternlab-node/issues/1100 ([613bba1](https://github.com/pattern-lab/patternlab-node/commit/613bba104f2082be507938db78f1db7a07f6b8be))
* **tests:** bump lerna ([886220e](https://github.com/pattern-lab/patternlab-node/commit/886220e40530ee26be12c05caab7931855748ac9))
* **tests:** change test command name similar to live-server until this passes CI ([5c39be1](https://github.com/pattern-lab/patternlab-node/commit/5c39be1328f0533827f5de38286073367b9483df))
* **tests:** exclude tests from code coverage ([288ccaa](https://github.com/pattern-lab/patternlab-node/commit/288ccaa91eacfbdeca6f422f82073a251ad9062d))
* **tests:** Fix broken import ([f0f61cb](https://github.com/pattern-lab/patternlab-node/commit/f0f61cb007b0b0af2fb58bd923bfc9ae816e9a15))
* **tests:** Fix tests across many files ([450b586](https://github.com/pattern-lab/patternlab-node/commit/450b586227c31b01f733b233e3da12bbf134afe0))
* **tests:** fix ui_builder test mocking ([02b3598](https://github.com/pattern-lab/patternlab-node/commit/02b35981c96f9c5f6995f7de4c53a7bcefc7ffc9))
* **test:** sledgehammer a test ([8b34be0](https://github.com/pattern-lab/patternlab-node/commit/8b34be0a39b1ec499d454304db33229175fd675f))
* **tests:** prevent dependency graph output file from being written ([0d9c57e](https://github.com/pattern-lab/patternlab-node/commit/0d9c57ebe44ad5858668cc8453a973e033c8f3ed))
* **tests:** Revert annotations file back to expected legacy format ([3618f27](https://github.com/pattern-lab/patternlab-node/commit/3618f27bc32aaf7c3b0f6da60d746e7274d07ff8))
* **tests:** Revert annotations file back to expected legacy format ([7313683](https://github.com/pattern-lab/patternlab-node/commit/73136837f95f1470e1f49789486ee81ec56facea))
* **tests:** Revert annotations file back to expected legacy format ([653f021](https://github.com/pattern-lab/patternlab-node/commit/653f0216c52b343f9a1989102f696b87e177627d))
* **tests:** scope the addition of each engine to only core ([cfd346c](https://github.com/pattern-lab/patternlab-node/commit/cfd346c1a2c00fe1c5e58c4f620d7ef8de5e260d))
* the namespace notation should not be mixed with PatternLab shorthand pattern naming & name is not defined in the textarea macro ([8250fe8](https://github.com/pattern-lab/patternlab-node/commit/8250fe88231d03735424d597eae40496da2cb48c))
* transformed asset types is ignored ([#1426](https://github.com/pattern-lab/patternlab-node/issues/1426)) ([8cbe189](https://github.com/pattern-lab/patternlab-node/commit/8cbe189d45afaa753ce6de41bdd9de1596e074f3)), closes [#1339](https://github.com/pattern-lab/patternlab-node/issues/1339)
* **travis:** Add global lerna install during CI ([1fea333](https://github.com/pattern-lab/patternlab-node/commit/1fea33303ef7869b17594b2835ae4bed2596bd53))
* tweak header and drawer padding when viewing on a device with curved edges ([98e9baf](https://github.com/pattern-lab/patternlab-node/commit/98e9baf649eceb9124218a924b6b08097b910e86))
* **twig engine:** startup and running problems ([#1478](https://github.com/pattern-lab/patternlab-node/issues/1478)) ([e5a1904](https://github.com/pattern-lab/patternlab-node/commit/e5a19049f083315939406677b1c0480f4b420569))
* twig logo is rendered as "NaN" ([#1434](https://github.com/pattern-lab/patternlab-node/issues/1434)) ([ab6b133](https://github.com/pattern-lab/patternlab-node/commit/ab6b133019d9dfa3816e8fc9a9caa7b547e19097)), closes [#1407](https://github.com/pattern-lab/patternlab-node/issues/1407)
* **twig:** starter-kit-twig urls are incorrect on npm ([#1297](https://github.com/pattern-lab/patternlab-node/issues/1297)) ([4256d6b](https://github.com/pattern-lab/patternlab-node/commit/4256d6b13f9c2cfadf7620b0cb744cf71c3257f5))
* **ui:**  fix keyboard shortcut for M link ([b4286ca](https://github.com/pattern-lab/patternlab-node/commit/b4286ca96a19bfc17df68f32895d16b8b0481f35))
* uikit fixes and minor CSS updates intended for the v5.3.0 release ([26c4ced](https://github.com/pattern-lab/patternlab-node/commit/26c4ceddaae09fa4fa4873f092c924274498c5da))
* **uikit-workshop:** add template files to published bundle ([9005fce](https://github.com/pattern-lab/patternlab-node/commit/9005fcee9e129fb41d509f706195e1437bddc710))
* **uikit-workshop:** add webpack config to published bundle ([060a573](https://github.com/pattern-lab/patternlab-node/commit/060a573cbddce9ee3d270d39337d0c8cac8372fa))
* **uikit-workshop:** fix merge problem ([d245b3b](https://github.com/pattern-lab/patternlab-node/commit/d245b3bca044c29f281052bf2feb95eeffafcf6b))
* **uikit:** clear out "404" responses when loading tabs ([73874b1](https://github.com/pattern-lab/patternlab-node/commit/73874b1b0b66ca6425c2b74331d417efdb529e2e))
* **uikit:** correct ishViewportRange logic ([365c626](https://github.com/pattern-lab/patternlab-node/commit/365c6267dcceede94dc1e26d47eae89250cb65f4))
* **uikit:** remove indent from code panels ([e263fb0](https://github.com/pattern-lab/patternlab-node/commit/e263fb002250eda8badb31e951d600ebe29348af))
* **uikits:** fix generation of view all pages within uikits ([7d6bdce](https://github.com/pattern-lab/patternlab-node/commit/7d6bdce1b380da15621db27958c57f4b576526db))
* **uikits:** fix ui_builder_tests ([e75f434](https://github.com/pattern-lab/patternlab-node/commit/e75f4348633457bdaa3e90bbac22c194285fcbe7))
* **uikit:** uikit no longer requires being in the root directory ([911ff06](https://github.com/pattern-lab/patternlab-node/commit/911ff0610a1b40742c8e91ee23a0cdb9a9360a02))
* **uikitworkshop:** preventing cropping pattern parts [#1174](https://github.com/pattern-lab/patternlab-node/issues/1174) ([6a67d03](https://github.com/pattern-lab/patternlab-node/commit/6a67d039048129e9837c3b6eb3e195ed2e86a815))
* **unit test:** Fix path to fixture ([b932f14](https://github.com/pattern-lab/patternlab-node/commit/b932f1415091ca6597e572cdbf0ae3bf583f99d1))
* **unit tests:** change verbose partial paths. not sure if this is a good idea. ([6fe9785](https://github.com/pattern-lab/patternlab-node/commit/6fe9785c8c46567e09043cd3f396f8d6e0a5cdab))
* **unit tests:** Fix more tests ([9f3c4c9](https://github.com/pattern-lab/patternlab-node/commit/9f3c4c9ab7902e92c5d88e08be757da730626238))
* **unit tests:** Fix more tests. Since we no longer render, no need to look for escaped values ([c50484d](https://github.com/pattern-lab/patternlab-node/commit/c50484d2163bb9983be9447de54e3f5406b5ea79))
* **unit tests:** Fix test ([2c6db20](https://github.com/pattern-lab/patternlab-node/commit/2c6db20e6183adc0f81331e8f1fdb1bf723a2764))
* **unit tests:** Fix tests ([cf0aaa5](https://github.com/pattern-lab/patternlab-node/commit/cf0aaa540cae6d39d2f1a0643cbd66f7f18d700c))
* **unit tests:** Fix tests ([4b14e5d](https://github.com/pattern-lab/patternlab-node/commit/4b14e5d9b10fee3305146d42e73a85952acaa995))
* update annotation style to display consistently in browser UI -- display inline isn't centered as expected for example. ([8449b1a](https://github.com/pattern-lab/patternlab-node/commit/8449b1a59abcf20b68cde4346cc6846c98df7bce))
* update autoprefixer browserslist config to address warning messages ([5e52f2b](https://github.com/pattern-lab/patternlab-node/commit/5e52f2b0ed02e2002ca867368636c3c0dc79ff0a))
* Update dependency on twing JS engine ([cfe88c6](https://github.com/pattern-lab/patternlab-node/commit/cfe88c6cdbf2219b9955eaa0ffcfc0e4a7683511))
* update drawer UI to not collapse content on smaller screen sizes ([7147085](https://github.com/pattern-lab/patternlab-node/commit/71470856b8b389421348366afd247a599d1e9c86))
* update globally installed version of Lerna on Travis to match local version ([125b111](https://github.com/pattern-lab/patternlab-node/commit/125b1117f881177cd72b7e1410c7f74b8ddb6562))
* update header styles to less-frequently wrap nav links to multiple lines ([ba0ca74](https://github.com/pattern-lab/patternlab-node/commit/ba0ca74f05eed6ed47db22e4a9451d8286f2e482))
* update iframe resizer broken path in UIKIt ([875573e](https://github.com/pattern-lab/patternlab-node/commit/875573eab6dd7a08e431e4dccc2c060e286323a4))
* update iframe resizer UI to be hidden when iframe is full width ([9797c1a](https://github.com/pattern-lab/patternlab-node/commit/9797c1a047d746d21b88a1f57b57f618a03a54df))
* update initial PL iframe path default ([a26fbb9](https://github.com/pattern-lab/patternlab-node/commit/a26fbb956e13901d1751c435b76de65637191ca4))
* update ish-controls to be vertically centered in the global PL header by default ([f75de74](https://github.com/pattern-lab/patternlab-node/commit/f75de74259521eefa5811ca2397bed3373d5f4ba))
* update Javascript to address merge conflict issue with previous PR merge / recent release ([cf2ecc1](https://github.com/pattern-lab/patternlab-node/commit/cf2ecc154383c3e8abd56dc88484370bc58ac30b))
* update Lerna to latest version; update bootstrap command to use local version of Lerna so bootstrapping works as expected ([f864da2](https://github.com/pattern-lab/patternlab-node/commit/f864da2c12c135a8691382c3eef25a77afcdd944))
* update link to new PL docs homepage ([831b467](https://github.com/pattern-lab/patternlab-node/commit/831b467c57b9259c32ce3d3ddf366fe1867a48a9))
* update native shim import path ([2959b93](https://github.com/pattern-lab/patternlab-node/commit/2959b938462c5afce15dc7066d5a604d75d13434)), closes [/github.com/sghoweri/patternlab-node/commit/72c0168bc4e3621f882c51ad61e32528694b4ad6#diff-d93f7a4be35cabaf5729f725702a9280](https://github.com//github.com/sghoweri/patternlab-node/commit/72c0168bc4e3621f882c51ad61e32528694b4ad6/issues/diff-d93f7a4be35cabaf5729f725702a9280)
* update package.json description in `@pattern-lab/uikit-polyfills` ([22fc44a](https://github.com/pattern-lab/patternlab-node/commit/22fc44a4b3683753a469a98abfcdad8f1234f28a))
* update package.json with missing custom elements packages ([e52e06e](https://github.com/pattern-lab/patternlab-node/commit/e52e06e2879f1f860ce83e0ce8f9af53f7f00cdc)), closes [/github.com/sghoweri/patternlab-node/commit/72c0168bc4e3621f882c51ad61e32528694b4ad6#diff-e756faf6983689c170147ebe05d614d4](https://github.com//github.com/sghoweri/patternlab-node/commit/72c0168bc4e3621f882c51ad61e32528694b4ad6/issues/diff-e756faf6983689c170147ebe05d614d4)
* Update packages/engine-twig-php/lib/engine_twig_php.js ([c67d50e](https://github.com/pattern-lab/patternlab-node/commit/c67d50ebb5d69816b7514e85f129f8ecde984ad3))
* update PL code viewer to open and resize as expected + animate much more performantly using CSS transforms; update existing JS logic to clean up inlined CSS styles when closing PL modal / code viewer panel ([a5be07b](https://github.com/pattern-lab/patternlab-node/commit/a5be07bb9a63773bbd9b640883f5607a58f0891e))
* update PrismJS import ([564da7a](https://github.com/pattern-lab/patternlab-node/commit/564da7ac5ed3ba2204c6aa7743eb9b78f77efe58))
* update query selector to fail properly if Hogan template hadn't yet rendered when this fires off ([a2d77c7](https://github.com/pattern-lab/patternlab-node/commit/a2d77c76f5a2fd188398cec1787b5e414e819a14))
* update sidebar breakpoint to match breakpoints used in other components ([541ca3a](https://github.com/pattern-lab/patternlab-node/commit/541ca3a632a15198f77fe359b74a3c5d06d1cad6))
* update styles for pattern state dots ([7728acc](https://github.com/pattern-lab/patternlab-node/commit/7728accc9a6e5cd83be451f7d74e522dfe721cad))
* update the default pattern that displays in the Handlebars demo ([ff1d85f](https://github.com/pattern-lab/patternlab-node/commit/ff1d85f2852fc4f210841e8e0aaf14b55165ce58))
* update the keyboard combo used to auto-focus on the uikit search input to now use command + shift + f vs the browser-specific command + f combo ([8490afc](https://github.com/pattern-lab/patternlab-node/commit/8490afcc5c15f4eda4102dafcc233b1f73453283))
* update twig-renderer ([46f53b7](https://github.com/pattern-lab/patternlab-node/commit/46f53b79f8bb0bb64a9c55fd32f29459cea6e28c))
* update typeahead selector so styles work as expected ([da13765](https://github.com/pattern-lab/patternlab-node/commit/da137657bea7561a9bdf7ef2d0da4761a91fc253))
* update viewport CSS to prevent JS from exceeding the maximum size of the page; update to account for vertical vs horizontal layouts ([c0fcd6f](https://github.com/pattern-lab/patternlab-node/commit/c0fcd6f468671212930a5d4c7b534b9d4180d356))
* update Viewport Size toggle to better handle async-loaded ishControl data + prevent rendering errors ([b937706](https://github.com/pattern-lab/patternlab-node/commit/b93770669c6f723128ba68e522c9398cc1d2d70c))
* update Webpack config public path + add to default Webpack config options that can get overwritten via the cosmic config file in place ([b047cba](https://github.com/pattern-lab/patternlab-node/commit/b047cba8e7dbed0d5d7675a78a1cd11e2ef28915))
* update Webpack config to point to the patched version of preact-dom ([d3660b7](https://github.com/pattern-lab/patternlab-node/commit/d3660b78bc0a74c52ed85b69b023c612b789c318))
* update yarn.lock ([dca1948](https://github.com/pattern-lab/patternlab-node/commit/dca19489b85f715de3ade2294fa49df89b8bb59f))
* updated base template to handlebars ([#1463](https://github.com/pattern-lab/patternlab-node/issues/1463)) ([c69c658](https://github.com/pattern-lab/patternlab-node/commit/c69c658d06dab9a1bf04f77e7902ff3f07c94c3e))
* Updated the README to reflect which issues are resolved. ([d90c3c4](https://github.com/pattern-lab/patternlab-node/commit/d90c3c4605f9a5bcd1153996e3f4d1a17d58bd92))
* updates to address eslint / prettier issues ([d945acc](https://github.com/pattern-lab/patternlab-node/commit/d945acc13b8e4e36f3815b017fbc12266c323d1f))
* updates to fix eslint / prettier issues; update packages/core to reuse root .eslintrc.js file ([5b7a057](https://github.com/pattern-lab/patternlab-node/commit/5b7a057d46ccd16b5832af1441030c7b76f237a8))
* use 100% of the screen available when JS is disabled / the first time the iframe loads up ([c0c5bff](https://github.com/pattern-lab/patternlab-node/commit/c0c5bff7a63b157d5b81dc2bcecee9e732ecfd4e))
* version bump the PL gulp edition package that was also out of sync with the latest version published to NPM ([fb8b425](https://github.com/pattern-lab/patternlab-node/commit/fb8b425015ff4aef359459e836e7c2b77cf95ed7))
* **version:** use static core method getVersion ([f9dcd4d](https://github.com/pattern-lab/patternlab-node/commit/f9dcd4d4a8c1ab31202b4e723788c8fba72a059e))
* **viewall:** fix viewall generation ([543558a](https://github.com/pattern-lab/patternlab-node/commit/543558a692d4db04b7d29f11f940cfd67ae25a6a))
* visually hide NavToggle icon text; fix for visual regression after merging down https://github.com/pattern-lab/patternlab-node/pull/1227 ([3a2ad9f](https://github.com/pattern-lab/patternlab-node/commit/3a2ad9f12d83b6d21dcca62e89d944a6a46342f6))
* **watchPatternLabFiles:** Register and manager watchers ([48f0190](https://github.com/pattern-lab/patternlab-node/commit/48f0190078b795925d7f5ec3278247232899ed55))
* **watch:** wire up serve and watch listeners correctly ([04cd18e](https://github.com/pattern-lab/patternlab-node/commit/04cd18e2439f9d44ef1540f3722ea82a7f623c5e))
* **wording:** reconcile Pattern Lab vs PatternLab ([f3d1e0d](https://github.com/pattern-lab/patternlab-node/commit/f3d1e0d807584ffbbbf2ea5869af7b916f25bbc8))
* workaround fix for the PL UIKit viewport resizer width occasionally getting stuck with a width of 0px in Safari and Firefox when the JS is initially booting up ([64c971d](https://github.com/pattern-lab/patternlab-node/commit/64c971d7848eca62f478b3d66899b6f1737a6aa4))
* workaround to address the pl-search autocomplete not displaying results the first time the component is focused ([95a4e71](https://github.com/pattern-lab/patternlab-node/commit/95a4e71f56b2122fa9a1c3dcdd48c5e58426a5e3))


### Features

* 1st pass wiring up automatic critical CSS generation to UIkit ([7a982d6](https://github.com/pattern-lab/patternlab-node/commit/7a982d665315ea8bac88ff6dd1772130a1c55f34))
* activate prettier for scss ([#1468](https://github.com/pattern-lab/patternlab-node/issues/1468)) ([fac6ad4](https://github.com/pattern-lab/patternlab-node/commit/fac6ad4be48c95eccfe890a280cad441ee84f677))
* add <pl-toggle-layout> component ([65b1177](https://github.com/pattern-lab/patternlab-node/commit/65b1177e5a55fb46355cea018712bea86da66e5e))
* add <pl-toggle-theme> component ([a04bade](https://github.com/pattern-lab/patternlab-node/commit/a04bade6259e49b176aa7c2ba4142dfbdd975051))
* add lit-element, basic Typescript support to Webpack ([611f705](https://github.com/pattern-lab/patternlab-node/commit/611f705be85eea8a31091169750d64e988798cee))
* add local copy of new Slotify library till published to NPM ([63b9d83](https://github.com/pattern-lab/patternlab-node/commit/63b9d833908151ce5cb5aa5184c72254125c7ed1))
* add localstorage support to redux store ([3d6a834](https://github.com/pattern-lab/patternlab-node/commit/3d6a8345a66880b0fb9128dae4bd54494979b36f))
* add new <pl-button> component to make Button-like styles more reusable ([5e7b014](https://github.com/pattern-lab/patternlab-node/commit/5e7b0140622eb89154c38925769a6def6d669fb3))
* add new <pl-icon> component ([e8ce2a9](https://github.com/pattern-lab/patternlab-node/commit/e8ce2a927365b8d5316a7d8229c979ff31b04907))
* add Preact-powered base component extended by other components ([dd1ac7e](https://github.com/pattern-lab/patternlab-node/commit/dd1ac7ef24fef156dcb4321330bdf821eceb11d1))
* add support for auto-closing Nav when clicking inside of the rendered iframe ([9d602fe](https://github.com/pattern-lab/patternlab-node/commit/9d602fe335a5d3b5bca5cac258c2465934d9a46a))
* add support for optional chaining syntax via Babel plugin ([c8886b6](https://github.com/pattern-lab/patternlab-node/commit/c8886b6d9d91fea246fa3ab7947f289509dc26d5))
* add the ability to disable Pattern Lab viewall links in the navigation ([156e609](https://github.com/pattern-lab/patternlab-node/commit/156e609a92e7f7e7ebd8f4f5cd77b5d695db8bad))
* add wrapping <pl-layout> component that responds to state changes by the <pl-toggle-theme> and <pl-toggle-layout> components ([2141ad7](https://github.com/pattern-lab/patternlab-node/commit/2141ad7c739d5f89af59f145974b8d2cdfc46b22))
* added https description to the docs ([#1355](https://github.com/pattern-lab/patternlab-node/issues/1355)) ([4118f74](https://github.com/pattern-lab/patternlab-node/commit/4118f740810842b16cf86b9ee28bda2a623aa9c7))
* **api:** expose getVersion statically ([4683cd0](https://github.com/pattern-lab/patternlab-node/commit/4683cd00ae493be18d08a29e2ff370b70928c9de))
* **API:** remove reliance on patternlab object during plugin install ([0850fd6](https://github.com/pattern-lab/patternlab-node/commit/0850fd6909ac1939a89be9840fbfa7d64fdda56d))
* **API:** standardize v() and version() into a single call ([6309e69](https://github.com/pattern-lab/patternlab-node/commit/6309e693b0971ea26c86e0e2b957ba413492e1b7))
* clean html at rendering ([f6becee](https://github.com/pattern-lab/patternlab-node/commit/f6becee53786f5bd829c96eda1a1d69ade60a05a))
* clean up UI controls in the light theme ([cd37c29](https://github.com/pattern-lab/patternlab-node/commit/cd37c293f534acbe0dcf6b8da6831701f4244881))
* **cli:** if starterkit has pl config, deep merge it in ([cd91786](https://github.com/pattern-lab/patternlab-node/commit/cd9178675a906d9f1d46815233db70cd3ae258ac))
* **cli:** make options more user friendly ([ad845b3](https://github.com/pattern-lab/patternlab-node/commit/ad845b394ef81f90895ebb5bc6f12cc608e5e3d4))
* **cli:** Rename package ([9ea40d4](https://github.com/pattern-lab/patternlab-node/commit/9ea40d4a8f35247a3995ce20fad5e716b582ee10))
* **CODEOWNERS:** add additional owners ([03933f7](https://github.com/pattern-lab/patternlab-node/commit/03933f71303abd46d3cf90a409500484b73718db))
* **config:** add new default pattern export options ([a7487a0](https://github.com/pattern-lab/patternlab-node/commit/a7487a0681cb11e6f3c5c8eaefd62e5648ad5ea3))
* **config:** add uikits config ([64c2e9f](https://github.com/pattern-lab/patternlab-node/commit/64c2e9f72b3b0fea5541c4fe9d1e4d7659f6d5c2))
* **config:** Alphabetize and set defaults for patternlab-config.json ([9b8bf2e](https://github.com/pattern-lab/patternlab-node/commit/9b8bf2e5d02410f454acefc192fe5be9be6fdfc0))
* **config:** remove hard-coded base module path from pattern lab paths ([a4961bd](https://github.com/pattern-lab/patternlab-node/commit/a4961bd5d696a05fb516cdd951163b0f918d5e19))
* **config:** simplify relative public paths ([812bab3](https://github.com/pattern-lab/patternlab-node/commit/812bab3659f504043e8b61b1dc1cdac71f248449))
* **config:** update StaleBot labels, timeouts, and messaging ([ddd6d12](https://github.com/pattern-lab/patternlab-node/commit/ddd6d12b54bc0a6ed3cd10ca1555de1c68c08748))
* **Contributing:** Update contributing info with prettier ([2a0ce52](https://github.com/pattern-lab/patternlab-node/commit/2a0ce52394334471d355a607d240b0ffab9f1f32))
* **core:** add changelog reference to README ([2d1b7a1](https://github.com/pattern-lab/patternlab-node/commit/2d1b7a15e4b3074e36c90bb74258145b2db09335))
* **core:** add newer installation instructions to README ([1d60512](https://github.com/pattern-lab/patternlab-node/commit/1d60512749780ca3ce2210fe2f5e40d4a69d1325))
* **core:** Add tests for help command ([62cd8fb](https://github.com/pattern-lab/patternlab-node/commit/62cd8fb2fb05a676ea9b730f4c9340eac005e9eb))
* **core:** invoke registered plugin hooks ([a54d775](https://github.com/pattern-lab/patternlab-node/commit/a54d7753b6939fe6a58da543f4fb34f64dd8901a))
* **core:** remove plugin install / disable / enable logic ([5a58824](https://github.com/pattern-lab/patternlab-node/commit/5a588240400870203c682d5071cd32f6dff9f94d)), closes [#872](https://github.com/pattern-lab/patternlab-node/issues/872)
* **create:** add create package to proxy npx @pattern-lab/cli init via npm create [@pattern-lab](https://github.com/pattern-lab) ([a759df9](https://github.com/pattern-lab/patternlab-node/commit/a759df90c09bcd25666fa0f3ea4d09f6ec392598))
* **create:** make typo fallback for missing hyphen on "npm create pattern-lab" ([26fd73f](https://github.com/pattern-lab/patternlab-node/commit/26fd73f117c166108ec63ec715cafdb7135e40fe))
* **create:** release create-pattern-lab so "npm create pattern-lab" is possible ([cc27f83](https://github.com/pattern-lab/patternlab-node/commit/cc27f8366d55fa60cb69b60a19d58e5f8d0d5518))
* **debug:** Remove printDebug entirely ([d729e4c](https://github.com/pattern-lab/patternlab-node/commit/d729e4c8b3523c0b07f8dfd3c4338d2037e80eac))
* define initial viewport ([#1386](https://github.com/pattern-lab/patternlab-node/issues/1386)) ([6fa630e](https://github.com/pattern-lab/patternlab-node/commit/6fa630e2353ed68295550e59c31148269f3b7cd0))
* **docs:** Add jsdoc output to public API and events ([d45e7b9](https://github.com/pattern-lab/patternlab-node/commit/d45e7b9252c446e47dc2df7fb6df428b26f109bf))
* **docs:** added plugin ([#1469](https://github.com/pattern-lab/patternlab-node/issues/1469)) ([535c5f0](https://github.com/pattern-lab/patternlab-node/commit/535c5f0805936a25eeddde0e360cb6000c000b1b))
* **docs:** adding a sitemap.xml ([#1329](https://github.com/pattern-lab/patternlab-node/issues/1329)) ([0a7fd95](https://github.com/pattern-lab/patternlab-node/commit/0a7fd95d5f1c3ce690bbe89cc30580ff58d1ab9c))
* **docs:** Experiment with doc generation ([8e1808b](https://github.com/pattern-lab/patternlab-node/commit/8e1808bbc9022d1f269f65a8983d7ae87d54bea7))
* **docs:** yarnify ([5a47dc7](https://github.com/pattern-lab/patternlab-node/commit/5a47dc7b90dc5c43c12a51143b41943dcbd8564c))
* **documentation:** added (sub)groups documentation again [#1262](https://github.com/pattern-lab/patternlab-node/issues/1262) ([#1334](https://github.com/pattern-lab/patternlab-node/issues/1334)) ([9fac269](https://github.com/pattern-lab/patternlab-node/commit/9fac2699d2f6c64c4544e8e4d8e18c1a1ce7e49f))
* **edition-node:** switch to engine-handlebars ([b481e22](https://github.com/pattern-lab/patternlab-node/commit/b481e22dc1f41ddd4da709621640a15190fba257))
* **engine-handlebars:** Default location for helpers, like engine-nunjucks ([11c4180](https://github.com/pattern-lab/patternlab-node/commit/11c41805e0c3dbebb7109719c4f3c780d32feab5))
* **engine-handlebars:** Demonstration of custom Handlebars helper ([f330b5b](https://github.com/pattern-lab/patternlab-node/commit/f330b5bca72f2f34bfafe5c2c64e6b0b8823eb1c))
* **engine-handlebars:** Document the Helpers feature ([a01e040](https://github.com/pattern-lab/patternlab-node/commit/a01e040429a7f77dfeb28d67c690e835b97881de))
* **engine-handlebars:** Load Handlebars helpers specified in the config ([a12df36](https://github.com/pattern-lab/patternlab-node/commit/a12df36d2a644dfac8ded1dfd94b987e99c29d79))
* **engine-nunjucks:** Configurable extension locations; Use usePatternlabConfig() ([e54e3b3](https://github.com/pattern-lab/patternlab-node/commit/e54e3b3d48f934d3a4d44b9f4ff262f742a4aaf9))
* **engine-react:** set package to private ([3aea881](https://github.com/pattern-lab/patternlab-node/commit/3aea8815f19df5b527cdda0b75cf99a9a8c3bc1e))
* **engine-twig-php:** update @basalt/twig-renderer to v3.0.1 using Twig v3.7.1 ([#1499](https://github.com/pattern-lab/patternlab-node/issues/1499)) ([2e5c9e1](https://github.com/pattern-lab/patternlab-node/commit/2e5c9e1c6a3318ba1cd3765d448c181e4a3a9a27)), closes [#1496](https://github.com/pattern-lab/patternlab-node/issues/1496) [#1496](https://github.com/pattern-lab/patternlab-node/issues/1496)
* **engine-twig:** add custom twing extensions ([#1435](https://github.com/pattern-lab/patternlab-node/issues/1435)) ([c32a45c](https://github.com/pattern-lab/patternlab-node/commit/c32a45c02e3b71bb841e7ea15cae000a68857df3)), closes [#1230](https://github.com/pattern-lab/patternlab-node/issues/1230) [#1230](https://github.com/pattern-lab/patternlab-node/issues/1230)
* **engine:** Add work from upstream ([5f9bae8](https://github.com/pattern-lab/patternlab-node/commit/5f9bae83c9c8cd24fc6bb98f77b1b67628d06e14))
* **engine:** Return a promise from render ([aa868b7](https://github.com/pattern-lab/patternlab-node/commit/aa868b776cad13afdfcf48d9ddc7061d904d5327))
* **engine:** Support async render ([19f969b](https://github.com/pattern-lab/patternlab-node/commit/19f969b47bf3c3e8f3d8d4990dafd981a6adbe9b))
* **engine:** Support async render ([b40be85](https://github.com/pattern-lab/patternlab-node/commit/b40be85030597582255a9383aba2cf3385f352a6))
* ensure consistent line endings across files ([#1372](https://github.com/pattern-lab/patternlab-node/issues/1372)) ([57efccb](https://github.com/pattern-lab/patternlab-node/commit/57efccb895f142d8a18e774d7b7c01b2f1266737))
* **events:** add PATTERNLAB_BUILD_END event and rename BUILD_START ([5b7bfa3](https://github.com/pattern-lab/patternlab-node/commit/5b7bfa38c22f37737c59bbf945defec48718a7d9))
* **exportData:** Broke out file with unit test coverage ([9d788b7](https://github.com/pattern-lab/patternlab-node/commit/9d788b77b19dbb74541c641c8ecd04c61c4cd98b))
* **feat(logs:** Rename utilities to log ([d127296](https://github.com/pattern-lab/patternlab-node/commit/d1272965a92229a63a34da5d2c12f9c648786716))
* **feat(logs:** Rename utilities variable to logger ([2e821fe](https://github.com/pattern-lab/patternlab-node/commit/2e821fee7073098b8a23c54d1a2dc3127cb4abd0))
* **help:** remove help. API is now documented ([2aef3a1](https://github.com/pattern-lab/patternlab-node/commit/2aef3a14e72c22fc6c3fba584bd8df6d4dc54fb9))
* **index:** Make the cleaning of public/ an asynchronous adventure ([bd485d2](https://github.com/pattern-lab/patternlab-node/commit/bd485d29603424248a5795cd3ded0594fcd27fb1))
* integrate @hadl/patternlab-plugin-pattern-wrap into core ([#1433](https://github.com/pattern-lab/patternlab-node/issues/1433)) ([414e038](https://github.com/pattern-lab/patternlab-node/commit/414e0383732b4bc4682981000908d1e0d1292703)), closes [#1432](https://github.com/pattern-lab/patternlab-node/issues/1432) [#1432](https://github.com/pattern-lab/patternlab-node/issues/1432)
* introduce netlify preview ([6c5d332](https://github.com/pattern-lab/patternlab-node/commit/6c5d332479fb6836bd8bd5530a074d13440f8ae4))
* lay down prep work for adding full on service worker support to Pattern Lab's UI. Cache busting logic will likely need to get added but the overall setup being added pretty much works! ([c6051e3](https://github.com/pattern-lab/patternlab-node/commit/c6051e3e364dffdaa561307a1df859eb5ff7402b))
* **list_item_hunter:** Re-work algorithm ([1ac77a7](https://github.com/pattern-lab/patternlab-node/commit/1ac77a75153ce667598163540300dfc42de99e71))
* **loadPattern:** Rename pattern_assembler to loadPattern and simplify export ([165afa7](https://github.com/pattern-lab/patternlab-node/commit/165afa707d26006262604bb9ba42a8b45503caef))
* **logs:** Refactor logs for annotation_exporter ([4ed5ac5](https://github.com/pattern-lab/patternlab-node/commit/4ed5ac56df5e8ca11281cbbb34d472312b6ee3bc))
* **logs:** Refactor logs for asset_copy ([5b7fdff](https://github.com/pattern-lab/patternlab-node/commit/5b7fdff667b71884e6617204b2a4ec4d8157ce04))
* **logs:** Refactor logs for json_copy ([eee7152](https://github.com/pattern-lab/patternlab-node/commit/eee71523881b2e90afea00efd2a7f5f7345a24e3))
* **logs:** Refactor logs for lineage_hunter ([2118e08](https://github.com/pattern-lab/patternlab-node/commit/2118e0806157d9a6440a3ea4acd9203bf48c1bff))
* **logs:** Refactor logs for list_item_hunter ([9442658](https://github.com/pattern-lab/patternlab-node/commit/9442658e97431539a9897383cf65d11bb9324320))
* **logs:** Refactor logs for markdown_parser ([41a61c2](https://github.com/pattern-lab/patternlab-node/commit/41a61c27b38109a96efa57f101744465a68f4af0))
* **logs:** Refactor logs for parameter_hunter ([5021384](https://github.com/pattern-lab/patternlab-node/commit/50213846f110264c008259f33a097c9892fc392f))
* **logs:** Refactor logs for pattern_assembler ([85c039a](https://github.com/pattern-lab/patternlab-node/commit/85c039ac9c197e6633f4c35f6968c5e202da40e3))
* **logs:** Refactor logs for pattern_engines ([3881544](https://github.com/pattern-lab/patternlab-node/commit/3881544308d49a75343b5e37a7f4484e879cf48b))
* **logs:** Refactor logs for patternlab.js ([b3de4c6](https://github.com/pattern-lab/patternlab-node/commit/b3de4c6ef81ffd5a5aa8af9ba223354b04d572df)), closes [#566](https://github.com/pattern-lab/patternlab-node/issues/566)
* **logs:** Refactor logs for plugin_manager ([884975c](https://github.com/pattern-lab/patternlab-node/commit/884975cb9ba3b5a26d2925f352b7334f67cb1913))
* **logs:** Refactor logs for pseudopattern_hunter ([5442a84](https://github.com/pattern-lab/patternlab-node/commit/5442a8415d93bd6bb9cf4a07d9662ff6733c3dec))
* **logs:** Refactor logs for serve ([c2a3fa6](https://github.com/pattern-lab/patternlab-node/commit/c2a3fa60ca19608e1b1321a60ef6ced51b1bcb49))
* **logs:** Refactor logs for starterkit_manager ([9607018](https://github.com/pattern-lab/patternlab-node/commit/9607018ac7364365933cf0083a6fd6ce7b5fd7e5))
* **logs:** Refactor logs for style_modifier_hunter ([a57b7d1](https://github.com/pattern-lab/patternlab-node/commit/a57b7d1ff342c1255584c6e9344b68af6e2aab72))
* **logs:** Refactor logs for ui_builder ([6bd0381](https://github.com/pattern-lab/patternlab-node/commit/6bd0381cff93574b1a7f599499a76aa7022b814e))
* **logs:** Refactor tests to account for debug ([f6a7e59](https://github.com/pattern-lab/patternlab-node/commit/f6a7e59cb681ca1ca93afd411eac8005c3855c2f))
* **logs:** Support escalating log levels, 'debug', 'info', 'warning', 'error', as well as 'quiet' ([e33eef8](https://github.com/pattern-lab/patternlab-node/commit/e33eef8a65edd4bef64aa7b70dcd0598426c8c4b))
* major improvements to local UIKit workflow ([4dc9173](https://github.com/pattern-lab/patternlab-node/commit/4dc9173a5a44b422e9677824de3728048b7c4f05))
* major refactoring + UI updates to address cross browser support; UI cleanup and conversion of the majority of the remaining components over to lit-element ([2ff8e1c](https://github.com/pattern-lab/patternlab-node/commit/2ff8e1c98cdd02e8077064c48eca5f7754a3db02))
* **meta patterns:** Async support ([774b827](https://github.com/pattern-lab/patternlab-node/commit/774b827c6ed4bd71df7871a4508187f93be93a72))
* **object_factory:** Make all engines async ([d7087fa](https://github.com/pattern-lab/patternlab-node/commit/d7087fa799ad665b892526a2365b9811386dcf19))
* optionate cleanHtmlOutput ([a6f4d9c](https://github.com/pattern-lab/patternlab-node/commit/a6f4d9c46d130b62ca3614d8c6630263eae9adad))
* **package:** add @pattern-lab/cli as a dependency ([760d0e0](https://github.com/pattern-lab/patternlab-node/commit/760d0e0175c9fc381089c984d4ce16bb8a49c064))
* **package:** Add bower as an explicit dependency ([c070b80](https://github.com/pattern-lab/patternlab-node/commit/c070b800fcf9d712562a9770e325e021bb12da2b))
* **package:** add cli as a dependency ([a52b487](https://github.com/pattern-lab/patternlab-node/commit/a52b4875f64b26e6de5695aa7862a0ec021ab327))
* **package:** Add default theme config to patternlab-config.json ([2f6747d](https://github.com/pattern-lab/patternlab-node/commit/2f6747de85f85947ebf986807159c84eb2d9b838)), closes [#726](https://github.com/pattern-lab/patternlab-node/issues/726)
* **package:** add engine-nunjucks to monorepo ([bf527ed](https://github.com/pattern-lab/patternlab-node/commit/bf527ede1af8b5ee09ea7c9d2c0bad04141dc092)), closes [#814](https://github.com/pattern-lab/patternlab-node/issues/814)
* **package:** add handlebars development edition ([454095d](https://github.com/pattern-lab/patternlab-node/commit/454095d0f8d9ec08a674eade8594485c78003288))
* **package:** add lerna-changelog ([86ad1d5](https://github.com/pattern-lab/patternlab-node/commit/86ad1d55e681e656b98335e1465a49faaa3d7602))
* **package:** add npmrc file ([55f5bc2](https://github.com/pattern-lab/patternlab-node/commit/55f5bc26d635805648caa2d35d1bf306fe4740d5))
* **package:** add npmrc to top-level ([8702fb2](https://github.com/pattern-lab/patternlab-node/commit/8702fb2d44139e0f6ef465d036763de900caf28b))
* **package:** Add prettier ([b8e3e11](https://github.com/pattern-lab/patternlab-node/commit/b8e3e11e65d00435a2255ea5fa80528d8cfd95e8))
* **package:** Add prettier precommit hook ([a0b85b5](https://github.com/pattern-lab/patternlab-node/commit/a0b85b5aa2575f84a8c3c0c779dfab00c5085cc4))
* **package:** Add standard version ([b2ba31c](https://github.com/pattern-lab/patternlab-node/commit/b2ba31c7d2f472bd9b86815b70654aa14dcc1a39))
* **package:** add test command which bails on error ([3118cac](https://github.com/pattern-lab/patternlab-node/commit/3118caca9316bdd6818e070dcd81d72b65df58f7))
* **package:** Communicate official node support ([96ca87f](https://github.com/pattern-lab/patternlab-node/commit/96ca87f7ca75631400761bdf5690ec30130263b4))
* **package:** Hoist up tap and test command. ([6cacdb6](https://github.com/pattern-lab/patternlab-node/commit/6cacdb64b4327777bdea8c6c9f36ad20e608278f))
* **package:** install all main engines as devDependencies so tests run ([f633671](https://github.com/pattern-lab/patternlab-node/commit/f633671858829724fab592c33e3f94ddbde3e5f9))
* **package:** pin all dependencies ([415698e](https://github.com/pattern-lab/patternlab-node/commit/415698eb9a70d477ffb7b2906e679ac8f2051c60))
* **package:** remove package-lock.json files ([5ab3995](https://github.com/pattern-lab/patternlab-node/commit/5ab399599a1dbea8239fbd09a34d5f39ad762e21))
* **package:** revamp plugin-tab ([2aa0f8f](https://github.com/pattern-lab/patternlab-node/commit/2aa0f8f84df33b03b7a91638f5582b2e706307ad))
* **package:** standardize and hoist common devDependencies ([7f4ce6f](https://github.com/pattern-lab/patternlab-node/commit/7f4ce6ff1238986bed906c27d2f4bf7329752d92))
* **packages:** Update all package.json repo and bug links ([5eb2c11](https://github.com/pattern-lab/patternlab-node/commit/5eb2c1148d428170236907cbbc42ba05d046e408))
* **package:** The initial merge of styleguidekit-assets-default and styleguidekit-mustache-default ([9ec911e](https://github.com/pattern-lab/patternlab-node/commit/9ec911e1a2937b93058e4f731324789c379ea4db))
* **package:** Update guidelines and templates ([604c958](https://github.com/pattern-lab/patternlab-node/commit/604c958b24d2243c88878339649ce24144b90355))
* **package:** update lerna ([bc7c8a2](https://github.com/pattern-lab/patternlab-node/commit/bc7c8a26ebb5d7903cfae7b80fb9059e108f0d44))
* **parameter_hunter:** Async support ([ba1c436](https://github.com/pattern-lab/patternlab-node/commit/ba1c43676b6885a5bc384fc8190b38b3e30bdc84))
* pass additional configuration into twig-php engine ([dff5a78](https://github.com/pattern-lab/patternlab-node/commit/dff5a7830918fa46e2692d9f9daed4121f803461))
* **pattern lab:** Copy pattern-specific js ([99bfc02](https://github.com/pattern-lab/patternlab-node/commit/99bfc0295ce40970c74d2de2fa3ea964214f2a15))
* **pattern lab:** Pass `patternPartial` as data to render ([351ea5e](https://github.com/pattern-lab/patternlab-node/commit/351ea5edfa8f3f8d0a3419ca3d397ff3e37ceda9))
* **pattern_assembler:** Break out renderSync ([921b513](https://github.com/pattern-lab/patternlab-node/commit/921b513ac547315e8182baef0dc7a20ae7f3f9bd))
* **pattern_assembler:** Breaking up into smaller files ([e2fa1f5](https://github.com/pattern-lab/patternlab-node/commit/e2fa1f5cf1bede546f249791630dc56ecf8c3f0a))
* **pattern_assembler:** Further broke out files ([2764a75](https://github.com/pattern-lab/patternlab-node/commit/2764a758890de01e6aa786aa769dfe1622816f6e))
* **pattern_assembler:** Further separate files ([7d57fe7](https://github.com/pattern-lab/patternlab-node/commit/7d57fe7f13084674e02f8c15451894856aee402a))
* **patternlab:** Accept additional data during build as an option ([3100402](https://github.com/pattern-lab/patternlab-node/commit/31004023e12a3fa8bcdd46812550ce83d10bc1b6))
* **patternlabjs:** Remove build callback ([d2f346d](https://github.com/pattern-lab/patternlab-node/commit/d2f346d43532bdc939d476cb26e2a821f7a982f7)), closes [#751](https://github.com/pattern-lab/patternlab-node/issues/751)
* **patternlab:** Separate patternlab.js into two files ([86233ca](https://github.com/pattern-lab/patternlab-node/commit/86233ca5e3ba3c81e88f8d582fec2455d8403ec5))
* **plugin-tab, core:** initial plugin hook exploration ([2f3d39a](https://github.com/pattern-lab/patternlab-node/commit/2f3d39ac6b125ad4c6b872e27ee224ce2ea33a12))
* **plugin-tab:** pivot to using hook functions ([d4b2598](https://github.com/pattern-lab/patternlab-node/commit/d4b25984fc2a2646cc1876a5c635f57593c35f09))
* port latest UIKit updates + fixes upstream ([d07952c](https://github.com/pattern-lab/patternlab-node/commit/d07952cb07e3792b995dda2e589262ecf4153fdc))
* **README:** Add coveralls badge to README ([c68e6a7](https://github.com/pattern-lab/patternlab-node/commit/c68e6a79252129c292b95790985cf63528e0276d)), closes [#728](https://github.com/pattern-lab/patternlab-node/issues/728)
* **README:** add netlify badges ([941df8a](https://github.com/pattern-lab/patternlab-node/commit/941df8a59b6b75bc1255646005f329e40be68106))
* **README:** Add prettier badge ([7c2787b](https://github.com/pattern-lab/patternlab-node/commit/7c2787bbe8dc6a5aed0fc536343217225709039e))
* **README:** clarify purpose of development edition ([d90df0e](https://github.com/pattern-lab/patternlab-node/commit/d90df0ef9de42a4c975450fca77496096c634ff2))
* **README:** simplify README and add CLI configuration instructions ([ceec673](https://github.com/pattern-lab/patternlab-node/commit/ceec673b1a9b473949534a444b4334c48bcdf5cd))
* **README:** Update for brevity and consistency ([65a2969](https://github.com/pattern-lab/patternlab-node/commit/65a29692c7f12a54689f6ed3a9ecc7d7d2475ace))
* **README:** Update for brevity and consistency ([a7f6866](https://github.com/pattern-lab/patternlab-node/commit/a7f68661be091868e4e17a0cbbac42dfd8a15970))
* **README:** Update for brevity and consistency ([aec7c50](https://github.com/pattern-lab/patternlab-node/commit/aec7c50aedb1e081c541cd106f31125f70658dec))
* refactor + convert pl-toggle-info to lit-element ([85cd9c5](https://github.com/pattern-lab/patternlab-node/commit/85cd9c50ca814066bf999badf2071d84964f00cc))
* refactor + convert pl-toggle-layout to lit-element ([46009d9](https://github.com/pattern-lab/patternlab-node/commit/46009d91b1cb9ed613baa5a7626cba4f42883465))
* refactor + convert pl-toggle-theme to lit-element ([95a3b21](https://github.com/pattern-lab/patternlab-node/commit/95a3b21a89dacd2d5b4df8c134ce438d4efdbd04))
* refactor Drawer to render via lit-element + massively improve rendering performance ([28d47eb](https://github.com/pattern-lab/patternlab-node/commit/28d47eb3cbbce038204203e786e5188b4cefe64f))
* remove mixin that was causing outlines to be removed from default UI styles ([622ed76](https://github.com/pattern-lab/patternlab-node/commit/622ed76d435b3b2e31e412266c3090506f98051b))
* remove pre-built uikit dist folder and switch to auto-building when bootstrapping OR when publishing to NPM ([b5dd553](https://github.com/pattern-lab/patternlab-node/commit/b5dd5538ee00ddf1da321851865fa1c223cedb43))
* remove sandbox attribute from iframe ([#1422](https://github.com/pattern-lab/patternlab-node/issues/1422)) ([4335660](https://github.com/pattern-lab/patternlab-node/commit/4335660bac6f87618baaef9d773e00d7e80c6eec))
* **render:** Add debugging ([558967e](https://github.com/pattern-lab/patternlab-node/commit/558967e9053b787996efdabd67c85ef6805594fd))
* **render:** Alter info to debug message ([ef54007](https://github.com/pattern-lab/patternlab-node/commit/ef54007547ab25805abfb23aa4e8687fc27f0a85))
* **scripts:** namespace scripts ([3ecbb3e](https://github.com/pattern-lab/patternlab-node/commit/3ecbb3e9467552c13f9c9d77329b2554920a8cff))
* **scripts:** refactor to use cli commands ([e8d5c21](https://github.com/pattern-lab/patternlab-node/commit/e8d5c211bd49a7e96bd43cf802d8bcefec4c6b93))
* **serve:** change calling method ([f47217a](https://github.com/pattern-lab/patternlab-node/commit/f47217af6f942991cfc199b5899713f59a4ad95a))
* **serve:** change calling method ([3b86a0d](https://github.com/pattern-lab/patternlab-node/commit/3b86a0dbb29ec8842d49e2158bd0c6ace45fb86b))
* **server:** beginning of refator ([a3d65c3](https://github.com/pattern-lab/patternlab-node/commit/a3d65c3af547371c6c10b33ec8133b48e9ed2a1d))
* **server:** continue server refactor ([8f6cd91](https://github.com/pattern-lab/patternlab-node/commit/8f6cd91d7aac80c4110f5bb99b7f01af451c0a1b))
* setup edition-twig in cli init ([480ed5d](https://github.com/pattern-lab/patternlab-node/commit/480ed5d14042a31d566d8d1107f7ca820ea18293))
* **starterkits:** add starterkit-handlebars-demo ([384d2cf](https://github.com/pattern-lab/patternlab-node/commit/384d2cfa3440c1e6f456d39f56ca6381f82f7689))
* switch engine-twig to use twing rather than node-twig ([daca95c](https://github.com/pattern-lab/patternlab-node/commit/daca95c4ffa48916fb6c67c5184bde9b624acd76))
* switch to Yarn + Yarn workspaces ([f4c4ec3](https://github.com/pattern-lab/patternlab-node/commit/f4c4ec33cd30d372c87ffa904fbe7d5b819ee14e))
* temp add unsafe-svg directive till upstream PR merged ([34de61c](https://github.com/pattern-lab/patternlab-node/commit/34de61ccd9c7bb3b48ca5ef386a87efc8e84babc))
* test adding cross-env to Twig Edition test ([3f8bb01](https://github.com/pattern-lab/patternlab-node/commit/3f8bb01bc4e96a0aba61c213ea1619c02593defc))
* **tests:** start altering tests ([175f9c9](https://github.com/pattern-lab/patternlab-node/commit/175f9c9717fbdcd57c9a479a18d35cf723b828d6))
* **tests:** use lerna run test at the monorepo level ([38a01b1](https://github.com/pattern-lab/patternlab-node/commit/38a01b148a5356e2f8b30182e0453f6746347d96))
* **ui_builder:** Async support ([dec04fe](https://github.com/pattern-lab/patternlab-node/commit/dec04fed9edf0eb99e970e9ea0b21bc28b966275))
* **ui_builder:** Broke out buildFooter ([32a13e1](https://github.com/pattern-lab/patternlab-node/commit/32a13e15589e0b55bb3235917d34f6a70cf14577))
* **uikit-workshop:** add plugin-loader ([fc966d6](https://github.com/pattern-lab/patternlab-node/commit/fc966d6b151e24055bc2f4146d6a90b5fb392765))
* **uikits:** add uikits to test config ([43a2017](https://github.com/pattern-lab/patternlab-node/commit/43a2017c330736343569a5cc12c378284665c137))
* **uikits:** additional test coverage ([f5b60b2](https://github.com/pattern-lab/patternlab-node/commit/f5b60b2462bd1659db8c900874b728a5eec0b584))
* **uikits:** additional test coverage of the main API ([fbcacfb](https://github.com/pattern-lab/patternlab-node/commit/fbcacfb9bbabf70d4f55336bec5ab0f9133ebf15))
* **uikits:** clean each build directory if configured ([8e11342](https://github.com/pattern-lab/patternlab-node/commit/8e1134280d2c031825f716a7710618bcb04e22f9))
* **uikits:** copy pattern-specific javascript ([3ac93dc](https://github.com/pattern-lab/patternlab-node/commit/3ac93dc06ad3d2f725fa36e6f20c6aba6bebb0e9))
* **uikits:** create MVP output to disk ([e1598d3](https://github.com/pattern-lab/patternlab-node/commit/e1598d37e0b3e4aa9dd34a1f5da6eddde353d8dd))
* **uikits:** filter out excluded pattern states from uikit output ([87c9d0d](https://github.com/pattern-lab/patternlab-node/commit/87c9d0d2c315d9f6060df70fc41a7f4a9a5e9f9d))
* **uikits:** load uikits before build ([4565202](https://github.com/pattern-lab/patternlab-node/commit/4565202d32e5498512d01ff03e21f9fdb51b4c20))
* **uikits:** output assets and annotations to each location ([b0a84ca](https://github.com/pattern-lab/patternlab-node/commit/b0a84cad95242867d5cf1fa1dd0edb0a6adff3c6))
* **uikits:** output pattern files to each location ([5df87b0](https://github.com/pattern-lab/patternlab-node/commit/5df87b058ccd128b41f72f90671084bd4373bf71))
* **uikits:** promote dependencyGraph.json output to root ([dd3e708](https://github.com/pattern-lab/patternlab-node/commit/dd3e708570b8dda69626cc19264c40e745755a96))
* **uikits:** remove workshop for default config ([55570ff](https://github.com/pattern-lab/patternlab-node/commit/55570ffd6a946a796c587d13bcde9f8e81872040))
* **uikits:** render header and footer data correctly ([f2a6f23](https://github.com/pattern-lab/patternlab-node/commit/f2a6f23eff6d730a2b493d470b3b159b8c6880d2))
* **uikits:** support incremental builds ([6670364](https://github.com/pattern-lab/patternlab-node/commit/66703646401b18af17e81d8ce2495f659408387c))
* **uikits:** support watched-asset copying ([4f05311](https://github.com/pattern-lab/patternlab-node/commit/4f0531137b19cd2e49ed09edeab24392d1eb1a28))
* **uikits:** uikits config ([027e56c](https://github.com/pattern-lab/patternlab-node/commit/027e56c55a06097520eb8367c0129f24d1d1d412))
* **uikits:** uikits config to default ([a393851](https://github.com/pattern-lab/patternlab-node/commit/a39385165e6d7398c0aa4fd2283651b5c10ac872))
* **unit tests:** Unit test coverage for loadPattern ([578a9af](https://github.com/pattern-lab/patternlab-node/commit/578a9af872f488f7e89a51a8a841ccec881069d2))
* update Node to v12 ([fcbb970](https://github.com/pattern-lab/patternlab-node/commit/fcbb970648cdd775c9a88078f14c1f24c5b62d73))
* update the Nav design to not bold the active item in order to not shift the layout ([0eda431](https://github.com/pattern-lab/patternlab-node/commit/0eda4312ba9f4c61afa6322c3ff45f9cda0efc9e))
* update Webpack config to use the latest Style Loader + new SVG icon system ([2ed70e7](https://github.com/pattern-lab/patternlab-node/commit/2ed70e79d8656c7314d8b3109aa1c34160ad24f9))
* upgrade Twig to use new filter, map, reduce ([4218a5a](https://github.com/pattern-lab/patternlab-node/commit/4218a5a04b06027548afd9f417486297dd25fef8))
* **utilities:** Add info level log method ([7f4cba8](https://github.com/pattern-lab/patternlab-node/commit/7f4cba8baf0af0a85714e58909303a0b4d1402dd))
* **vs-code:** added recommendations ([#1375](https://github.com/pattern-lab/patternlab-node/issues/1375)) ([cfa74c0](https://github.com/pattern-lab/patternlab-node/commit/cfa74c0d09c3aae78ef10654f48749a568f3e30d))
* **watches:** add additional assets to ignore ([18e74c2](https://github.com/pattern-lab/patternlab-node/commit/18e74c2f34aacd3b5cd983337ea41b202496e717))
* wire up new PL-specific iframe loader toast to display before the JS updating the iframe content kicks in ([4cb08d5](https://github.com/pattern-lab/patternlab-node/commit/4cb08d581a1b346f8adf94760c6f89113558b796))
* wire up redux + store + a few basic actions to support globally toggling the theme and layout config options ([01f9dce](https://github.com/pattern-lab/patternlab-node/commit/01f9dce254ccda0fe56154892fc40b2ef61d612d))


### Reverts

* Revert "refactor: optimized engines directory retrieval (#1359)" (#1363) ([a275d36](https://github.com/pattern-lab/patternlab-node/commit/a275d36c50c3846fc51c78baf6e11dba5309f5dc)), closes [#1359](https://github.com/pattern-lab/patternlab-node/issues/1359) [#1363](https://github.com/pattern-lab/patternlab-node/issues/1363)
* Revert "[skip travis] chore(release): publish v5.10.0" ([7496318](https://github.com/pattern-lab/patternlab-node/commit/7496318e083f667b6da914e21595c52442d62703))
* Revert "Update version" ([32ec1c8](https://github.com/pattern-lab/patternlab-node/commit/32ec1c8dec2e95d95b837397bd9aa2d47d84b887))
* Revert "added coveralls" ([50a4660](https://github.com/pattern-lab/patternlab-node/commit/50a466022efd8e89594f5e97e3b68b0848c28ad7))
* Revert "pushing experimental fix for a CLI issue" ([457ed48](https://github.com/pattern-lab/patternlab-node/commit/457ed4893f5a6b49bd1d4f7cba832e425e69aa55))
* Revert "pushing some cleanup relevant to https://github.com/pattern-lab/patternlab-node/issues/428" ([25bbea0](https://github.com/pattern-lab/patternlab-node/commit/25bbea0aefc319f1ebb7807030a929525ad7d279))
* Revert "in process stylemodifier work" ([6fc72a2](https://github.com/pattern-lab/patternlab-node/commit/6fc72a27734926ef903740f72a144fdcf949e4fa))
* **create:** delete typo fallback since npm won't let me publish it ([1bbdb50](https://github.com/pattern-lab/patternlab-node/commit/1bbdb508a021eb974e70a5324881451e560ed3d6))
* don't flatten folders containing only one item inside ([77f1f46](https://github.com/pattern-lab/patternlab-node/commit/77f1f46595328bd96fba46347b532295c65802d1))
* undo removing hideScroll mixin from previous commit ([caa124a](https://github.com/pattern-lab/patternlab-node/commit/caa124ace177cea0772f673c35a20e1ce93f5846))


### BREAKING CHANGES

* **core:** plugins now use async functions instead of events
* **plugin-tab:** event based listeners replaced with functions
* **cli:** previously, we concatenated arrays, which is unlikely to be intended
* **edition-node:** use handlebars over mustache
* **API:** change `version()` to return a string representation of the version, removing `v()`





# [6.1.0](https://github.com/pattern-lab/patternlab-node/compare/v6.0.3...v6.1.0) (2023-12-21)


### Features

* **engine-twig-php:** update @basalt/twig-renderer to v3.0.1 using Twig v3.7.1 ([#1499](https://github.com/pattern-lab/patternlab-node/issues/1499)) ([2e5c9e1](https://github.com/pattern-lab/patternlab-node/commit/2e5c9e1c6a3318ba1cd3765d448c181e4a3a9a27)), closes [#1496](https://github.com/pattern-lab/patternlab-node/issues/1496) [#1496](https://github.com/pattern-lab/patternlab-node/issues/1496)





## [6.0.3](https://github.com/pattern-lab/patternlab-node/compare/v6.0.2...v6.0.3) (2023-03-12)


### Bug Fixes

* subitems menu height restricted only for horizontal mode ([#1492](https://github.com/pattern-lab/patternlab-node/issues/1492)) ([e65f294](https://github.com/pattern-lab/patternlab-node/commit/e65f294d9cbf032fd7fd03d9f957500949db5440))





## [6.0.2](https://github.com/pattern-lab/patternlab-node/compare/v6.0.1...v6.0.2) (2023-02-26)


### Bug Fixes

* **starterkit-twig-demo:** pages not rendering pattern-specific data from json ([#1490](https://github.com/pattern-lab/patternlab-node/issues/1490)) ([1c878df](https://github.com/pattern-lab/patternlab-node/commit/1c878dfa35d549f23e199b3e235ff79cb471ac86)), closes [#1486](https://github.com/pattern-lab/patternlab-node/issues/1486)





## [6.0.1](https://github.com/pattern-lab/patternlab-node/compare/v6.0.0...v6.0.1) (2023-02-01)


### Bug Fixes

* **twig engine:** startup and running problems ([#1478](https://github.com/pattern-lab/patternlab-node/issues/1478)) ([e5a1904](https://github.com/pattern-lab/patternlab-node/commit/e5a19049f083315939406677b1c0480f4b420569))





# [6.0.0](https://github.com/pattern-lab/patternlab-node/compare/v5.17.0...v6.0.0) (2023-01-31)


### Bug Fixes

* **engine-twig-php:** twig include function syntax not matched by findPartials ([#1472](https://github.com/pattern-lab/patternlab-node/issues/1472)) ([3677539](https://github.com/pattern-lab/patternlab-node/commit/3677539409ac41dfee71d90cc429be5c92890838)), closes [#1471](https://github.com/pattern-lab/patternlab-node/issues/1471)
* **engine-twig:** twig include function syntax not matched by findPartials ([#1473](https://github.com/pattern-lab/patternlab-node/issues/1473)) ([cfa792b](https://github.com/pattern-lab/patternlab-node/commit/cfa792b2753d9f9f1840e08d55983c6c051b01fd)), closes [#1471](https://github.com/pattern-lab/patternlab-node/issues/1471)
* hogan to handlebars migration leftovers ([#1461](https://github.com/pattern-lab/patternlab-node/issues/1461)) ([566485a](https://github.com/pattern-lab/patternlab-node/commit/566485a5c20d739bfe9c77c11b8ddfa09e292481))
* HTML structure ([#1450](https://github.com/pattern-lab/patternlab-node/issues/1450)) ([8567e2b](https://github.com/pattern-lab/patternlab-node/commit/8567e2b218a4ef9df0e359ca77229dda54712200))
* js error ([#1475](https://github.com/pattern-lab/patternlab-node/issues/1475)) ([209b9a1](https://github.com/pattern-lab/patternlab-node/commit/209b9a15871354ac4ae982d93d6be03272799005)), closes [/github.com/pattern-lab/patternlab-node/pull/1102/files#diff-9111c2e0138c935342632437be7178f25322b8f5c86431f2b85f4fe760d32980L96-R111](https://github.com//github.com/pattern-lab/patternlab-node/pull/1102/files/issues/diff-9111c2e0138c935342632437be7178f25322b8f5c86431f2b85f4fe760d32980L96-R111)
* updated base template to handlebars ([#1463](https://github.com/pattern-lab/patternlab-node/issues/1463)) ([c69c658](https://github.com/pattern-lab/patternlab-node/commit/c69c658d06dab9a1bf04f77e7902ff3f07c94c3e))


### Features

* activate prettier for scss ([#1468](https://github.com/pattern-lab/patternlab-node/issues/1468)) ([fac6ad4](https://github.com/pattern-lab/patternlab-node/commit/fac6ad4be48c95eccfe890a280cad441ee84f677))
* **docs:** added plugin ([#1469](https://github.com/pattern-lab/patternlab-node/issues/1469)) ([535c5f0](https://github.com/pattern-lab/patternlab-node/commit/535c5f0805936a25eeddde0e360cb6000c000b1b))





# [5.17.0](https://github.com/pattern-lab/patternlab-node/compare/v5.16.4...v5.17.0) (2022-09-25)


### Features

* **engine-twig:** add custom twing extensions ([#1435](https://github.com/pattern-lab/patternlab-node/issues/1435)) ([c32a45c](https://github.com/pattern-lab/patternlab-node/commit/c32a45c02e3b71bb841e7ea15cae000a68857df3)), closes [#1230](https://github.com/pattern-lab/patternlab-node/issues/1230) [#1230](https://github.com/pattern-lab/patternlab-node/issues/1230)
* integrate @hadl/patternlab-plugin-pattern-wrap into core ([#1433](https://github.com/pattern-lab/patternlab-node/issues/1433)) ([414e038](https://github.com/pattern-lab/patternlab-node/commit/414e0383732b4bc4682981000908d1e0d1292703)), closes [#1432](https://github.com/pattern-lab/patternlab-node/issues/1432) [#1432](https://github.com/pattern-lab/patternlab-node/issues/1432)





## [5.16.4](https://github.com/pattern-lab/patternlab-node/compare/v5.16.2...v5.16.4) (2022-09-23)


### Bug Fixes

* code scanning alert ([#1442](https://github.com/pattern-lab/patternlab-node/issues/1442)) ([749a3e7](https://github.com/pattern-lab/patternlab-node/commit/749a3e722249846c522e3f7de6e73b5afa8531b1))
* div isn't allowed in button elements ([#1438](https://github.com/pattern-lab/patternlab-node/issues/1438)) ([e5c6950](https://github.com/pattern-lab/patternlab-node/commit/e5c6950e6218df99f9d9d35388c36a0130236f28))
* twig logo is rendered as "NaN" ([#1434](https://github.com/pattern-lab/patternlab-node/issues/1434)) ([ab6b133](https://github.com/pattern-lab/patternlab-node/commit/ab6b133019d9dfa3816e8fc9a9caa7b547e19097)), closes [#1407](https://github.com/pattern-lab/patternlab-node/issues/1407)





## [5.16.2](https://github.com/pattern-lab/patternlab-node/compare/v5.16.1...v5.16.2) (2022-02-07)


### Bug Fixes

* transformed asset types is ignored ([#1426](https://github.com/pattern-lab/patternlab-node/issues/1426)) ([8cbe189](https://github.com/pattern-lab/patternlab-node/commit/8cbe189d45afaa753ce6de41bdd9de1596e074f3)), closes [#1339](https://github.com/pattern-lab/patternlab-node/issues/1339)


### Features

* remove sandbox attribute from iframe ([#1422](https://github.com/pattern-lab/patternlab-node/issues/1422)) ([4335660](https://github.com/pattern-lab/patternlab-node/commit/4335660bac6f87618baaef9d773e00d7e80c6eec))





## [5.16.1](https://github.com/pattern-lab/patternlab-node/compare/v5.16.0...v5.16.1) (2022-01-29)

**Note:** Version bump only for package patternlab-node-main





# [5.16.0](https://github.com/pattern-lab/patternlab-node/compare/v5.15.7...v5.16.0) (2022-01-29)


### Bug Fixes

* **annotations:** displaying annotation tooltips correctly ([#1406](https://github.com/pattern-lab/patternlab-node/issues/1406)) ([3f33ce5](https://github.com/pattern-lab/patternlab-node/commit/3f33ce5c51f2f7a6afd86d3500b7659afd0198e6)), closes [#2](https://github.com/pattern-lab/patternlab-node/issues/2) [#1](https://github.com/pattern-lab/patternlab-node/issues/1)
* **annotations:** hiding those correctly ([#1415](https://github.com/pattern-lab/patternlab-node/issues/1415)) ([ef0a60f](https://github.com/pattern-lab/patternlab-node/commit/ef0a60fcc8656acc6d83bb0723c02a658f7ff1f3))





## [5.15.7](https://github.com/pattern-lab/patternlab-node/compare/v5.15.6...v5.15.7) (2021-12-07)

**Note:** Version bump only for package patternlab-node-main





## [5.15.6](https://github.com/pattern-lab/patternlab-node/compare/v5.15.5...v5.15.6) (2021-12-07)

**Note:** Version bump only for package patternlab-node-main





## [5.15.5](https://github.com/pattern-lab/patternlab-node/compare/v5.15.3...v5.15.5) (2021-12-06)


### Bug Fixes

* corrected some github urls ([#1388](https://github.com/pattern-lab/patternlab-node/issues/1388)) ([7f37e9d](https://github.com/pattern-lab/patternlab-node/commit/7f37e9d56b553dc4be53590766c0fc6251458829))


### Features

* define initial viewport ([#1386](https://github.com/pattern-lab/patternlab-node/issues/1386)) ([6fa630e](https://github.com/pattern-lab/patternlab-node/commit/6fa630e2353ed68295550e59c31148269f3b7cd0))





## [5.15.4](https://github.com/pattern-lab/patternlab-node/compare/v5.15.3...v5.15.4) (2021-12-06)


### Bug Fixes

* corrected some github urls ([#1388](https://github.com/pattern-lab/patternlab-node/issues/1388)) ([7f37e9d](https://github.com/pattern-lab/patternlab-node/commit/7f37e9d56b553dc4be53590766c0fc6251458829))


### Features

* define initial viewport ([#1386](https://github.com/pattern-lab/patternlab-node/issues/1386)) ([6fa630e](https://github.com/pattern-lab/patternlab-node/commit/6fa630e2353ed68295550e59c31148269f3b7cd0))





## [5.15.3](https://github.com/pattern-lab/patternlab-node/compare/v5.15.2...v5.15.3) (2021-11-21)


### Bug Fixes

* **docs:** tiles z-index to not overlay the menu anymore ([#1370](https://github.com/pattern-lab/patternlab-node/issues/1370)) ([384dc89](https://github.com/pattern-lab/patternlab-node/commit/384dc8900ee5768f5a260fd00fe03d11ae047484))
* **handlebars-demo:** move and modify the icon files ([#1377](https://github.com/pattern-lab/patternlab-node/issues/1377)) ([7c66f8a](https://github.com/pattern-lab/patternlab-node/commit/7c66f8ad4cd15e0a814f9808d0fbca727903aeb5))


### Features

* **vs-code:** added recommendations ([#1375](https://github.com/pattern-lab/patternlab-node/issues/1375)) ([cfa74c0](https://github.com/pattern-lab/patternlab-node/commit/cfa74c0d09c3aae78ef10654f48749a568f3e30d))
* ensure consistent line endings across files ([#1372](https://github.com/pattern-lab/patternlab-node/issues/1372)) ([57efccb](https://github.com/pattern-lab/patternlab-node/commit/57efccb895f142d8a18e774d7b7c01b2f1266737))





## [5.15.2](https://github.com/pattern-lab/patternlab-node/compare/v5.15.1...v5.15.2) (2021-11-03)


### Bug Fixes

* **core:** Subgroup cannot be hidden ([#1368](https://github.com/pattern-lab/patternlab-node/issues/1368)) ([3ce13ab](https://github.com/pattern-lab/patternlab-node/commit/3ce13abffaab2810194003aeca88be671fedd38f))





## [5.15.1](https://github.com/pattern-lab/patternlab-node/compare/v5.15.0...v5.15.1) (2021-10-16)


### Bug Fixes

* **docs:** use "UIKits" instead of "StyleguideKits" ([#1345](https://github.com/pattern-lab/patternlab-node/issues/1345)) ([a2885ea](https://github.com/pattern-lab/patternlab-node/commit/a2885ea738c2d807dd99c6749ac6e6437d8d3e7e))
* **initialize:** updating no-emit-webpack-plugin dependency [#1348](https://github.com/pattern-lab/patternlab-node/issues/1348) ([#1349](https://github.com/pattern-lab/patternlab-node/issues/1349)) ([a884897](https://github.com/pattern-lab/patternlab-node/commit/a884897cf9f98b61c9bdd20acf7e079de0782f10))
* **node16:** prevent warning on installation process ([#1352](https://github.com/pattern-lab/patternlab-node/issues/1352)) ([d58e4c6](https://github.com/pattern-lab/patternlab-node/commit/d58e4c6f2979f5e0bba9a14e17e0dbc4afc64f75))


### Features

* added https description to the docs ([#1355](https://github.com/pattern-lab/patternlab-node/issues/1355)) ([4118f74](https://github.com/pattern-lab/patternlab-node/commit/4118f740810842b16cf86b9ee28bda2a623aa9c7))


### Reverts

* Revert "refactor: optimized engines directory retrieval (#1359)" (#1363) ([a275d36](https://github.com/pattern-lab/patternlab-node/commit/a275d36c50c3846fc51c78baf6e11dba5309f5dc)), closes [#1359](https://github.com/pattern-lab/patternlab-node/issues/1359) [#1363](https://github.com/pattern-lab/patternlab-node/issues/1363)





# [5.15.0](https://github.com/pattern-lab/patternlab-node/compare/v5.14.3...v5.15.0) (2021-07-01)


### Bug Fixes

* **live-server:** testing ([#1331](https://github.com/pattern-lab/patternlab-node/issues/1331)) ([2b2e1b1](https://github.com/pattern-lab/patternlab-node/commit/2b2e1b1c2426ab578dc014ea99df520d17a7db92))


### Features

* **docs:** adding a sitemap.xml ([#1329](https://github.com/pattern-lab/patternlab-node/issues/1329)) ([0a7fd95](https://github.com/pattern-lab/patternlab-node/commit/0a7fd95d5f1c3ce690bbe89cc30580ff58d1ab9c))
* **documentation:** added (sub)groups documentation again [#1262](https://github.com/pattern-lab/patternlab-node/issues/1262) ([#1334](https://github.com/pattern-lab/patternlab-node/issues/1334)) ([9fac269](https://github.com/pattern-lab/patternlab-node/commit/9fac2699d2f6c64c4544e8e4d8e18c1a1ce7e49f))





## [5.14.3](https://github.com/pattern-lab/patternlab-node/compare/v5.14.2...v5.14.3) (2021-05-17)


### Bug Fixes

* **pseudopatterns:** use the template instead of the pseudo data file for template rendering [#1308](https://github.com/pattern-lab/patternlab-node/issues/1308) ([#1312](https://github.com/pattern-lab/patternlab-node/issues/1312)) ([7ecca69](https://github.com/pattern-lab/patternlab-node/commit/7ecca69bcfed4060d17390b76562e5f468b4a897))





## [5.14.2](https://github.com/pattern-lab/patternlab-node/compare/v5.14.1...v5.14.2) (2021-03-28)


### Bug Fixes

* **core:** ReadDocumentation throw error on older node versions ([#1295](https://github.com/pattern-lab/patternlab-node/issues/1295)) ([399d0e1](https://github.com/pattern-lab/patternlab-node/commit/399d0e118ab77a414a926b078da9abbcb5347969))
* **twig:** starter-kit-twig urls are incorrect on npm ([#1297](https://github.com/pattern-lab/patternlab-node/issues/1297)) ([4256d6b](https://github.com/pattern-lab/patternlab-node/commit/4256d6b13f9c2cfadf7620b0cb744cf71c3257f5))





## [5.14.1](https://github.com/pattern-lab/patternlab-node/compare/v5.14.0...v5.14.1) (2021-02-19)


### Bug Fixes

* **demopage:** switched to HTTPS URLs for image placeholders ([#1289](https://github.com/pattern-lab/patternlab-node/issues/1289)) ([e09bf6a](https://github.com/pattern-lab/patternlab-node/commit/e09bf6aae9bad99365b5a01381e0df6de9ddeafe))





# [5.14.0](https://github.com/pattern-lab/patternlab-node/compare/v5.13.3...v5.14.0) (2021-01-12)

**Note:** Version bump only for package patternlab-node





## [5.13.3](https://github.com/pattern-lab/patternlab-node/compare/v5.13.2...v5.13.3) (2020-12-17)

**Note:** Version bump only for package patternlab-node-main





## [5.13.2](https://github.com/pattern-lab/patternlab-node/compare/v5.13.1...v5.13.2) (2020-11-12)

**Note:** Version bump only for package patternlab-node-main





## [5.13.1](https://github.com/pattern-lab/patternlab-node/compare/v5.13.0...v5.13.1) (2020-09-06)

**Note:** Version bump only for package patternlab-node-main





# [5.13.0](https://github.com/pattern-lab/patternlab-node/compare/v5.12.0...v5.13.0) (2020-08-26)

**Note:** Version bump only for package patternlab-node-main





# [5.12.0](https://github.com/pattern-lab/patternlab-node/compare/v5.11.1...v5.12.0) (2020-08-09)

**Note:** Version bump only for package patternlab-node





## [5.11.1](https://github.com/pattern-lab/patternlab-node/compare/v5.10.2...v5.11.1) (2020-06-28)


### Bug Fixes

* update Viewport Size toggle to better handle async-loaded ishControl data + prevent rendering errors ([b937706](https://github.com/pattern-lab/patternlab-node/commit/b93770669c6f723128ba68e522c9398cc1d2d70c))
* update Webpack config to point to the patched version of preact-dom ([d3660b7](https://github.com/pattern-lab/patternlab-node/commit/d3660b78bc0a74c52ed85b69b023c612b789c318))
* update yarn.lock ([dca1948](https://github.com/pattern-lab/patternlab-node/commit/dca19489b85f715de3ade2294fa49df89b8bb59f))
* visually hide NavToggle icon text; fix for visual regression after merging down https://github.com/pattern-lab/patternlab-node/pull/1227 ([3a2ad9f](https://github.com/pattern-lab/patternlab-node/commit/3a2ad9f12d83b6d21dcca62e89d944a6a46342f6))
* **docs:** corrected a URL ([26ede14](https://github.com/pattern-lab/patternlab-node/commit/26ede14a6eafe8649cbc6b0076d84f1d323c3e20))
* **docs:** fixed css code for custom patternstates color ([8995241](https://github.com/pattern-lab/patternlab-node/commit/89952416162c01d1e3e05221ce58a7755544131c)), closes [#1216](https://github.com/pattern-lab/patternlab-node/issues/1216)
* **docs:** headlines styling breaks in edge cases [#1158](https://github.com/pattern-lab/patternlab-node/issues/1158) ([d8244a2](https://github.com/pattern-lab/patternlab-node/commit/d8244a2d307b0a81d0846491f8c5a12e0ae167a5))
* **patternflyouts:** preventing horizontal scrollbar in pattern flyouts in Edge 18 [#1124](https://github.com/pattern-lab/patternlab-node/issues/1124) ([63300bc](https://github.com/pattern-lab/patternlab-node/commit/63300bc00ee797e38bfdb73fdc7694c188a423dc))
* **patternstate:** added css color for pattern state "inprogress" [#1216](https://github.com/pattern-lab/patternlab-node/issues/1216) ([856bcda](https://github.com/pattern-lab/patternlab-node/commit/856bcda150239928bb5e8719246b97e9fa366468))
* **resetcss:** selector in uikit-workshop [#1109](https://github.com/pattern-lab/patternlab-node/issues/1109) ([6893b7c](https://github.com/pattern-lab/patternlab-node/commit/6893b7cb5478309d4fdab0121edba3921718bd69))
* enable partial build via option ([8aaa533](https://github.com/pattern-lab/patternlab-node/commit/8aaa53398563ade14123c481bf509f9ee0c768f5))
* enable partial build via option ([4b9dbf9](https://github.com/pattern-lab/patternlab-node/commit/4b9dbf9095bfb8bfd2360b310dd7395dbfe3cf98))





# [5.11.0](https://github.com/pattern-lab/patternlab-node/compare/v5.10.2...v5.11.0) (2020-06-28)


### Bug Fixes

* update Viewport Size toggle to better handle async-loaded ishControl data + prevent rendering errors ([b937706](https://github.com/pattern-lab/patternlab-node/commit/b93770669c6f723128ba68e522c9398cc1d2d70c))
* update Webpack config to point to the patched version of preact-dom ([d3660b7](https://github.com/pattern-lab/patternlab-node/commit/d3660b78bc0a74c52ed85b69b023c612b789c318))
* visually hide NavToggle icon text; fix for visual regression after merging down https://github.com/pattern-lab/patternlab-node/pull/1227 ([3a2ad9f](https://github.com/pattern-lab/patternlab-node/commit/3a2ad9f12d83b6d21dcca62e89d944a6a46342f6))
* **docs:** corrected a URL ([26ede14](https://github.com/pattern-lab/patternlab-node/commit/26ede14a6eafe8649cbc6b0076d84f1d323c3e20))
* **docs:** fixed css code for custom patternstates color ([8995241](https://github.com/pattern-lab/patternlab-node/commit/89952416162c01d1e3e05221ce58a7755544131c)), closes [#1216](https://github.com/pattern-lab/patternlab-node/issues/1216)
* **docs:** headlines styling breaks in edge cases [#1158](https://github.com/pattern-lab/patternlab-node/issues/1158) ([d8244a2](https://github.com/pattern-lab/patternlab-node/commit/d8244a2d307b0a81d0846491f8c5a12e0ae167a5))
* **patternflyouts:** preventing horizontal scrollbar in pattern flyouts in Edge 18 [#1124](https://github.com/pattern-lab/patternlab-node/issues/1124) ([63300bc](https://github.com/pattern-lab/patternlab-node/commit/63300bc00ee797e38bfdb73fdc7694c188a423dc))
* **patternstate:** added css color for pattern state "inprogress" [#1216](https://github.com/pattern-lab/patternlab-node/issues/1216) ([856bcda](https://github.com/pattern-lab/patternlab-node/commit/856bcda150239928bb5e8719246b97e9fa366468))
* **resetcss:** selector in uikit-workshop [#1109](https://github.com/pattern-lab/patternlab-node/issues/1109) ([6893b7c](https://github.com/pattern-lab/patternlab-node/commit/6893b7cb5478309d4fdab0121edba3921718bd69))
* enable partial build via option ([8aaa533](https://github.com/pattern-lab/patternlab-node/commit/8aaa53398563ade14123c481bf509f9ee0c768f5))
* enable partial build via option ([4b9dbf9](https://github.com/pattern-lab/patternlab-node/commit/4b9dbf9095bfb8bfd2360b310dd7395dbfe3cf98))





## [5.10.2](https://github.com/pattern-lab/patternlab-node/compare/v5.10.1...v5.10.2) (2020-05-24)


### Bug Fixes

* update link to new PL docs homepage ([831b467](https://github.com/pattern-lab/patternlab-node/commit/831b467c57b9259c32ce3d3ddf366fe1867a48a9))





## [5.10.1](https://github.com/pattern-lab/patternlab-node/compare/v5.10.0...v5.10.1) (2020-05-09)

**Note:** Version bump only for package pl-node





# [5.10.0](https://github.com/pattern-lab/patternlab-node/compare/v5.9.3...v5.10.0) (2020-05-09)


### Bug Fixes

* **docs:** google lighthouse error - bg and text contrast ratio [#1197](https://github.com/pattern-lab/patternlab-node/issues/1197) ([f43978a](https://github.com/pattern-lab/patternlab-node/commit/f43978a3a121b661cfbf763ba72bcda2c36a5d3a))
* **docs:** resolving broken link (new URL) in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([8dc020a](https://github.com/pattern-lab/patternlab-node/commit/8dc020a217b51cfafdd62ceca95fc42811a6c285))
* **docs:** resolving broken link (new URL) in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([f557fdd](https://github.com/pattern-lab/patternlab-node/commit/f557fddeda640d88c7267d9d5fba8e8cc5e07929))
* **docs:** resolving broken link (new URL) in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([0023a91](https://github.com/pattern-lab/patternlab-node/commit/0023a910126a635006c1ad468a412af0e93338fb))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([c9635ec](https://github.com/pattern-lab/patternlab-node/commit/c9635ec2d9eb700b23188d5c72b83b3d16e6deda))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([f56ad39](https://github.com/pattern-lab/patternlab-node/commit/f56ad3951ea0319a43f0b1aeabba0d3ad96c5553))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([cae9420](https://github.com/pattern-lab/patternlab-node/commit/cae94208c52e4068430e048e729f4ff97847715a))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([84138c3](https://github.com/pattern-lab/patternlab-node/commit/84138c36cdfe5b9a38b34e32b177a0416b077716))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([374c103](https://github.com/pattern-lab/patternlab-node/commit/374c103a59504ba239b16680f86a89b4d95e304f))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([cb0fcdb](https://github.com/pattern-lab/patternlab-node/commit/cb0fcdb5ad8504f9d78d4d5e040afa408aa2c356))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([48de8c2](https://github.com/pattern-lab/patternlab-node/commit/48de8c2e134a61c0b4440375254bc9590a3e2563))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([363f22c](https://github.com/pattern-lab/patternlab-node/commit/363f22c643239ef4ca48d6f5942111604fda5ead))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([487cc78](https://github.com/pattern-lab/patternlab-node/commit/487cc783388043ec16ab1e54a3bfd8490038d058))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([571017f](https://github.com/pattern-lab/patternlab-node/commit/571017ffafa2cf6e8fa01b7ea7effc88922b05d1))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([420e829](https://github.com/pattern-lab/patternlab-node/commit/420e8293c033557ede073bc13e68955a450a3c8e))
* **docs:** resolving broken links in new docs site [#1192](https://github.com/pattern-lab/patternlab-node/issues/1192) ([b4eb12e](https://github.com/pattern-lab/patternlab-node/commit/b4eb12e68ceb402964a7e303610e5b0c008876ba))
* Contribution guidelines should refer to yarn ([c30cc81](https://github.com/pattern-lab/patternlab-node/commit/c30cc81a3e155072774438304b73d58b6635876d))
* **uikitworkshop:** preventing cropping pattern parts [#1174](https://github.com/pattern-lab/patternlab-node/issues/1174) ([6a67d03](https://github.com/pattern-lab/patternlab-node/commit/6a67d039048129e9837c3b6eb3e195ed2e86a815))





## [5.9.3](https://github.com/pattern-lab/patternlab-node/compare/v5.9.2...v5.9.3) (2020-05-01)


### Bug Fixes

* **plugintabs:** enabling multiple file formats [#1163](https://github.com/pattern-lab/patternlab-node/issues/1163) ([bb5e817](https://github.com/pattern-lab/patternlab-node/commit/bb5e8179e6b8553a6e1af0bede26db412b6c0b68))
* adjust UIKit Nav updates to account for the noViewAll config variation ([73eac97](https://github.com/pattern-lab/patternlab-node/commit/73eac976461f4e587b0c30668942c4895aea319f))
* make sure the top-level Dropdown menus always open/close ([7a8b418](https://github.com/pattern-lab/patternlab-node/commit/7a8b418bfcbd200ef8b2802b1a07964a9995bf9f))
* only allow one top level nav item to be open at a time while rendering as a dropdown menu ([409bef3](https://github.com/pattern-lab/patternlab-node/commit/409bef37165260d9b728013ac33e7aa67541c832))
* re-try Netlify preview to debug local vs prod rendering differences ([6da41a1](https://github.com/pattern-lab/patternlab-node/commit/6da41a14feea034f891c745dfeb062fa3b196235))
* Update dependency on twing JS engine ([cfe88c6](https://github.com/pattern-lab/patternlab-node/commit/cfe88c6cdbf2219b9955eaa0ffcfc0e4a7683511))
* **cli:** fix test script glob ([ff18eb5](https://github.com/pattern-lab/patternlab-node/commit/ff18eb51ce24fc5423b009168e85ede366069139))





## [5.9.2](https://github.com/pattern-lab/patternlab-node/compare/v5.9.1...v5.9.2) (2020-04-24)

**Note:** Version bump only for package pl-node





## [5.9.1](https://github.com/pattern-lab/patternlab-node/compare/v5.9.0...v5.9.1) (2020-04-24)


### Bug Fixes

* **cli:** ensure specified directory exists prior to scaffold ([cc3b696](https://github.com/pattern-lab/patternlab-node/commit/cc3b69624d486c94ee3b1f4b1bbb0334a514fa59))





# [5.9.0](https://github.com/pattern-lab/patternlab-node/compare/v5.8.0...v5.9.0) (2020-04-24)


### Bug Fixes

* **cli:** set current working directory before scaffolded npm init ([6d2186d](https://github.com/pattern-lab/patternlab-node/commit/6d2186d8e8a74634198a4474ca8ae83221dd70a9))
* **core:** do not warn about uikit-polyfills ([6bb68e7](https://github.com/pattern-lab/patternlab-node/commit/6bb68e763769969546542bf7aaf6d1f4235c6622))
* actually exit build when Twig render fails ([5d28a24](https://github.com/pattern-lab/patternlab-node/commit/5d28a24a53011396289c1e29e0a715cd82470185))
* Update packages/engine-twig-php/lib/engine_twig_php.js ([c67d50e](https://github.com/pattern-lab/patternlab-node/commit/c67d50ebb5d69816b7514e85f129f8ecde984ad3))


### Features

* **docs:** yarnify ([5a47dc7](https://github.com/pattern-lab/patternlab-node/commit/5a47dc7b90dc5c43c12a51143b41943dcbd8564c))
* **README:** add netlify badges ([941df8a](https://github.com/pattern-lab/patternlab-node/commit/941df8a59b6b75bc1255646005f329e40be68106))





# [5.8.0](https://github.com/pattern-lab/patternlab-node/compare/v5.7.2...v5.8.0) (2020-04-03)


### Bug Fixes

* the namespace notation should not be mixed with PatternLab shorthand pattern naming & name is not defined in the textarea macro ([8250fe8](https://github.com/pattern-lab/patternlab-node/commit/8250fe88231d03735424d597eae40496da2cb48c))
* Updated the README to reflect which issues are resolved. ([d90c3c4](https://github.com/pattern-lab/patternlab-node/commit/d90c3c4605f9a5bcd1153996e3f4d1a17d58bd92))


### Features

* switch engine-twig to use twing rather than node-twig ([daca95c](https://github.com/pattern-lab/patternlab-node/commit/daca95c4ffa48916fb6c67c5184bde9b624acd76))





## [5.7.2](https://github.com/pattern-lab/patternlab-node/compare/v5.7.1...v5.7.2) (2020-03-24)


### Bug Fixes

* update iframe resizer UI to be hidden when iframe is full width ([9797c1a](https://github.com/pattern-lab/patternlab-node/commit/9797c1a047d746d21b88a1f57b57f618a03a54df))





## [5.7.1](https://github.com/pattern-lab/patternlab-node/compare/v5.7.0...v5.7.1) (2020-02-24)


### Bug Fixes

* update twig-renderer ([46f53b7](https://github.com/pattern-lab/patternlab-node/commit/46f53b79f8bb0bb64a9c55fd32f29459cea6e28c))





# [5.7.0](https://github.com/pattern-lab/patternlab-node/compare/v5.6.0...v5.7.0) (2020-02-17)


### Features

* **cli:** make options more user friendly ([ad845b3](https://github.com/pattern-lab/patternlab-node/commit/ad845b394ef81f90895ebb5bc6f12cc608e5e3d4))





# [5.6.0](https://github.com/pattern-lab/patternlab-node/compare/v5.5.0...v5.6.0) (2020-01-18)


### Bug Fixes

* a11y fix on text contrast ([6d75b22](https://github.com/pattern-lab/patternlab-node/commit/6d75b226ce27228025b2915e5d402f7080faee31))
* a11y issue on a missing description of that complementary icon ([4f13807](https://github.com/pattern-lab/patternlab-node/commit/4f13807cb93df33435088de3a51170b9c4515889))


### Features

* pass additional configuration into twig-php engine ([dff5a78](https://github.com/pattern-lab/patternlab-node/commit/dff5a7830918fa46e2692d9f9daed4121f803461))






# [5.5.0](https://github.com/pattern-lab/patternlab-node/compare/v5.4.2...v5.5.0) (2019-12-19)


### Features

* upgrade Twig to use new filter, map, reduce ([4218a5a](https://github.com/pattern-lab/patternlab-node/commit/4218a5a04b06027548afd9f417486297dd25fef8))





## [5.4.2](https://github.com/pattern-lab/patternlab-node/compare/v5.4.1...v5.4.2) (2019-11-27)

**Note:** Version bump only for package pl-node-pr





## [5.4.1](https://github.com/pattern-lab/patternlab-node/compare/v5.4.0...v5.4.1) (2019-11-26)


### Bug Fixes

* temp workaround to address instance where the latest version of Edge supports ES modules but NOT Custom Elements ([ada3d82](https://github.com/pattern-lab/patternlab-node/commit/ada3d829019345fd33ed949f306972efdcb4fa57))





# [5.4.0](https://github.com/pattern-lab/patternlab-node/compare/v5.3.3...v5.4.0) (2019-11-26)


### Bug Fixes

* re-add popstate listener ([6dbbd6a](https://github.com/pattern-lab/patternlab-node/commit/6dbbd6aae3709cc17544c12dd10588120eb9e71a))
* **script:** remove quotes around starterkit ([e4897fb](https://github.com/pattern-lab/patternlab-node/commit/e4897fb6e4d4cd0985ab72397abd03ff04be514b))
* add a new method to check if PL is currently compiling + add new method to get the config PL is using ([26e886c](https://github.com/pattern-lab/patternlab-node/commit/26e886c93db5d135c91de648724f7278c4d5b3e9))
* check if dependency graph file exists before trying to remove ([f9af6a9](https://github.com/pattern-lab/patternlab-node/commit/f9af6a95025a22041e7ff8a4bfb19e4727385e98))
* comment out example config to disable viewAll links ([ddb3fad](https://github.com/pattern-lab/patternlab-node/commit/ddb3fad5770d1d66432c4b583ae9af09a3a47d48))


### Features

* add the ability to disable Pattern Lab viewall links in the navigation ([156e609](https://github.com/pattern-lab/patternlab-node/commit/156e609a92e7f7e7ebd8f4f5cd77b5d695db8bad))
* major improvements to local UIKit workflow ([4dc9173](https://github.com/pattern-lab/patternlab-node/commit/4dc9173a5a44b422e9677824de3728048b7c4f05))
* test adding cross-env to Twig Edition test ([3f8bb01](https://github.com/pattern-lab/patternlab-node/commit/3f8bb01bc4e96a0aba61c213ea1619c02593defc))





## [5.3.3](https://github.com/pattern-lab/patternlab-node/compare/v5.3.2...v5.3.3) (2019-11-22)


### Bug Fixes

* simplify overflow fix ([378cf42](https://github.com/pattern-lab/patternlab-node/commit/378cf4282a3e5b4f597287eb538270e3358c8c69))
* testing potential FF fix for https://github.com/pattern-lab/patternlab-node/issues/1100 ([613bba1](https://github.com/pattern-lab/patternlab-node/commit/613bba104f2082be507938db78f1db7a07f6b8be))






## [5.3.2](https://github.com/pattern-lab/patternlab-node/compare/v5.3.1...v5.3.2) (2019-11-14)

**Note:** Version bump only for package pl-node





## [5.3.1](https://github.com/pattern-lab/patternlab-node/compare/v5.3.0...v5.3.1) (2019-11-13)


### Bug Fixes

* CSS fix to properly highlight the correct active page / link in the Nav; improve dropdown open / close animation ([ec4ab84](https://github.com/pattern-lab/patternlab-node/commit/ec4ab84ddc8007796c9012a3f493822d76f039a7))
* small UI fixes for the sticky Tabs header on smaller screens + drawer content collapsing on smaller screens + better handling of Nav link cleanup when changing pages ([347e2fe](https://github.com/pattern-lab/patternlab-node/commit/347e2fe29a78a1d168005a07c656b4f9f1124c7f))
* tweak header and drawer padding when viewing on a device with curved edges ([98e9baf](https://github.com/pattern-lab/patternlab-node/commit/98e9baf649eceb9124218a924b6b08097b910e86))
* uikit fixes and minor CSS updates intended for the v5.3.0 release ([26c4ced](https://github.com/pattern-lab/patternlab-node/commit/26c4ceddaae09fa4fa4873f092c924274498c5da))





# [5.3.0](https://github.com/pattern-lab/patternlab-node/compare/v5.2.0...v5.3.0) (2019-11-13)


### Bug Fixes

* add PluginTab workaround for Safari ([2fa9367](https://github.com/pattern-lab/patternlab-node/commit/2fa936769be65484af52f242dca2536a3382462c))
* **core:** re-add cleanPublic fix ([c100bbc](https://github.com/pattern-lab/patternlab-node/commit/c100bbca3f339e9132acb9c482e98c1c8a66b8b5))
* **plugin-tab:** defensively call addPanels ([b82bd12](https://github.com/pattern-lab/patternlab-node/commit/b82bd129fdbe48de95b62d75fb7fe95cea896b7e))
* port over missing UIKit Sass that wasn't added in the original PR ([f7659e6](https://github.com/pattern-lab/patternlab-node/commit/f7659e64d0eee13be20921dd5afc48ac20ae93e6))


### Features

* port latest UIKit updates + fixes upstream ([d07952c](https://github.com/pattern-lab/patternlab-node/commit/d07952cb07e3792b995dda2e589262ecf4153fdc))





# [5.2.0](https://github.com/pattern-lab/patternlab-node/compare/v5.1.0...v5.2.0) (2019-11-12)


### Bug Fixes

* **deploy:** add setup command ([7c1d8d1](https://github.com/pattern-lab/patternlab-node/commit/7c1d8d14842a467bb301e2ede2ec83074ff35ae2))
* add missing $ ([c95a06e](https://github.com/pattern-lab/patternlab-node/commit/c95a06ece78631b068f8721666caf33452e57a7a))
* address bug causing viewport width to progressively decrease in size when resizing your screen / refreshing on certain devices ([41b11af](https://github.com/pattern-lab/patternlab-node/commit/41b11af8aaaf066fcf99abd2513eae8706122d32))
* configure the Logo's `altText` config option when used as an HTML attribute ([ade34a2](https://github.com/pattern-lab/patternlab-node/commit/ade34a29435f5112f0449ad020bee7e9dc2c81e1))
* fix classname typo ([da3c5f1](https://github.com/pattern-lab/patternlab-node/commit/da3c5f144d22b1ac3ad99680a264433d4438ebb2))
* temp workaround to fix content exceeding the height of drawer container ([435243c](https://github.com/pattern-lab/patternlab-node/commit/435243cbfbd000a7d96a0e9fa7beff1a988ede64))
* update drawer UI to not collapse content on smaller screen sizes ([7147085](https://github.com/pattern-lab/patternlab-node/commit/71470856b8b389421348366afd247a599d1e9c86))
* update package.json description in `@pattern-lab/uikit-polyfills` ([22fc44a](https://github.com/pattern-lab/patternlab-node/commit/22fc44a4b3683753a469a98abfcdad8f1234f28a))
* **engine_twig_php:** Allow additional flexibility with twig namespaces. ([07bfaa3](https://github.com/pattern-lab/patternlab-node/commit/07bfaa35a00ff62fd2016cc9f34e09cf5af36559))


### Features

* add lit-element, basic Typescript support to Webpack ([611f705](https://github.com/pattern-lab/patternlab-node/commit/611f705be85eea8a31091169750d64e988798cee))
* add local copy of new Slotify library till published to NPM ([63b9d83](https://github.com/pattern-lab/patternlab-node/commit/63b9d833908151ce5cb5aa5184c72254125c7ed1))
* add new <pl-button> component to make Button-like styles more reusable ([5e7b014](https://github.com/pattern-lab/patternlab-node/commit/5e7b0140622eb89154c38925769a6def6d669fb3))
* add new <pl-icon> component ([e8ce2a9](https://github.com/pattern-lab/patternlab-node/commit/e8ce2a927365b8d5316a7d8229c979ff31b04907))
* add support for auto-closing Nav when clicking inside of the rendered iframe ([9d602fe](https://github.com/pattern-lab/patternlab-node/commit/9d602fe335a5d3b5bca5cac258c2465934d9a46a))
* add support for optional chaining syntax via Babel plugin ([c8886b6](https://github.com/pattern-lab/patternlab-node/commit/c8886b6d9d91fea246fa3ab7947f289509dc26d5))
* major refactoring + UI updates to address cross browser support; UI cleanup and conversion of the majority of the remaining components over to lit-element ([2ff8e1c](https://github.com/pattern-lab/patternlab-node/commit/2ff8e1c98cdd02e8077064c48eca5f7754a3db02))
* refactor + convert pl-toggle-info to lit-element ([85cd9c5](https://github.com/pattern-lab/patternlab-node/commit/85cd9c50ca814066bf999badf2071d84964f00cc))
* refactor + convert pl-toggle-layout to lit-element ([46009d9](https://github.com/pattern-lab/patternlab-node/commit/46009d91b1cb9ed613baa5a7626cba4f42883465))
* refactor + convert pl-toggle-theme to lit-element ([95a3b21](https://github.com/pattern-lab/patternlab-node/commit/95a3b21a89dacd2d5b4df8c134ce438d4efdbd04))
* refactor Drawer to render via lit-element + massively improve rendering performance ([28d47eb](https://github.com/pattern-lab/patternlab-node/commit/28d47eb3cbbce038204203e786e5188b4cefe64f))
* remove mixin that was causing outlines to be removed from default UI styles ([622ed76](https://github.com/pattern-lab/patternlab-node/commit/622ed76d435b3b2e31e412266c3090506f98051b))
* temp add unsafe-svg directive till upstream PR merged ([34de61c](https://github.com/pattern-lab/patternlab-node/commit/34de61ccd9c7bb3b48ca5ef386a87efc8e84babc))
* update the Nav design to not bold the active item in order to not shift the layout ([0eda431](https://github.com/pattern-lab/patternlab-node/commit/0eda4312ba9f4c61afa6322c3ff45f9cda0efc9e))
* update Webpack config to use the latest Style Loader + new SVG icon system ([2ed70e7](https://github.com/pattern-lab/patternlab-node/commit/2ed70e79d8656c7314d8b3109aa1c34160ad24f9))






# [5.1.0](https://github.com/pattern-lab/patternlab-node/compare/v5.0.2...v5.1.0) (2019-10-29)


### Features

* **config:** add new default pattern export options ([a7487a0](https://github.com/pattern-lab/patternlab-node/commit/a7487a0681cb11e6f3c5c8eaefd62e5648ad5ea3))





## [5.0.2](https://github.com/pattern-lab/patternlab-node/compare/v5.0.1...v5.0.2) (2019-10-28)


### Bug Fixes

* **uikit-workshop:** add template files to published bundle ([9005fce](https://github.com/pattern-lab/patternlab-node/commit/9005fcee9e129fb41d509f706195e1437bddc710))
* **uikit-workshop:** add webpack config to published bundle ([060a573](https://github.com/pattern-lab/patternlab-node/commit/060a573cbddce9ee3d270d39337d0c8cac8372fa))





## [5.0.1](https://github.com/pattern-lab/patternlab-node/compare/v5.0.0...v5.0.1) (2019-10-28)


### Bug Fixes

* add missing “dist” folder to array of files / folders published to NPM ([8829429](https://github.com/pattern-lab/patternlab-node/commit/88294296c438352570befd2eb6b9e1ca2ae3b750))





# [5.0.0](https://github.com/pattern-lab/patternlab-node/compare/v3.0.0-beta.3...v5.0.0) (2019-10-25)


### Bug Fixes

* **1049:** Treat folders like patterns only if they're subfolders of pattern groupings ([4eb79ab](https://github.com/pattern-lab/patternlab-node/commit/4eb79ab48b335a35b2e5ed3b7053974b8e8bb6b6))
* **cli:** add custom install logic to edition-node ([f04fd26](https://github.com/pattern-lab/patternlab-node/commit/f04fd266429cd806987dab747e6d69bff9b926a4))
* **cli:** allow any package to be installed as a starterkit ([d2aa1be](https://github.com/pattern-lab/patternlab-node/commit/d2aa1be810a0a7473dcc52391a2263dacfdda0b8)), closes [#1067](https://github.com/pattern-lab/patternlab-node/issues/1067)
* **cli:** merge config arrays via overwrite instead of concatenate ([42e5f7b](https://github.com/pattern-lab/patternlab-node/commit/42e5f7b42a26b4fc1f262c68ee4b474b546f2eac))
* **cli:** proper path resolution to helpers ([a18fe5e](https://github.com/pattern-lab/patternlab-node/commit/a18fe5ef4d1c074a5eba8bfa255ebbee2261bf74))
* **cli:** re-order and clarify engines ([e39e301](https://github.com/pattern-lab/patternlab-node/commit/e39e301a33306c6615fabf64262f1893ca682b97))
* **core:** allow plugin resolution to follow normal algorithm ([3f6b83b](https://github.com/pattern-lab/patternlab-node/commit/3f6b83be080c88aec1d8b73bececb76f0f57a79d))
* **core:** find plugins from config only and with simpler args ([fe7351c](https://github.com/pattern-lab/patternlab-node/commit/fe7351cba346425512cbb2ef3a1b7728ab06ae60))
* **deploy:** add setup command ([74dd314](https://github.com/pattern-lab/patternlab-node/commit/74dd3142bf48873a9f1ec4e8dccb8aa2fef9001d))
* **engine_twig_php:** Pseudo patterns Twig PHP ([226aa8b](https://github.com/pattern-lab/patternlab-node/commit/226aa8bbaaf5e418530ccf54a28f6c5657ee6dea)), closes [#1045](https://github.com/pattern-lab/patternlab-node/issues/1045)
* **engine_twig_php:** Twig incremental rebuilds ([1ade945](https://github.com/pattern-lab/patternlab-node/commit/1ade9451840b2645706a0b01129e2b697dc22d4b)), closes [#1015](https://github.com/pattern-lab/patternlab-node/issues/1015)
* **engine_twig_php:** Twig incremental rebuilds ([5d33f24](https://github.com/pattern-lab/patternlab-node/commit/5d33f24f156ebe50900701513a855de7de608dcf)), closes [#1015](https://github.com/pattern-lab/patternlab-node/issues/1015)
* **lerna:** typo in config ([525a47b](https://github.com/pattern-lab/patternlab-node/commit/525a47b51fba91c1bf5b7439735f48eb7dfa073e))
* **lint:** Use const instead of var ([ad1e782](https://github.com/pattern-lab/patternlab-node/commit/ad1e782ef71295eb610f56d019eaa35499fb3f85))
* **plugin:** correct spelling error and function locations ([d4abd88](https://github.com/pattern-lab/patternlab-node/commit/d4abd88cb017550002407241b5045a2ad1adb1dc))
* **plugin-tab:** bump lodash from 4.17.5 to 4.17.15 in /packages/plugin-tab ([#1081](https://github.com/pattern-lab/patternlab-node/issues/1081)) ([3f89dda](https://github.com/pattern-lab/patternlab-node/commit/3f89dda1685874e251f9777f969c0943e0080881))
* **plugin-tab:** handle params correctly ([d248993](https://github.com/pattern-lab/patternlab-node/commit/d2489939bb0db1a1d67b0e7f47dfb1838b88b0a0))
* **starterkit:** add css output and build command ([ccb2d35](https://github.com/pattern-lab/patternlab-node/commit/ccb2d3569b741220324a3fa738ab3d4d2eb97ffe))
* add better pre-rendering support ([8ecd615](https://github.com/pattern-lab/patternlab-node/commit/8ecd6159a89232f42e0a9dc3c688b6e21de8fc30))
* add eslint fixes ([00d7bbe](https://github.com/pattern-lab/patternlab-node/commit/00d7bbe319ea77a6ee8cc9cd0348856feaaf13ad))
* add missing @babel/runtime package to address silent error getting thrown on Travis ([1918d04](https://github.com/pattern-lab/patternlab-node/commit/1918d042d7e90cc8aaa2fdfcd8649961c0a5dd50))
* add missing preact-render-to-string library ([881296a](https://github.com/pattern-lab/patternlab-node/commit/881296a2c256424beac28bd560c5b1a5e1fed005))
* add repo info to root package.json so Auto knows what repo to configure for ([85142e8](https://github.com/pattern-lab/patternlab-node/commit/85142e8e94549edd7980459e5975d0639c34864d))
* address unrelated eslint errors from PL core ([6ada00d](https://github.com/pattern-lab/patternlab-node/commit/6ada00d396eb436837f7453664bfa50522a2ec10))
* correct typo in build logging ([96d989f](https://github.com/pattern-lab/patternlab-node/commit/96d989f8869630ba9f59705bfca66755f20e35ab))
* fall back to seeing the current pattern's query string to `all` or the defaultPattern value if undefined when the iframe page initially loads ([a368459](https://github.com/pattern-lab/patternlab-node/commit/a3684590fca02cf96b99421b87a0ad0a711893ad))
* fix incorrect Webpack version in package.json ([9788e89](https://github.com/pattern-lab/patternlab-node/commit/9788e8977921e31fe43f2a1ec19d4684dd4709c5))
* fix issue with viewport height exceeding the space available ([95cd1cf](https://github.com/pattern-lab/patternlab-node/commit/95cd1cfa57f086ecb84ac2e996ecda81f0c6a1a6))
* fix Prism.js typo so languages not found / supported don't throw a JS error ([a8c19f9](https://github.com/pattern-lab/patternlab-node/commit/a8c19f9f9b11d4abbdcd9e573fb0cb418d665660))
* fix Twig Edition examples by adding missing Twig namespaces to config ([b4c20ef](https://github.com/pattern-lab/patternlab-node/commit/b4c20ef88ee0d3010760584c6f05ff7f92b711a6))
* minor CSS fixes + fresh prod build ([8ac2c1f](https://github.com/pattern-lab/patternlab-node/commit/8ac2c1fa1c7558ed2ac50755f599a438d682ee2a))
* re-enable displaying the top level `All` link if PL isn't configured to hide this specific link in the ishControlsHide config option. Addresses [#1048](https://github.com/pattern-lab/patternlab-node/issues/1048) ([6bb4e1a](https://github.com/pattern-lab/patternlab-node/commit/6bb4e1ac6f38b47f93030c8c5bca62d5db2132e4))
* re-enable using the defaultPattern config for the initial iframe page load if defined ([d645ea1](https://github.com/pattern-lab/patternlab-node/commit/d645ea15150061d7ad13741d2dc37b12b9786411))
* regenerate fresh UIKit build after fixing main JS issues ([9ea34d2](https://github.com/pattern-lab/patternlab-node/commit/9ea34d2efe43cafacb3729ac113121ba51126344))
* Rename Handlebars and Nunjucks extension setting to "extend" ([74e5af2](https://github.com/pattern-lab/patternlab-node/commit/74e5af28c4e714fdfc1db535b94c52f3dc14a3a4))
* squashing minor UI bugs ([a8a606c](https://github.com/pattern-lab/patternlab-node/commit/a8a606cfb224f7041f53ff5026a84e13fa17914c))
* temporarily disable Random and Disco viewport controls until the full JS logic for these is re-enabled ([14b9a19](https://github.com/pattern-lab/patternlab-node/commit/14b9a19e4dee9462f3784eae28066893cc893624))
* temporarily downgrade Preact version so tooltip used for displaying viewport sizes renders correctly ([52dcf85](https://github.com/pattern-lab/patternlab-node/commit/52dcf85e756ee171ca993288d98f5b5ef9a0a24b))
* update autoprefixer browserslist config to address warning messages ([5e52f2b](https://github.com/pattern-lab/patternlab-node/commit/5e52f2b0ed02e2002ca867368636c3c0dc79ff0a))
* update initial PL iframe path default ([a26fbb9](https://github.com/pattern-lab/patternlab-node/commit/a26fbb956e13901d1751c435b76de65637191ca4))
* update Javascript to address merge conflict issue with previous PR merge / recent release ([cf2ecc1](https://github.com/pattern-lab/patternlab-node/commit/cf2ecc154383c3e8abd56dc88484370bc58ac30b))
* update styles for pattern state dots ([7728acc](https://github.com/pattern-lab/patternlab-node/commit/7728accc9a6e5cd83be451f7d74e522dfe721cad))
* update the default pattern that displays in the Handlebars demo ([ff1d85f](https://github.com/pattern-lab/patternlab-node/commit/ff1d85f2852fc4f210841e8e0aaf14b55165ce58))
* **starterkit:** remove config file ([f90e38a](https://github.com/pattern-lab/patternlab-node/commit/f90e38aa873dcff0dd08fe4dabc3b71bf95080b6))
* **starterkit:** use handlebars meta files ([d8f5e12](https://github.com/pattern-lab/patternlab-node/commit/d8f5e12471bd783bd3755626701ecc17669fc761))
* updates to address eslint / prettier issues ([d945acc](https://github.com/pattern-lab/patternlab-node/commit/d945acc13b8e4e36f3815b017fbc12266c323d1f))
* updates to fix eslint / prettier issues; update packages/core to reuse root .eslintrc.js file ([5b7a057](https://github.com/pattern-lab/patternlab-node/commit/5b7a057d46ccd16b5832af1441030c7b76f237a8))
* use 100% of the screen available when JS is disabled / the first time the iframe loads up ([c0c5bff](https://github.com/pattern-lab/patternlab-node/commit/c0c5bff7a63b157d5b81dc2bcecee9e732ecfd4e))
* **uikit:** clear out "404" responses when loading tabs ([73874b1](https://github.com/pattern-lab/patternlab-node/commit/73874b1b0b66ca6425c2b74331d417efdb529e2e))
* **uikit-workshop:** fix merge problem ([d245b3b](https://github.com/pattern-lab/patternlab-node/commit/d245b3bca044c29f281052bf2feb95eeffafcf6b))


### Features

* **core:** invoke registered plugin hooks ([a54d775](https://github.com/pattern-lab/patternlab-node/commit/a54d7753b6939fe6a58da543f4fb34f64dd8901a))
* **edition-node:** switch to engine-handlebars ([b481e22](https://github.com/pattern-lab/patternlab-node/commit/b481e22dc1f41ddd4da709621640a15190fba257))
* **engine-handlebars:** Default location for helpers, like engine-nunjucks ([11c4180](https://github.com/pattern-lab/patternlab-node/commit/11c41805e0c3dbebb7109719c4f3c780d32feab5))
* **engine-handlebars:** Demonstration of custom Handlebars helper ([f330b5b](https://github.com/pattern-lab/patternlab-node/commit/f330b5bca72f2f34bfafe5c2c64e6b0b8823eb1c))
* **engine-handlebars:** Document the Helpers feature ([a01e040](https://github.com/pattern-lab/patternlab-node/commit/a01e040429a7f77dfeb28d67c690e835b97881de))
* **engine-handlebars:** Load Handlebars helpers specified in the config ([a12df36](https://github.com/pattern-lab/patternlab-node/commit/a12df36d2a644dfac8ded1dfd94b987e99c29d79))
* **engine-nunjucks:** Configurable extension locations; Use usePatternlabConfig() ([e54e3b3](https://github.com/pattern-lab/patternlab-node/commit/e54e3b3d48f934d3a4d44b9f4ff262f742a4aaf9))
* **engine-react:** set package to private ([3aea881](https://github.com/pattern-lab/patternlab-node/commit/3aea8815f19df5b527cdda0b75cf99a9a8c3bc1e))
* **plugin-tab:** pivot to using hook functions ([d4b2598](https://github.com/pattern-lab/patternlab-node/commit/d4b25984fc2a2646cc1876a5c635f57593c35f09))
* **plugin-tab, core:** initial plugin hook exploration ([2f3d39a](https://github.com/pattern-lab/patternlab-node/commit/2f3d39ac6b125ad4c6b872e27ee224ce2ea33a12))
* **starterkits:** add starterkit-handlebars-demo ([384d2cf](https://github.com/pattern-lab/patternlab-node/commit/384d2cfa3440c1e6f456d39f56ca6381f82f7689))
* **uikit-workshop:** add plugin-loader ([fc966d6](https://github.com/pattern-lab/patternlab-node/commit/fc966d6b151e24055bc2f4146d6a90b5fb392765))
* introduce netlify preview ([6c5d332](https://github.com/pattern-lab/patternlab-node/commit/6c5d332479fb6836bd8bd5530a074d13440f8ae4))
* remove pre-built uikit dist folder and switch to auto-building when bootstrapping OR when publishing to NPM ([b5dd553](https://github.com/pattern-lab/patternlab-node/commit/b5dd5538ee00ddf1da321851865fa1c223cedb43))
* switch to Yarn + Yarn workspaces ([f4c4ec3](https://github.com/pattern-lab/patternlab-node/commit/f4c4ec33cd30d372c87ffa904fbe7d5b819ee14e))
* update Node to v12 ([fcbb970](https://github.com/pattern-lab/patternlab-node/commit/fcbb970648cdd775c9a88078f14c1f24c5b62d73))


### Reverts

* don't flatten folders containing only one item inside ([77f1f46](https://github.com/pattern-lab/patternlab-node/commit/77f1f46595328bd96fba46347b532295c65802d1))


### BREAKING CHANGES

* **core:** plugins now use async functions instead of events
* **plugin-tab:** event based listeners replaced with functions
* **cli:** previously, we concatenated arrays, which is unlikely to be intended
* **edition-node:** use handlebars over mustache
