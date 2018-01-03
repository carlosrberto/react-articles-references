# React + Redux community articles and references

A list of topics to study before implementing a **large** and **scalable** **React + Redux** application.

- [Front-End](#front-end)
    - [Organization](#organization)
    - [Micro Frontend and decoupling](#micro-frontend-and-decoupling)
    - [React](#react)
    - [React Router](#react-router)
    - [React Native](#react-native)
    - [Redux](#redux)
    - [Redux Saga](#redux-saga)
    - [Redux Forms](#redux-forms)
    - [Redux Dev Tools](#redux-dev-tools)
    - [Testing](#testing)
    - [Advanced ES6 Features](#advanced-es6-features)
    - [Functional programming](#functional-programming)
    - [Immutability](#immutability)
    - [Offline first & Progressive Web Apps](#offline-first--progressive-web-apps)
    - [Webpack](#webpack)
- [CSS](#css)
    - [CSS Modules](#css-modules)
- [Environment](#environment)
- [Shell](#shell)
- [Server-side](#server-side)
    - [JSON Web Token](#json-web-token)
    - [Amazon S3](#amazon-s3)
- [Libraries to take a look](#libraries-to-take-a-look)
    - [Browser/Server](#browserserver)
    - [React](#react-1)
    - [Redux](#redux-1)
    - [Yarn](#yarn)
- [Others](#others)
    - [Services](#services)
    - [React Ecosystem Links](#react-ecosystem-links)

## Front-End

### Organization
- [Project Structure](https://github.com/markerikson/react-redux-links/blob/master/project-structure.md)
- [How To Scale React Applications](https://www.smashingmagazine.com/2016/09/how-to-scale-react-applications/)
- https://marmelab.com/blog/2015/12/17/react-directory-structure.html
- https://jaysoo.ca/2016/02/28/organizing-redux-application/
- https://tech.okcupid.com/how-okcupid-organizes-its-multi-page-react-app/
- https://www.smashingmagazine.com/2016/09/how-to-scale-react-applications/
- http://engineering.kapost.com/2016/01/organizing-large-react-applications/
- https://hackernoon.com/my-journey-toward-a-maintainable-project-structure-for-react-redux-b05dfd999b5
- [Fractal — A react app structure for infinite scale](https://hackernoon.com/fractal-a-react-app-structure-for-infinite-scale-4dab943092af)

### Micro Frontend and decoupling
- https://www.slideshare.net/mobile/VivianFarrell/scaling-react-and-redux-at-ioof
- https://github.com/neuland/micro-frontends
- https://medium.com/@tomsoderlund/micro-frontends-a-microservice-approach-to-front-end-web-development-f325ebdadc16

### React
- [Presentational and Container Components – Dan Abramov – Medium](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
- [How To Scale React Applications – Smashing Magazine](https://www.smashingmagazine.com/2016/09/how-to-scale-react-applications/)
- [Advice on large scale React.js apps, rebuilding the biggest social publishing platform for Latam](https://medium.com/taringa-on-publishing/advice-on-large-scale-react-js-apps-rebuilding-the-biggest-social-publishing-platform-for-latam-1f4c8fa35a4f)
- [Tips For a Better Redux Architecture: Lessons for Enterprise Scale](https://hashnode.com/post/tips-for-a-better-redux-architecture-lessons-for-enterprise-scale-civrlqhuy0keqc6539boivk2f)
- [Large open source react/redux projects](https://www.reddit.com/r/reactjs/comments/496db2/large_open_source_reactredux_projects/)
- [sound-redux](https://github.com/andrewngu/sound-redux)
- Concepts
  - [Higher-Order Components](http://engineering.invisionapp.com/post/higher-order-components/)
  - [What If React Was Really Only The V in MVC?](https://medium.com/javascript-inside/what-if-react-was-really-only-the-v-in-mvc-5854fd6f601c)
  - [Mixins Are Dead. Long Live Composition](https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750)
- Modais & Overlays
  - [Scalable Modals with React and Redux](https://codersmind.com/scalable-modals-react-redux/)
  - https://github.com/souporserious/react-tether
### React Router
- [A Simple React Router v4 Tutorial](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf)
- [Switch](https://github.com/ReactTraining/react-router/blob/master/packages/react-router/docs/api/Switch.md)
- [Code Split with Webpack](https://hackernoon.com/code-splitting-for-react-router-with-webpack-and-hmr-bb509968e86f)
- [Code Split Example](https://github.com/ReactTraining/react-router/blob/master/packages/react-router-dom/docs/guides/code-splitting.md)
- [React router modal-only routes](https://stackoverflow.com/questions/28795085/react-router-modal-only-routes)

### React Native
- [Code Sharing Between React Native and React Web Apps](https://medium.com/the-many/code-sharing-between-react-native-and-react-web-apps-b1e1de22fc53)
- [Sharing Code between React Web and Native Apps](http://jkaufman.io/react-web-native-codesharing/)
[Using redux-saga To Simplify Your Growing React Native Codebase](https://shift.infinite.red/using-redux-saga-to-simplify-your-growing-react-native-codebase-2b8036f650de)

### Redux
- [Anti-pattern: reacting to @@INIT action](https://github.com/reactjs/redux/issues/186)
- [redux-define](https://github.com/smeijer/redux-define)
- [Redux Ecosystem](https://github.com/markerikson/redux-ecosystem-links/blob/master/widgets.md)
- [Usage with React](http://redux.js.org/docs/basics/UsageWithReact.html)
- [ToDo Example](https://github.com/rajaraodv/redux/tree/master/examples/todos)
- [Large SPA boilerplate use react redux](https://github.com/chen844033231/react-workflow)
- [[WP] Redux state organization with large application](https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md) ([source](https://github.com/Automattic/wp-calypso/tree/master/client/state))
- [How to use Redux on highly scalable javascript applications?](https://medium.com/@alexmngn/how-to-use-redux-on-highly-scalable-javascript-applications-4e4b8cb5ef38)
- [Redux AJAX request examples](https://gist.github.com/markerikson/bb7589d395db3fe2a7bde5996ee7f193)
- [Usage with React Router](http://redux.js.org/docs/advanced/UsageWithReactRouter.html)
- [Timers in React Apps with Redux](https://medium.com/@machadogj/timers-in-react-with-redux-apps-9a5a722162e8)
- [A Beginner's Guide to Redux Middleware (timers)](https://www.codementor.io/vkarpov/beginner-s-guide-to-redux-middleware-du107uyud)
- [Discussion about action constats names (redux issue)](https://github.com/reactjs/redux/issues/384) ([wp example](https://github.com/Automattic/wp-calypso/blob/master/client/state/posts/actions.js))
- [Actions (playing sound) based on Redux store changes](https://stackoverflow.com/questions/37266247/actions-playing-sound-based-on-redux-store-changes)
- [Flux Standard Action](https://github.com/acdlite/flux-standard-action)
- Concepts
  - [Reusing Reducer Logic](http://redux.js.org/docs/recipes/reducers/ReusingReducerLogic.html) ([see multireducer](https://github.com/erikras/multireducer/blob/master/docs/Usage.md))
  - [Question: How to choose between Redux's store and React's state?](https://github.com/reactjs/redux/issues/1287)
  - [Encapsulation in Redux: the Right Way to Write Reusable Components](https://blog.javascripting.com/2016/02/02/encapsulation-in-redux/)
- Organization
    - [Organizing State](https://redux.js.org/docs/faq/OrganizingState.html)
    - [Where should my “business logic” go?](https://medium.com/@jeffbski/where-do-i-put-my-business-logic-in-a-react-redux-application-9253ef91ce1)
    - [Where do I put my business logic in a React-Redux application?](https://medium.com/@jeffbski/where-do-i-put-my-business-logic-in-a-react-redux-application-9253ef91ce1)
    - https://github.com/erikras/ducks-modular-redux
    - Action names
      https://github.com/reactjs/redux/issues/786
- Libs
  - [Redux Hero Part 3: Choose Wisely (a Fun Introduction to reselect.js)](https://decembersoft.com/posts/redux-hero-part-3-choose-wisely-a-fun-introduction-to-reselect-js/)
  - https://github.com/erikras/multireducer
  - https://github.com/DataDog/redux-doghouse
- Convention
  - [Where to write to localStorage in a Redux app?](https://stackoverflow.com/questions/35305661/where-to-write-to-localstorage-in-a-redux-app)
  - [A Simple Naming Convention for Action Creators in Redux.js](https://decembersoft.com/posts/a-simple-naming-convention-for-action-creators-in-redux-js/)

### Redux Saga
- [using root saga or multiple sagas](https://github.com/redux-saga/redux-saga/issues/160)
- [Managing Side Effects In React + Redux Using Sagas](https://jaysoo.ca/2016/01/03/managing-processes-in-redux-using-sagas/)
- [Redux Saga: Você no controle das operações assíncronas](https://medium.com/nossa-coletividad/redux-saga-voc%C3%AA-no-controle-das-opera%C3%A7%C3%B5es-ass%C3%ADncronas-71c9e6b3aabc)
- [What is the difference between a saga, a process manager and a document-based approach?](https://stackoverflow.com/questions/15528015/what-is-the-difference-between-a-saga-a-process-manager-and-a-document-based-ap)
- [redux-saga - Saga Middleware for Redux to Handle Side Effects - Interview with Yassine Elouafi](https://survivejs.com/blog/redux-saga-interview/)
- [JavaScript Power Tools: Redux-Saga](https://formidable.com/blog/2017/javascript-power-tools-redux-saga/)
- Discussions
  - [Question: Authentication flow](https://github.com/redux-saga/redux-saga/issues/14)
  - [Different ways to watch actions](https://github.com/redux-saga/redux-saga/issues/684)
  - [https://stackoverflow.com/questions/34930735/pros-cons-of-using-redux-saga-with-es6-generators-vs-redux-thunk-with-es7-async](https://stackoverflow.com/questions/34930735/pros-cons-of-using-redux-saga-with-es6-generators-vs-redux-thunk-with-es7-async)
  - [How to cancel "all"?](https://github.com/redux-saga/redux-saga/issues/988)

### Redux Forms
- [Redux Forms and Sagas](https://github.com/redux-saga/redux-saga/issues/161#issuecomment-191312502)

### Redux Dev Tools
  https://github.com/gaearon/redux-devtools
- https://github.com/zalmoxisus/redux-devtools-extension
- https://github.com/zalmoxisus/redux-remotedev
- [Using Redux Devtools in Production](https://medium.com/@zalmoxis/using-redux-devtools-in-production-4c5b56c5600f)

### Testing
 - [Saga, Testing error handling?](https://github.com/redux-saga/redux-saga/issues/28)
 - [Real integration tests with React, Redux and Router](https://medium.freecodecamp.org/real-integration-tests-with-react-redux-and-react-router-417125212638)
 - [Testing React Router apps with Jest and Enzyme](https://medium.com/@antonybudianto/react-router-testing-with-jest-and-enzyme-17294fefd303)
 - [Enzyme: JavaScript Testing utilities for React](https://medium.com/airbnb-engineering/enzyme-javascript-testing-utilities-for-react-a417e5e5090f)
 - [Testing Redux](https://hackernoon.com/redux-testing-step-by-step-a-simple-methodology-for-testing-business-logic-8901670756ce)
 - https://github.com/wix/redux-testkit
 - [Unit Testing React Components: Jest or Enzyme?](https://www.codementor.io/vijayst/unit-testing-react-components-jest-or-enzyme-du1087lh8)
 - [React and Enzyme example](https://github.com/vjwilson/enzyme-example-jest/blob/master/src/__tests__/Foo-test.js)
 - [Testing Components](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#testing-components)
 - [Enzyme](http://airbnb.io/enzyme/)
 - [enzyme-matchers for React](https://github.com/blainekasten/enzyme-matchers)
 - [Am I testing connected components correclty?](https://github.com/reactjs/react-redux/issues/325)
 - http://redux.js.org/docs/recipes/WritingTests.html

### Advanced ES6 Features
- Generators
  - [The Hidden Power of ES6 Generators: Observable Async Flow Control](https://medium.com/javascript-scene/the-hidden-power-of-es6-generators-observable-async-flow-control-cfa4c7f31435)
  - [The Definitive Guide to the Javascript Generators](https://github.com/gajus/gajus.com-blog/blob/master/posts/the-definitive-guide-to-the-javascript-generators/index.md)

### Functional programming
- [Why care about functional programming? Part 1: Immutability](https://miles.no/blogg/why-care-about-functional-programming-part-1-immutability)
- [What is a Pure Function?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)-
- [What is Thunk](https://www.wikiwand.com/en/Thunk)
- [Functional Programming In JavaScript — With Practical Examples (Part 1) (Functors, Monads)](https://medium.freecodecamp.org/functional-programming-in-js-with-practical-examples-part-1-87c2b0dbc276)

### Immutability
- [Efficient implementation of immutable (double) LinkedList](https://stackoverflow.com/questions/10045446/efficient-implementation-of-immutable-double-linkedlist)
- [Anjana Vakil: Immutable data structures for functional JS | JSConf EU 2017](https://www.youtube.com/watch?v=Wo0qiGPSV-s)

### Offline first & Progressive Web Apps
- [The App Shell Model](https://developers.google.com/web/fundamentals/architecture/app-shell)
- [Offline-First Architecture for Progressive Web Applications and React Native](https://hackernoon.com/introducing-redux-offline-offline-first-architecture-for-progressive-web-applications-and-react-68c5167ecfe0)
- [redux-offline](https://github.com/jevakallio/redux-offline)
- [create-react-app + sw-precache = PWA](http://www.phpied.com/create-react-app-sw-precache-pwa/)
- https://github.com/GoogleChrome/sw-precache
- [Progressive Web Apps with React.js: Part 3 — Offline support and network resilience](https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-3-offline-support-and-network-resilience-c84db889162c)
- [Redux Persist](https://github.com/rt2zz/redux-persist)
- [How to refresh the page after a ServiceWorker update?](https://stackoverflow.com/questions/34865072/how-to-refresh-the-page-after-a-serviceworker-update)
- Service Worker Issues
  - https://stackoverflow.com/questions/41891031/refresh-page-on-controllerchange-in-service-worker
  - https://stackoverflow.com/questions/41502870/service-worker-reload-page-on-cache-update
  - https://github.com/GoogleChrome/sw-precache/blob/master/demo/app/js/service-worker-registration.js

### Webpack
- [A beginner's guide to Code Splitting with React Router and Webpack 2](https://brotzky.co/blog/code-splitting-react-router-webpack-2/)
- Code Spliting
  - https://github.com/insin/react-examples/tree/master/code-splitting-redux-reducers
  - [Extract text chunks](https://github.com/webpack/webpack/tree/master/examples/multiple-entry-points-commons-chunk-css-bundle)
- Plugins
  - https://github.com/dominique-mueller/simple-progress-webpack-plugin
  - https://github.com/faceyspacey/extract-css-chunks-webpack-plugin
- Loaders
  - https://survivejs.com/webpack/loading/images/
- Hot Loading
  - [HMR issue with modules](https://github.com/facebookincubator/create-react-app/issues/2317)
  - [Redux HMR](https://gist.github.com/markerikson/dc6cee36b5b6f8d718f2e24a249e0491)
  - https://github.com/gaearon/react-hot-loader
  - https://webpack.js.org/guides/hot-module-replacement/
  - https://github.com/KleoPetroff/react-webpack-boilerplate
- Split Config
  - https://github.com/react-boilerplate/react-boilerplate/commit/d61413074e1463e1f959e59878381e968558745b
  - https://github.com/goldhand/cookiecutter-webpack/tree/master/%7B%7Bcookiecutter.repo_name%7D%7D/config
- Cache
  - https://webpack.js.org/guides/caching/
- DllPlugin
  - https://robertknight.github.io/posts/webpack-dll-plugins/
  - https://engineering.bitnami.com/articles/optimizing-your-webpack-builds.html
- Issues
  - [Moment locale issue](https://github.com/facebookincubator/create-react-app/blob/e91648a9bb55230fa15a7867fd5b730d7e1a5808/packages/react-scripts/config/webpack.config.prod.js#L339)
  - [Generate CSS from chunks](https://github.com/webpack-contrib/extract-text-webpack-plugin/issues/455)

## CSS

### CSS Modules
- [CSS Modules by Example](https://www.andrewhfarmer.com/css-modules-by-example/)
- [CSS Modules — Solving the challenges of CSS at scale](https://medium.com/front-end-developers/css-modules-solving-the-challenges-of-css-at-scale-85789980b04f)
- [CSS Modules - Welcome to the Future](https://glenmaddern.com/articles/css-modules)

## Environment
 - [.env metodology](https://12factor.net/config)
 - https://www.npmjs.com/package/dotenv

## Shell
- [Command-line interface description language](http://docopt.org/)

## Server-side

### JSON Web Token
- [Introduction to JSON Web Token](https://jwt.io/introduction/)
- [Securing React Redux Apps With JWT Tokens](https://medium.com/@rajaraodv/securing-react-redux-apps-with-jwt-tokens-fcfe81356ea0)
- [Express JWT Permissions](https://github.com/MichielDeMey/express-jwt-permissions)

### Amazon S3
- [Static Website on S3](http://aserafin.pl/2016/03/23/react-router-on-amazon-s3/)
- [Deploying create-react-app to S3 and CloudFront](https://medium.com/@omgwtfmarc/deploying-create-react-app-to-s3-or-cloudfront-48dae4ce0af)

## Libraries to take a look

### Browser/Server
- https://www.npmjs.com/package/debug ([example](https://github.com/Automattic/wp-calypso/blob/master/client/state/sites/domains/actions.js))
- https://github.com/mafintosh/is-my-json-valid
- https://codemix.github.io/flow-runtime/#/

### React 
- https://github.com/paypal/react-autocompletely (autocomplete)
- https://github.com/souporserious/react-tether (overlays)

### Redux
- https://github.com/acdlite/redux-actions
- https://github.com/acdlite/redux-promise
- https://github.com/gaearon/redux-thunk
- https://github.com/jaredpalmer/formik
- https://github.com/kuy/redux-tower

### Yarn 
- [Interactive Upgrade](https://github.com/yarnpkg/yarn/pull/1444)

## Others

### Services
[Package Quality](http://packagequality.com/)

### React Ecosystem Links
- https://github.com/markerikson/react-redux-links
