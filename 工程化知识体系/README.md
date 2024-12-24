# 工程化知识体系
前端知识体系大合集 - 你要的框架、类库、工具集都在这里

> 网页版更直观:[前端视界-导航](https://www.fe-vision.cn/nav)

## 框架
[Vite](https://github.com/vitejs/vite): 69.6k, 快速构建工具，特别适合现代前端框架（如 Vue、React）。通过原生 ES 模块加速开发，并提供高效的生产环境打包.      
[Webpack](https://github.com/webpack/webpack): 64.6k, 目前最流行的前端模块打包工具，将各种资源（JavaScript、CSS、图片等）打包成可在浏览器中使用的静态文件.       
[Parcel](https://github.com/parcel-bundler/parcel): 43.4k, 零配置的打包工具，专注于简单和快速，适合小型或中型项目.       
[esbuild](https://github.com/evanw/esbuild): 38.3k, 高速的 JavaScript 和 TypeScript 构建工具，以极快的构建速度和低资源消耗著称.       
[Lerna](https://github.com/lerna/lerna): 35.6k, Monorepo 项目管理工具，帮助开发者管理多个包的发布和依赖关系.       
[Gulp](https://github.com/gulpjs/gulp): 33k, 基于流的自动化构建工具，用于任务自动化（如文件压缩、Sass/LESS 编译、代码检查等）.       
[Turborepo](https://github.com/vercel/turborepo): 26k, Monorepo 构建系统，提供增量构建和缓存优化，提升构建性能.       
[Rollup](https://github.com/rollup/rollup): 25.2k, JavaScript 模块打包器，适合构建开源库，生成更小、更优化的代码.       
[NX](https://github.com/nrwl/nx): 24k, 构建和开发工具集，为 Monorepo 项目设计，可管理多个应用或包.       
[Snowpack](https://github.com/FredKSchott/snowpack): 19.5k, 使用原生 ES 模块的构建工具，开发时无需打包，加快构建速度，适合现代前端开发.       
[Browserify](https://github.com/browserify/browserify): 14.6k, 模块打包工具，为浏览器提供 Node.js 的模块化功能.       
[Grunt](https://github.com/gruntjs/grunt): 12.3k, JavaScript 任务运行器，支持文件压缩、CSS/JS 编译等自动化任务.       
[Yeoman](https://github.com/yeoman/yo): 3.8k, 脚手架工具，通过生成器创建项目的基本框架，自动配置项目结构、依赖和任务.     

## 脚手架
[create-react-app](https://github.com/facebook/create-react-app): 103k, React 工程脚手架，快速创建一个基于 React 的项目.       
[html5-boilerplate](https://github.com/h5bp/html5-boilerplate): 56.4k, HTML5 构建脚手架，用于快速构建现代化的 HTML 项目.        
[gatsby-cli](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-cli): 55.2k, 启动和运行 Gatsby 应用程序的命令行工具.        
[create-expo-app](https://github.com/expo/create-react-native-app): 13.3k, 创建一个安装了 Expo 包的新 React Native 项目.        
[@vue/cli](https://github.com/vuejs/vue-cli): 29.8k, Vue 2 工程脚手架，帮助快速创建和管理 Vue 2 项目.        
[create-remix](https://github.com/remix-run/remix/tree/main/packages/create-remix): 29.1k, 创建一个新的 Remix 项目，支持现代 React 应用程序开发.        
[create-vue](https://github.com/vuejs/create-vue): 3.7k, Vue 3 工程脚手架，用于快速初始化一个 Vue 3 项目.        
[ember-cli](https://github.com/ember-cli/ember-cli): 3.3k, Ember.js 工程脚手架，提供自动化工具和模板来加速开发.        
[@ionic/cli](https://github.com/ionic-team/ionic-cli): 2k, Ionic 移动端框架的构建脚手架，用于创建和管理移动应用程序.        
[@nestjs/cli](https://github.com/nestjs/nest-cli): 2k, NestJS 工程脚手架，用于快速构建基于 NestJS 的项目.        
[express-generator](https://github.com/expressjs/generator): 1.8k, Express 项目构建脚手架，快速生成基础 Express 项目结构.

## 包管理工具
[deno](https://github.com/denoland/deno): 101k, 现代的 JavaScript/TypeScript 运行时环境，由 Node.js 的创建者 Ryan Dahl 开发，旨在提供更安全和更简洁的工具。      
[bun](https://github.com/oven-sh/bun): 75k, 快速的 JavaScript 运行时和工具包，优化了现代开发，包括一个包管理器和打包工具。      
[yarn](https://github.com/yarnpkg/yarn): 41.4k, 流行的 JavaScript 包管理器，以速度、可靠性和安全的依赖管理著称。      
[pnpm](https://github.com/pnpm/pnpm): 30.2k, 高效处理 Node.js 模块的包管理器，通过从全局存储链接模块来节省空间并提高速度。      
[npm](https://github.com/npm/cli): 8.6k, Node.js 的默认包管理器，用于安装、共享和管理 JavaScript 包。    

## 静态代码分析工具
[Prettier](https://github.com/prettier/prettier): 49.1k, 代码格式化工具，用于保持代码风格的一致性。       
[ESLint](https://github.com/eslint/eslint): 25.4k, JavaScript 代码的静态分析工具，用于发现和修复代码中的问题。        
[Stylelint](https://github.com/stylelint/stylelint): 11k, 用于分析 CSS 和预处理器（如 Sass、Less）的代码风格问题。        
[Oxc](https://github.com/oxc-project/oxc): 12.9k, JavaScript 代码的静态分析工具，比 ESLint 快 50 到 100 倍，已经支持 400 多条规则。        
[HTMLHint](https://github.com/htmlhint/HTMLHint): 3.1k, 用于 HTML 代码的静态分析，检查 HTML 的错误和规范问题。

## 测试框架  
[Cypress](https://github.com/cypress-io/cypress): 47.6k, 前端测试工具，专注于端到端测试。        
[Jest](https://github.com/jestjs/jest): 44.1k, JavaScript 测试框架，提供功能全面的测试功能。        
[Mocha](https://github.com/mochajs/mocha): 22.6k, 测试框架，提供灵活的测试用例编写功能。
