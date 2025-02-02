# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [5.0.2](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/v5.0.1...v5.0.2) (2019-10-28)


### Bug Fixes

* **uikit-workshop:** add template files to published bundle ([9005fce](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/9005fcee9e129fb41d509f706195e1437bddc710))
* **uikit-workshop:** add webpack config to published bundle ([060a573](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/060a573cbddce9ee3d270d39337d0c8cac8372fa))





## [5.0.1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/v5.0.0...v5.0.1) (2019-10-28)


### Bug Fixes

* add missing “dist” folder to array of files / folders published to NPM ([8829429](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/88294296c438352570befd2eb6b9e1ca2ae3b750))





# [5.0.0](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/v3.0.0-beta.3...v5.0.0) (2019-10-25)


### Bug Fixes

* add better pre-rendering support ([8ecd615](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/8ecd6159a89232f42e0a9dc3c688b6e21de8fc30))
* add missing @babel/runtime package to address silent error getting thrown on Travis ([1918d04](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/1918d042d7e90cc8aaa2fdfcd8649961c0a5dd50))
* add missing preact-render-to-string library ([881296a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/881296a2c256424beac28bd560c5b1a5e1fed005))
* fall back to seeing the current pattern's query string to `all` or the defaultPattern value if undefined when the iframe page initially loads ([a368459](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a3684590fca02cf96b99421b87a0ad0a711893ad))
* fix incorrect Webpack version in package.json ([9788e89](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/9788e8977921e31fe43f2a1ec19d4684dd4709c5))
* fix issue with viewport height exceeding the space available ([95cd1cf](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/95cd1cfa57f086ecb84ac2e996ecda81f0c6a1a6))
* fix Prism.js typo so languages not found / supported don't throw a JS error ([a8c19f9](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a8c19f9f9b11d4abbdcd9e573fb0cb418d665660))
* minor CSS fixes + fresh prod build ([8ac2c1f](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/8ac2c1fa1c7558ed2ac50755f599a438d682ee2a))
* re-enable displaying the top level `All` link if PL isn't configured to hide this specific link in the ishControlsHide config option. Addresses [#1048](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/issues/1048) ([6bb4e1a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/6bb4e1ac6f38b47f93030c8c5bca62d5db2132e4))
* re-enable using the defaultPattern config for the initial iframe page load if defined ([d645ea1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/d645ea15150061d7ad13741d2dc37b12b9786411))
* regenerate fresh UIKit build after fixing main JS issues ([9ea34d2](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/9ea34d2efe43cafacb3729ac113121ba51126344))
* squashing minor UI bugs ([a8a606c](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a8a606cfb224f7041f53ff5026a84e13fa17914c))
* temporarily disable Random and Disco viewport controls until the full JS logic for these is re-enabled ([14b9a19](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/14b9a19e4dee9462f3784eae28066893cc893624))
* temporarily downgrade Preact version so tooltip used for displaying viewport sizes renders correctly ([52dcf85](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/52dcf85e756ee171ca993288d98f5b5ef9a0a24b))
* update autoprefixer browserslist config to address warning messages ([5e52f2b](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/5e52f2b0ed02e2002ca867368636c3c0dc79ff0a))
* **plugin:** correct spelling error and function locations ([d4abd88](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/d4abd88cb017550002407241b5045a2ad1adb1dc))
* **uikit:** clear out "404" responses when loading tabs ([73874b1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/73874b1b0b66ca6425c2b74331d417efdb529e2e))
* **uikit-workshop:** fix merge problem ([d245b3b](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/d245b3bca044c29f281052bf2feb95eeffafcf6b))
* update initial PL iframe path default ([a26fbb9](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a26fbb956e13901d1751c435b76de65637191ca4))
* update Javascript to address merge conflict issue with previous PR merge / recent release ([cf2ecc1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/cf2ecc154383c3e8abd56dc88484370bc58ac30b))
* update styles for pattern state dots ([7728acc](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/7728accc9a6e5cd83be451f7d74e522dfe721cad))
* updates to fix eslint / prettier issues; update packages/core to reuse root .eslintrc.js file ([5b7a057](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/5b7a057d46ccd16b5832af1441030c7b76f237a8))
* use 100% of the screen available when JS is disabled / the first time the iframe loads up ([c0c5bff](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/c0c5bff7a63b157d5b81dc2bcecee9e732ecfd4e))


