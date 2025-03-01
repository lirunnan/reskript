# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [5.2.1](https://github.com/ecomfe/reskript/compare/v5.2.0...v5.2.1) (2022-03-29)

**Note:** Version bump only for package @reskript/showcase-todo





# [5.2.0](https://github.com/ecomfe/reskript/compare/v5.1.0...v5.2.0) (2022-03-14)


### Bug Fixes

* **build:** 修复*.var.less未自动注入的问题 ([#279](https://github.com/ecomfe/reskript/issues/279)) ([65db818](https://github.com/ecomfe/reskript/commit/65db818545b8366450612a48abbf14201f9ea6c2))





# [5.1.0](https://github.com/ecomfe/reskript/compare/v5.0.0...v5.1.0) (2022-03-11)

**Note:** Version bump only for package @reskript/showcase-todo





# [5.0.0](https://github.com/ecomfe/reskript/compare/v5.0.0-beta.1...v5.0.0) (2022-03-10)

**Note:** Version bump only for package @reskript/showcase-todo





# [5.0.0-beta.1](https://github.com/ecomfe/reskript/compare/v5.0.0-beta.0...v5.0.0-beta.1) (2022-03-10)


### Features

* **plugin-inject-html:** 支持plugin-inject-plugin仅在指定的命令下启用 ([9e9ab97](https://github.com/ecomfe/reskript/commit/9e9ab97358ad0339d76d54d8c5ab1b8c30492774))
* **plugin-utils:** 增加插件相关的工具包 ([#275](https://github.com/ecomfe/reskript/issues/275)) ([5b82848](https://github.com/ecomfe/reskript/commit/5b828489c2ee96a612f8faecfb18a4d34fb14228))


### Performance Improvements

* **build:** 预处理antd和core-js的打包 ([0559a6e](https://github.com/ecomfe/reskript/commit/0559a6e42b3c50fc3445cb91224a531c25d9c31d))





# [5.0.0-beta.0](https://github.com/ecomfe/reskript/compare/v4.3.0...v5.0.0-beta.0) (2022-03-03)


### Features

* **build:** 在Vite引擎中支持publicPath ([#200](https://github.com/ecomfe/reskript/issues/200)) ([c4da054](https://github.com/ecomfe/reskript/commit/c4da054ed4e2a3c704c2d54dc3777801b343167e))
* **build:** 支持Vite的build命令 ([#200](https://github.com/ecomfe/reskript/issues/200)) ([4294acf](https://github.com/ecomfe/reskript/commit/4294acf3da0346760313d1a89db3ca4fb93c45c8))
* **build:** 支持Vite的service worker生成 ([#200](https://github.com/ecomfe/reskript/issues/200)) ([47600c0](https://github.com/ecomfe/reskript/commit/47600c0cb20276bf72e4d81be7071929816c6d1f))
* **build:** 支持双引擎的HTML修改功能 ([#200](https://github.com/ecomfe/reskript/issues/200)) ([41d9521](https://github.com/ecomfe/reskript/commit/41d9521225ff4b5bcb43614d82f9eec87bcd638d))
* **dev:** 在Vite引擎中支持customizeMiddleware ([#200](https://github.com/ecomfe/reskript/issues/200)) ([f023a42](https://github.com/ecomfe/reskript/commit/f023a42b47bc41bcd6e0af7c3b3c2df2dcec5e2f))
* **dev:** 实现Vite的dev基础功能 ([#200](https://github.com/ecomfe/reskript/issues/200)) ([2e46749](https://github.com/ecomfe/reskript/commit/2e46749180f47810abf9171d74d0b85820d98d55))
* **play:** 支持Vite引擎的play功能 ([#200](https://github.com/ecomfe/reskript/issues/200)) ([bb7e629](https://github.com/ecomfe/reskript/commit/bb7e62936582c62098e3bea31ee93f286eaa81a6))
* **portal:** 实现portal模块 ([#266](https://github.com/ecomfe/reskript/issues/266)) ([2e765dc](https://github.com/ecomfe/reskript/commit/2e765dc84f7d9224b317c73bb5ceb9576a28b779))
* 使用query引入worker ([#200](https://github.com/ecomfe/reskript/issues/200)) ([ed5efd4](https://github.com/ecomfe/reskript/commit/ed5efd46a67672b14919b84fa4ea9805afd326c2))
* 实现Vite样式相关的配置 ([#200](https://github.com/ecomfe/reskript/issues/200)) ([ee7bab0](https://github.com/ecomfe/reskript/commit/ee7bab0c127d153ebc158e41f6be6921e108c619))


### BREAKING CHANGES

* **build:** `@reskript/webpack-plugin-extra-script`已经废弃，使用`@reskript/plugin-inject-html`替代
* **dev:** `@reskript/config-webpack`和`build.finalize`中的`styleResources`相关的功能已经移除，由内置的less插件实现
* **dev:** `$features`改名为`skr.features`，`$build`改名为`skr.build`
* **dev:** 自定义HTML模板中，只能使用`templateData.*`获取模板数据
* **dev:** 原入口配置中的`export const html`中，用于模板数据的部分，更新为`export const templateData`
* 要将文件引入为worker，需要使用`xxx?worker`的形式





# [4.3.0](https://github.com/ecomfe/reskript/compare/v4.2.1...v4.3.0) (2022-03-03)


### Features

* **settings:** 提供客户端常用类型 ([#270](https://github.com/ecomfe/reskript/issues/270)) ([84994c1](https://github.com/ecomfe/reskript/commit/84994c1cf74c093b72ebde2cf1f05b6637131554))





## [4.2.1](https://github.com/ecomfe/reskript/compare/v4.2.0...v4.2.1) (2022-02-25)

**Note:** Version bump only for package @reskript/showcase-todo





# [4.2.0](https://github.com/ecomfe/reskript/compare/v4.1.2...v4.2.0) (2022-02-25)

**Note:** Version bump only for package @reskript/showcase-todo





## [4.1.2](https://github.com/ecomfe/reskript/compare/v4.1.1...v4.1.2) (2022-02-10)

**Note:** Version bump only for package @reskript/showcase-todo





## [4.1.1](https://github.com/ecomfe/reskript/compare/v4.1.0...v4.1.1) (2022-02-08)

**Note:** Version bump only for package @reskript/showcase-todo





# [4.1.0](https://github.com/ecomfe/reskript/compare/v4.0.1...v4.1.0) (2022-02-07)

**Note:** Version bump only for package @reskript/showcase-todo





## [4.0.1](https://github.com/ecomfe/reskript/compare/v4.0.0...v4.0.1) (2022-02-07)

**Note:** Version bump only for package @reskript/showcase-todo





# [4.0.0](https://github.com/ecomfe/reskript/compare/v4.0.0-beta.2...v4.0.0) (2022-02-03)


### Features

* 优化build.finalize的参数类型 ([#244](https://github.com/ecomfe/reskript/issues/244)) ([4fe2677](https://github.com/ecomfe/reskript/commit/4fe267765d6d63d1021cb2956fc8d5721e2568b6))
* 支持插件配置的值为空值或数组 ([#245](https://github.com/ecomfe/reskript/issues/245)) ([b98c2c8](https://github.com/ecomfe/reskript/commit/b98c2c8df7cd141963690ae53320e2a4ad2e6539))


### BREAKING CHANGES

* `plugins`配置为函数时的`commandName`参数增加了`"play"`的可能性，原版本在使用`skr play`时的该参数值为`"dev"`





# [4.0.0-beta.2](https://github.com/ecomfe/reskript/compare/v4.0.0-beta.1...v4.0.0-beta.2) (2022-02-02)


### Bug Fixes

* **build:** 修复loader-of-loader会无视前置loader的问题 ([400ee50](https://github.com/ecomfe/reskript/commit/400ee50c691d029d4d6a128454436a7a102f69a8))





# [4.0.0-beta.1](https://github.com/ecomfe/reskript/compare/v4.0.0-beta.0...v4.0.0-beta.1) (2022-02-01)


### Features

* **build:** 支持各个loader的ESM化 ([#39](https://github.com/ecomfe/reskript/issues/39)) ([d7451e5](https://github.com/ecomfe/reskript/commit/d7451e5fd6c88aed0bcfdd11e807948a824ce2f3))





# [4.0.0-beta.0](https://github.com/ecomfe/reskript/compare/v3.0.6...v4.0.0-beta.0) (2022-01-30)


### Code Refactoring

* 核心部分迁移到纯ESM包格式 ([#39](https://github.com/ecomfe/reskript/issues/39)) ([f9d06b0](https://github.com/ecomfe/reskript/commit/f9d06b0fd802caa002707686d004ca8683f7002f))


### Features

* **build:** 各个插件转为ESM格式 ([#39](https://github.com/ecomfe/reskript/issues/39)) ([1950ace](https://github.com/ecomfe/reskript/commit/1950ace8c05d317b855a7f01b4680e54a011d61f))
* **play:** 支持play的组件配置为ts等扩展名 ([#231](https://github.com/ecomfe/reskript/issues/231)) ([ae72706](https://github.com/ecomfe/reskript/commit/ae72706b2c870c8f519cacf88f43075df9a2179d))
* **settings:** 支持且仅支持.mjs和.ts类型的项目配置 ([#225](https://github.com/ecomfe/reskript/issues/225)) ([5a9586b](https://github.com/ecomfe/reskript/commit/5a9586b053f16d89a7b87b22dd6a4ca84d96edd2))
* **settings:** 支持自定义配置文件路径 ([#230](https://github.com/ecomfe/reskript/issues/230)) ([2a4ca98](https://github.com/ecomfe/reskript/commit/2a4ca987ae7e193916ed8c7972dbcbff521b4863))


### Performance Improvements

* **build:** 异步检索loader路径优化性能 ([#234](https://github.com/ecomfe/reskript/issues/234)) ([3ace896](https://github.com/ecomfe/reskript/commit/3ace89660fac60986b5daa9c8a07d9cf4a6248c8))


### BREAKING CHANGES

* **settings:** 项目配置必须为`reskript.config.{mjs|ts}`，且格式为ESM
* **settings:** 应用入口配置必须为`xxx.config.{mjs|ts}`，且格式为ESM
* 发布的包为纯ESM格式，无法通过CommonJS的`require`引入。参考[sinderesorhus的建议](https://gist.github.com/sindresorhus/a39789f98801d908bbc7ff3ecc99d99c)





## [3.0.6](https://github.com/ecomfe/reskript/compare/v3.0.5...v3.0.6) (2022-01-21)

**Note:** Version bump only for package @reskript/showcase-todo





## [3.0.5](https://github.com/ecomfe/reskript/compare/v3.0.4...v3.0.5) (2022-01-21)

**Note:** Version bump only for package @reskript/showcase-todo





## [3.0.4](https://github.com/ecomfe/reskript/compare/v3.0.3...v3.0.4) (2022-01-20)

**Note:** Version bump only for package @reskript/showcase-todo





## [3.0.3](https://github.com/ecomfe/reskript/compare/v3.0.2...v3.0.3) (2022-01-20)


### Bug Fixes

* **lint:** 样式文件的lint问题可以被自动修复 ([#232](https://github.com/ecomfe/reskript/issues/232)) ([a154f31](https://github.com/ecomfe/reskript/commit/a154f317d519e366b875534639c13a7b3306f4e9))





## [3.0.2](https://github.com/ecomfe/reskript/compare/v3.0.1...v3.0.2) (2022-01-13)

**Note:** Version bump only for package @reskript/showcase-todo





## [3.0.1](https://github.com/ecomfe/reskript/compare/v3.0.0...v3.0.1) (2022-01-04)

**Note:** Version bump only for package @reskript/showcase-todo





# [3.0.0](https://github.com/ecomfe/reskript/compare/v3.0.0-beta.1...v3.0.0) (2022-01-03)

**Note:** Version bump only for package @reskript/showcase-todo





# [3.0.0-beta.1](https://github.com/ecomfe/reskript/compare/v3.0.0-beta.0...v3.0.0-beta.1) (2022-01-03)

**Note:** Version bump only for package @reskript/showcase-todo





# [3.0.0-beta.0](https://github.com/ecomfe/reskript/compare/v2.5.3...v3.0.0-beta.0) (2022-01-03)


### Features

* 支持eslint 8 ([#176](https://github.com/ecomfe/reskript/issues/176)) ([76acae3](https://github.com/ecomfe/reskript/commit/76acae373762da03b2208088908d7a0022bb0536))
* 支持stylelint 14 ([#186](https://github.com/ecomfe/reskript/issues/186)) ([05e24c0](https://github.com/ecomfe/reskript/commit/05e24c0e8f004e7c342c138e00d1b73724545aa3))


### BREAKING CHANGES

* 需要`eslint`升级至`8.x`
* 需要`stylelint`升级至`14.x`





## [2.5.3](https://github.com/ecomfe/reskript/compare/v2.5.2...v2.5.3) (2021-12-31)

**Note:** Version bump only for package @reskript/showcase-todo





## [2.5.2](https://github.com/ecomfe/reskript/compare/v2.5.1...v2.5.2) (2021-12-29)

**Note:** Version bump only for package @reskript/showcase-todo





## [2.5.1](https://github.com/ecomfe/reskript/compare/v2.5.0...v2.5.1) (2021-12-28)


### Bug Fixes

* **build:** 支持import的时候使用.js但指向.ts或.tsx ([#219](https://github.com/ecomfe/reskript/issues/219)) ([4bad498](https://github.com/ecomfe/reskript/commit/4bad49865cd55aa44e5bf41e72436ec91284c822))
* **build:** 支持项目使用纯ESM格式，配置文件使用cjs ([#218](https://github.com/ecomfe/reskript/issues/218)) ([2646bac](https://github.com/ecomfe/reskript/commit/2646bac2f50e1ff52a0a7a4b088a7b282d6cf614))





# [2.5.0](https://github.com/ecomfe/reskript/compare/v2.4.0...v2.5.0) (2021-12-25)


### Bug Fixes

* **build:** 在build时也同样读用户自定义的lint配置 ([#211](https://github.com/ecomfe/reskript/issues/211)) ([e580bce](https://github.com/ecomfe/reskript/commit/e580bce69a0d1a7f2714409d9611a50688020291))


### Features

* **dev:** 支持HTTPS协议启动调试服务器 ([#217](https://github.com/ecomfe/reskript/issues/217)) ([4646f77](https://github.com/ecomfe/reskript/commit/4646f77e30dd28f8e3f6b408ef81f325dcf1fd37))





# [2.4.0](https://github.com/ecomfe/reskript/compare/v2.3.0...v2.4.0) (2021-12-14)


### Features

* **build:** 引入psotcss-preset-env ([#204](https://github.com/ecomfe/reskript/issues/204)) ([f910249](https://github.com/ecomfe/reskript/commit/f9102496978c2fbaf2049c18cc0a5250b03daba1))





# [2.3.0](https://github.com/ecomfe/reskript/compare/v2.2.2...v2.3.0) (2021-11-04)


### Bug Fixes

* **build:** 读取.env顺序修复 ([#174](https://github.com/ecomfe/reskript/issues/174)) ([132f01f](https://github.com/ecomfe/reskript/commit/132f01f9166f96e2046b935ee08132e15444ee51))





## [2.2.2](https://github.com/ecomfe/reskript/compare/v2.2.1...v2.2.2) (2021-09-12)

**Note:** Version bump only for package @reskript/showcase-todo





## [2.2.1](https://github.com/ecomfe/reskript/compare/v2.2.0...v2.2.1) (2021-09-12)

**Note:** Version bump only for package @reskript/showcase-todo





# [2.2.0](https://github.com/ecomfe/reskript/compare/v2.1.0...v2.2.0) (2021-09-12)


### Features

* **build:** 增加一个产出检查项，确保产出的HTML适用于微前端 ([#163](https://github.com/ecomfe/reskript/issues/163)) ([5f6b252](https://github.com/ecomfe/reskript/commit/5f6b2524d89f8787c7a45ae4765928bc41535ef4))





# [2.1.0](https://github.com/ecomfe/reskript/compare/v2.0.0...v2.1.0) (2021-08-31)


### Bug Fixes

* **build:** 把SVG转为组件时保留ref ([#159](https://github.com/ecomfe/reskript/issues/159)) ([863f582](https://github.com/ecomfe/reskript/commit/863f58254eb8bc3ee1e04eb04187b5381f570b5f))





# [2.0.0](https://github.com/ecomfe/reskript/compare/v2.0.0-beta.5...v2.0.0) (2021-08-26)

**Note:** Version bump only for package @reskript/showcase-todo





# [2.0.0-beta.5](https://github.com/ecomfe/reskript/compare/v2.0.0-beta.4...v2.0.0-beta.5) (2021-08-26)

**Note:** Version bump only for package @reskript/showcase-todo





# [2.0.0-beta.4](https://github.com/ecomfe/reskript/compare/v2.0.0-beta.3...v2.0.0-beta.4) (2021-08-25)


### Bug Fixes

* **build:** 修复读取入口配置时的逻辑错误 ([#149](https://github.com/ecomfe/reskript/issues/149)) ([0ce0026](https://github.com/ecomfe/reskript/commit/0ce00269216bb5c419467ad7b91ff2f40e295f39))





# [2.0.0-beta.3](https://github.com/ecomfe/reskript/compare/v2.0.0-beta.2...v2.0.0-beta.3) (2021-08-25)

**Note:** Version bump only for package @reskript/showcase-todo





# [2.0.0-beta.2](https://github.com/ecomfe/reskript/compare/v2.0.0-beta.1...v2.0.0-beta.2) (2021-08-25)

**Note:** Version bump only for package @reskript/showcase-todo





# [2.0.0-beta.1](https://github.com/ecomfe/reskript/compare/v1.15.2...v2.0.0-beta.1) (2021-08-25)


* feat(dev)!: 支持webpack-dev-server 4版本 (#123) ([40f0478](https://github.com/ecomfe/reskript/commit/40f047851e36c37e1f572e4945d9872e1bc11edf)), closes [#123](https://github.com/ecomfe/reskript/issues/123)
* fix(build)!: 由用户自行安装core-js (#137) ([9af1569](https://github.com/ecomfe/reskript/commit/9af1569255ae166771be8a0ccaef4e133b5bc7d9)), closes [#137](https://github.com/ecomfe/reskript/issues/137)


### Features

* **build:** 增加严格模式开关 ([#54](https://github.com/ecomfe/reskript/issues/54)) ([3e00afc](https://github.com/ecomfe/reskript/commit/3e00afc503371412a30260c5a836935b47b7eb60))
* 支持tailwind ([#119](https://github.com/ecomfe/reskript/issues/119)) ([d636c80](https://github.com/ecomfe/reskript/commit/d636c804ddfbaae00674682a86cec5ec32ff9265))


### BREAKING CHANGES

* `webpack-dev-server`更新至`4.x`版本，具体参考[官方迁移指南](https://github.com/webpack/webpack-dev-server/blob/master/migration-v4.md)
* `devServer.hot`的类型修改为`boolean`
* `config-babel`的`hot`配置类型修改为`boolean`
* 不再处理`core-js`的引入，用户必须在项目中自行安装`core-js@3`





## [1.15.2](https://github.com/ecomfe/reskript/compare/v1.15.1...v1.15.2) (2021-08-24)

**Note:** Version bump only for package @reskript/showcase-todo
