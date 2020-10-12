# Web Frontend Techniques

**Table of Content**

- Frontend Fundamentals
- Basic Frameworks
- Frontend Engineering
- Modern Frontend
  - Modern CSS
  - Progressive JS Frameworks
  - Web Components
- Application Development
  - Cross-Platform Mobile Applications
  - Cross-Platform Desktop Applications
  - Mini Programs
  - Full Stack Web Development
- More Techniques
  - Web Graphics
  - Web Assembly
- Advanced Topics
  - Web Performance
  - Cross-Browser Compatibility
- Libraries
- Tools

## Main

Color Meanings

- <span style="color:purple" class="text-purple">Purple: Recommend</span>
- <span style="color:green">Green: Alternative Option</span>
- <span style="color:gray">Gray: Don't recommend</span>

## Frontend Fundamentals

- <span style="color:purple">HTML</span>
- <span style="color:purple">CSS</span>
  - basics, layouts, responsive design and media queries
- <span style="color:purple">JavaScript</span>
  - basics, DOM manipulation, ajax, ES6+ and modular JavaScript, advanced (hoisting, event bubbling, scope, prototype, shadow DOM, strict)
- ECMAScript



## Basic Frameworks

- CSS Frameworks
  - <span style="color:purple">Bootstrap</span>
  - <span style="color:green">Materialize CSS</span>
  - <span style="color:green">Bulma</span>
- JavaScript Frameworks
  - jQuery



## Frontend Engineering

- Package Managers
  - <span style="color:purple">npm</span>
  - <span style="color:purple">yarn</span>
- Build Tools
  - Task Runners
    - <span style="color:purple">npm scripts</span>
    - Grunt
    - <span style="color:gray">Gulp</span>
  - Module Builders
    - <span style="color:purple">Webpack</span>
    - <span style="color:green">Rollup</span>
    - <span style="color:green">Parcel</span>
    - Snowpack
  - Transpiler
    - Babel
  - Linters and Formatters
    - Prettier
    - ESLint
    - <span style="color:gray">StandardJS</span>
- Progressive JS Frameworks
  - <span style="color:purple">React.js</span>
    - Fundamental Topics
      - Create React App, JSX, Components, Props vs State, Conditional Rendering, Component Lifecycle, List and Keys, Composition vs Inheritance
    - Advanced Topics
      - Hooks, Context, Refs, Render Props, Code Splitting, High Order Components, Portals, Error Boundaries, Fiber Architecture
    - Ecosystem
      - Routers
        - <span style="color:purple">React Router</span>
        - <span style="color:green">Reach Router</span>
      - State Management
        - <span style="color:purple">Context / State</span>
        - <span style="color:purple">Redux</span>
        - <span style="color:green">MobX</span>
        - Redux-Saga
      - Styling
        - <span style="color:purple">Styled Components</span>
        - <span style="color:green">Chakra UI</span>
        - <span style="color:green">Material UI</span>
        - <span style="color:green">antd (Ant Design)</span>
        - <span style="color:green">Emotion</span>
        - UmiJS
      - Forms
        - <span style="color:purple">React Hook Form</span>
        - <span style="color:green">Formik</span>
        - <span style="color:green">Final Form</span>
      - Testing
        - <span style="color:purple">Jest</span>
        - <span style="color:purple">React Testing Library</span>
        - <span style="color:purple">Cypress</span>
      - Server Side Rendering (SSR)
        - <span style="color:purple">Next.js</span>
      - Static Site Generator (SSG)
        - <span style="color:purple">Next.js</span>
        - <span style="color:green">Gatsby</span>
      - API Calls
        - GraphQL
          - <span style="color:purple">Apollo</span>
          - <span style="color:green">Relay Modern</span>
        - REST API Calls
          - <span style="color:purple">Axios</span>
          - <span style="color:green">Unfetch</span>
          - <span style="color:green">Superagent</span>
        - Hooks Based
          - <span style="color:purple">use-http</span>
      - Mobile
        - <span style="color:purple">React Native</span>
  - <span style="color:green">Vue.js</span>
    - Ecosystem
      - Tools
        - vue-cli
      - Router
        - Vue Router
        - Router5, vue-component-router
      - State Management
        - VueX
      - Styling
        - Quasar, Vuetify, iView
        - Vuesax, bootstrap-vue
        - vue-element-admin-ui
      - API Clients
        - REST
          - fetch (native)
          - SuperAgent, axios
        - GraphQL
          - Apollo
          - Relay
      - Utility Libraries
        - Lodash, Moment
        - Numeral, RxJS
        - Ramda
      - Testing
        - Unit Testing
          - Jest, Vue-test-utils, Sinon
          - Mocha, Chai
          - AVA, Tape
        - Integration Testing
          - Karma
        - E2E Testing
          - Nightwatch
          - Selenium, Puppeteer, Cucumber.js
      - i18n
        - vue-i18n
      - Server Side Rendering (SSR)
        - Nuxt
      - Static Site Generator (SSG)
        - VuePress
      - Mobile
        - Quasar
        - Vue Native, Nativescript Vue, Weex
      - Desktop
        - Quasar
        - Electron, NW.js, Vuldo
  - <span style="color:green">AngularJS</span>
    - RxJS
    - NgRx



## Modern Frontend