### Features

* **uikit-workshop:** add plugin-loader ([fc966d6](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/fc966d6b151e24055bc2f4146d6a90b5fb392765))
* remove pre-built uikit dist folder and switch to auto-building when bootstrapping OR when publishing to NPM ([b5dd553](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/b5dd5538ee00ddf1da321851865fa1c223cedb43))


### Reverts

* don't flatten folders containing only one item inside ([77f1f46](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/77f1f46595328bd96fba46347b532295c65802d1))






## [1.0.7](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.6...@pattern-lab/uikit-workshop@1.0.7) (2019-10-14)

**Note:** Version bump only for package @pattern-lab/uikit-workshop






## [1.0.6](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.5...@pattern-lab/uikit-workshop@1.0.6) (2019-10-14)

**Note:** Version bump only for package @pattern-lab/uikit-workshop






## [1.0.2](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.1...@pattern-lab/uikit-workshop@1.0.2) (2019-08-23)


### Bug Fixes

* add better pre-rendering support ([8ecd615](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/8ecd615))
* add missing @babel/runtime package to address silent error getting thrown on Travis ([1918d04](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/1918d04))
* add missing preact-render-to-string library ([881296a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/881296a))
* fix incorrect Webpack version in package.json ([9788e89](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/9788e89))
* fix issue with viewport height exceeding the space available ([95cd1cf](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/95cd1cf))
* minor CSS fixes + fresh prod build ([8ac2c1f](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/8ac2c1f))
* squashing minor UI bugs ([a8a606c](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a8a606c))
* update initial PL iframe path default ([a26fbb9](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a26fbb9))
* updates to fix eslint / prettier issues; update packages/core to reuse root .eslintrc.js file ([5b7a057](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/5b7a057))
* **uikit-workshop:** fix merge problem ([d245b3b](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/d245b3b))






## [1.0.1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.1-alpha.0...@pattern-lab/uikit-workshop@1.0.1) (2019-05-16)


### Bug Fixes

* **uikit:** uikit no longer requires being in the root directory ([911ff06](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/911ff06))





# [1.0.0-beta.1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-beta.0...@pattern-lab/uikit-workshop@1.0.0-beta.1) (2019-02-09)


### Bug Fixes