- Modern CSS
  - CSS Architecture
    - BEM
    - <span style="color:gray">OOCSS</span>
    - <span style="color:gray">SMACSS</span>
  - CSS Preprocessors
    - Sass
    - PostCSS
    - <span style="color:gray">Less</span>
    - Stylus
  - Modern CSS
    - <span style="color:purple">Styled Components</span>
    - <span style="color:purple">CSS Modules</span>
    - <span style="color:green">Styled JSX</span>
    - <span style="color:green">Emotion</span>
    - <span style="color:gray">Radium</span>
    - <span style="color:gray">Glamorous</span>
  - CSS Frameworks (JS-Based)
    - <span style="color:purple">Reactstrap</span>
    - <span style="color:purple">Material UI</span>
    - <span style="color:green">Tailwind CSS</span>
    - <span style="color:green">Chakra UI</span>
- Web Components
  - HTML Templates
  - Custom Elements
  - Shadow DOM
- Test
  - <span style="color:purple">Jest</span>
  - <span style="color:purple">react-testing-library</span>
  - <span style="color:purple">Cypress</span>
  - <span style="color:purple">Enzyme</span>
  - Mocha JS
  - Chai JS
  - Ava
  - Jasmine
- Type Checkers
  - <span style="color:purple">TypeScript</span>
  - Flow
- Server Side Rendering (SSR)
  - React.js
    - <span style="color:purple">Next.js</span>
    - <span style="color:gray">After.js</span>
  - AngularJS
    - <span style="color:green">Universal</span>
  - Vue.js
    - <span style="color:green">Nuxt.js</span>
- Static Site Generators
  - <span style="color:purple">Next.js</span>
  - <span style="color:purple">GatsbyJS</span>
  - <span style="color:green">Nuxt.js</span>
  - <span style="color:green">Vuepress</span>
  - <span style="color:green">Jekyll</span>
  - <span style="color:green">Hugo</span>



## Application Development

- Cross-Platform Mobile Applications
  - <span style="color:purple">React Native</span>
  - Progressive Web Apps (PWA)
  - NativeScript
  - Flutter
  - Ionic 4
  - Apache Cordova
  - Weex
  - Taro
  - Quasar Framework
  - uni-app
- Cross-Platform Desktop Applications
  - <span style="color:purple">Electron</span>
  - NW.js
  - <span style="color:gray">Carlo</span>
  - <span style="color:gray">Proton Native</span>
- Mini Programs
  - <span style="color:purple">WeChat Mini Program</span>
  - QQ Mini Program
  - Alipay Mini Program
- Full Stack Web Development
  - Node.js
  - Web Frameworks
    - Express
    - Koa.js
  - Database
    - MongoDB
  - GraphQL
    - <span style="color:purple">Apollo</span>
    - <span style="color:green">Relay Modern</span>



## More Techniques

- Web Graphics
  - WebGL
- Web Assembly



## Advanced Topics

- Web Performance
  - Performance Metrics
    - FP (First Paint)
    - FCP (First Contentful Paint)
    - FMP (First Meaningful Paint)
    - TTI (Time to Interactive)
    - HET
    - First CPU Idle
  - Performance Optimization Tools
    - Website Performance Test
      - WebPageTest
    - Website Quality Audit
      - Microsoft Application Insights
      - Google PageSpeed Insights
      - Lighthouse
    - Load Test
      - Bombardier
    - Browser Developer tools
    - Browser APIs
  - Optimization Solutions
    - Network Optimization
      - Request
      - Resources
      - Compression
      - Cache
    - Rendering Optimization
      - CSS/JS
      - DOM
      - Lazy Loading
- Cross-Browser Compatibility



## Libraries

- Data Visualization
  - Highcharts
  - Apache Echarts
  - AntV
  - D3.js
- UI Frameworks
  - Semantic UI
  - Foundation
  - Layui
- UI Components
  - Element UI
  - iView
  - antd
  - Material UI (React UI Framework)
  - jQuery UI
  - Date
    - Date picker
    - layDate
  - Calendar
    - FullCalendar
  - Tree
    - zTree
  - Grid
    - jQgrid
    - jQuery Gridly
  - Alert
    - Layui
    - Sweetalert
  - Input Tags
    - jQuery Plugin inputTags.js
    - Bootstrap Tags Input
    - Layui inputTags
- Rich Text Editors
  - TinyMCE
  - UEditor
  - CKEditor
  - Draft.js
  - Slate.js
- Animation
  - Animate.css
  - Anime.js
- Simulation Data Generator
  - Mock.js
- Utilities
  - UnderScore.js
  - Lodash
  - Moment.js
- Font and Icon
  - Font Awesome
  - Iconfont



## Tools

- IDEs
  - <span style="color:purple">WebStorm</span>
  - <span style="color:purple">VSCode</span>
  - HBuilder
- Editors
  - Sublime
- Browsers
  - Chrome
  - Firefox
  - Safari
- Version Control
  - <span style="color:purple">Git</span>
  - SVN
- Servers
  - Nginx
  - Docker

## References

[1] [Frontend Developer Roadmap](https://roadmap.sh/frontend)

React

- [React Developer Roadmap](https://roadmap.sh/react)
- [awesome-react](https://github.com/enaqx/awesome-react)
- [awesome-react-components](https://github.com/brillout/awesome-react-components)

Vue

- [Vue Developer Roadmap](https://github.com/marekbrainhub/vue-developer-roadmap)
- [awesome-vue](https://github.com/vuejs/awesome-vue)