* add missing style-loader ([0ce7470](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/0ce7470))
* clean up and fix overflow / scrolling issues ([bc13bd2](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/bc13bd2))
* fix bug with context menu not overlapping search input on smaller screen sizes ([0b175d9](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/0b175d9))
* fix inability to previously open / close / traverse pattern lab's navigation via keyboard ([25c9366](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/25c9366))
* fix scrolling issues with sidebar layout when nested nav sections are open; update sidebar layout to ensure viewport tools are still available on larger screens ([c7d1cda](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/c7d1cda))
* fix typo with CSS var in mixin ([fd7f2ea](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/fd7f2ea))
* fixing bug with dropdown offset since original Typeahead styles are no longer inlined ([f3e5467](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/f3e5467))
* hide borders on action menu when sidebar is visible ([a2e5720](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a2e5720))
* ie 11 cross browser fixes ([b3abb20](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/b3abb20))
* misc firefox-related bug fixes and quirks, including requiring the modal-viewer JS to get further delayed to prevent JS binding issues ([62f8bdb](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/62f8bdb))
* misc IE 11-specific UI and layout bugs ([930b619](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/930b619))
* remove anti-pattern of removing scrollbars on accordions — prevents users from knowing content is scrollable. also fix accessibility in global PL navigation which had been preventing full keyboard navigation ([cc9bf02](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/cc9bf02))
* update annotation style to display consistently in browser UI -- display inline isn't centered as expected for example. ([8449b1a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/8449b1a))
* update header styles to less-frequently wrap nav links to multiple lines ([ba0ca74](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/ba0ca74))
* **package:** remove jshint ([7254a2d](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/7254a2d))
* update iframe resizer broken path in UIKIt ([875573e](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/875573e))
* update native shim import path ([2959b93](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/2959b93)), closes [/github.com/sghoweri/patternlab-node/commit/72c0168bc4e3621f882c51ad61e32528694b4ad6#diff-d93f7a4be35cabaf5729f725702a9280](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/issues/diff-d93f7a4be35cabaf5729f725702a9280)
* update package.json with missing custom elements packages ([e52e06e](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/e52e06e)), closes [/github.com/sghoweri/patternlab-node/commit/72c0168bc4e3621f882c51ad61e32528694b4ad6#diff-e756faf6983689c170147ebe05d614d4](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/issues/diff-e756faf6983689c170147ebe05d614d4)
* update query selector to fail properly if Hogan template hadn't yet rendered when this fires off ([a2d77c7](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a2d77c7))
* update sidebar breakpoint to match breakpoints used in other components ([541ca3a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/541ca3a))
* update the keyboard combo used to auto-focus on the uikit search input to now use command + shift + f vs the browser-specific command + f combo ([8490afc](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/8490afc))
* update viewport CSS to prevent JS from exceeding the maximum size of the page; update to account for vertical vs horizontal layouts ([c0fcd6f](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/c0fcd6f))
* update Webpack config public path + add to default Webpack config options that can get overwritten via the cosmic config file in place ([b047cba](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/b047cba))
* workaround to address the pl-search autocomplete not displaying results the first time the component is focused ([95a4e71](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/95a4e71))


### Features

* add <pl-toggle-layout> component ([65b1177](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/65b1177))
* add <pl-toggle-theme> component ([a04bade](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a04bade))
* add localstorage support to redux store ([3d6a834](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/3d6a834))
* add Preact-powered base component extended by other components ([dd1ac7e](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/dd1ac7e))
* add wrapping <pl-layout> component that responds to state changes by the <pl-toggle-theme> and <pl-toggle-layout> components ([2141ad7](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/2141ad7))
* clean up UI controls in the light theme ([cd37c29](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/cd37c29))
* wire up redux + store + a few basic actions to support globally toggling the theme and layout config options ([01f9dce](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/01f9dce))


### Reverts

* undo removing hideScroll mixin from previous commit ([caa124a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/caa124a))





<a name="1.0.0-beta.0"></a>
# [1.0.0-beta.0](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-alpha.7...@pattern-lab/uikit-workshop@1.0.0-beta.0) (2018-09-07)


### Bug Fixes

* add missing node-sass dependency ([643808b](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/643808b))
* add webpack-cli as a uikit-workshop dependency; update npm script to use locally installed version vs globally / temp version via npx ([812efe9](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/812efe9))
* adjust how PL's viewport is sized / positioned when the sidebar layout is active so iframed content is centered properly ([3caffbf](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/3caffbf))
* change const back to var since PL's Uikit JS isn't run through Babel just yet.. update Prettier config to ignore Uikit's JavaScript for the time being ([35c5726](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/35c5726))
* check to make sure the code panel-related <script> tag contains data before attempting to parse expected JSON. Partial fix to [#761](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/issues/761) as this should at least help prevent the current batch of JS errors from getting thrown ([9c16675](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/9c16675))
* fix broken / missing closing HTML tag ([100ea8f](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/100ea8f))
* fix JS paths imported ([1d7dec8](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/1d7dec8))
* update ish-controls to be vertically centered in the global PL header by default ([f75de74](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/f75de74))
* update PL code viewer to open and resize as expected + animate much more performantly using CSS transforms; update existing JS logic to clean up inlined CSS styles when closing PL modal / code viewer panel ([a5be07b](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/a5be07b))
* **ui:**  fix keyboard shortcut for M link ([b4286ca](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/b4286ca))
* **uikit:** correct ishViewportRange logic ([365c626](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/365c626))
* **uikit:** remove indent from code panels ([e263fb0](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/e263fb0))
* update PrismJS import ([564da7a](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/564da7a))
* update typeahead selector so styles work as expected ([da13765](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/da13765))
* workaround fix for the PL UIKit viewport resizer width occasionally getting stuck with a width of 0px in Safari and Firefox when the JS is initially booting up ([64c971d](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/64c971d))


### Features

* 1st pass wiring up automatic critical CSS generation to UIkit ([7a982d6](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/7a982d6))
* lay down prep work for adding full on service worker support to Pattern Lab's UI. Cache busting logic will likely need to get added but the overall setup being added pretty much works! ([c6051e3](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/c6051e3))
* wire up new PL-specific iframe loader toast to display before the JS updating the iframe content kicks in ([4cb08d5](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/4cb08d5))
* **package:** add test command which bails on error ([3118cac](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/3118cac))





<a name="1.0.0-alpha.7"></a>

# [1.0.0-alpha.7](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-alpha.6...@pattern-lab/uikit-workshop@1.0.0-alpha.7) (2018-07-06)

### Features

* **package:** add npmrc file ([55f5bc2](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/55f5bc2))
* **package:** pin all dependencies ([415698e](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/415698e))
* **package:** remove package-lock.json files ([5ab3995](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/5ab3995))

<a name="1.0.0-alpha.6"></a>

# [1.0.0-alpha.6](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-alpha.5...@pattern-lab/uikit-workshop@1.0.0-alpha.6) (2018-07-05)

### Features

* **tests:** use lerna run test at the monorepo level ([38a01b1](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/38a01b1))

<a name="1.0.0-alpha.5"></a>

# [1.0.0-alpha.5](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-alpha.4...@pattern-lab/uikit-workshop@1.0.0-alpha.5) (2018-05-04)

**Note:** Version bump only for package @pattern-lab/uikit-workshop

<a name="1.0.0-alpha.4"></a>

# [1.0.0-alpha.4](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-alpha.3...@pattern-lab/uikit-workshop@1.0.0-alpha.4) (2018-03-21)

### Bug Fixes

* **lint:** run code through prettier ([ca52fde](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/ca52fde)), closes [#825](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/issues/825)
* **package:** remove files obsoleted by monorepo ([9abb8ac](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/9abb8ac))
* **package:** update LICENSE ([337aa32](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/337aa32))
* **polyfill:** Remove classList reference ([f0978da](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/f0978da))
* **README:** update content for consistency ([4edf0d4](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/4edf0d4)), closes [#815](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/issues/815)
* **README:** update installation command ([026e810](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/026e810))

### Features

* **package:** Add bower as an explicit dependency ([c070b80](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/c070b80))

<a name="1.0.0-alpha.3"></a>

# [1.0.0-alpha.3](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/compare/@pattern-lab/uikit-workshop@1.0.0-alpha.2...@pattern-lab/uikit-workshop@1.0.0-alpha.3) (2018-03-05)

### Bug Fixes

* **config:** Add npm registry to lerna config ([1473cd5](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/1473cd5))

<a name="1.0.0-alpha.2"></a>

# 1.0.0-alpha.2 (2018-03-02)

### Bug Fixes

* **packages:** Allow scoped publishing ([58beeb6](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/58beeb6))

### Features

* **packages:** Update all package.json repo and bug links ([5eb2c11](https://github.com/pattern-lab/patternlab-node/tree/master/packages/uikit-workshop/commit/5eb2c11))
