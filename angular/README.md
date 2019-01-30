# AngularJS References and Resources

## Links

### AngularJS
- [Angular Controller Inherintance](https://github.com/exratione/angularjs-controller-inheritance)
- [Learn directive part 1](http://www.sitepoint.com/practical-guide-angularjs-directives/)
- [Learn directive part 2](http://www.sitepoint.com/practical-guide-angularjs-directives-part-two/)
- [Pre and Post linking in directive](https://github.com/angular/angular.js/wiki/Understanding-Directives)
- [Access directive scope variables from directive controllers and vice versa](http://juristr.com/blog/2015/01/learning-ng-directives-access-scope-controller/)
- [Improving REST with ngResource](https://devdactic.com/improving-rest-with-ngresource/) (not all official documentation's details, but more fluent)
- [Building Angular with Flux pattern](https://medium.com/@gerard.sans/angular-using-flux-6a835c9c0656#.yy80cjpsj)
- [Angular with RxJS, introduction](https://medium.com/google-developer-experts/angular-introduction-to-reactive-extensions-rxjs-a86a7430a61f#.fehxo0888)
- [Demo of Angular 1 with component like Angular 2](https://github.com/petebacondarwin/ng1-component-demo/tree/master/app)
- [Introduction to Redux with Angular 2 and Typescript](http://blog.ng-book.com/introduction-to-redux-with-typescript-and-angular-2/)
- [NG6 Starter](https://github.com/AngularClass/NG6-starter): use to follow [Todd Motto style guide](https://github.com/toddmotto/angular-styleguide)
- [Angular 1 Component Based Architecture](http://blog.grossman.io/angular-1-component-based-architecture-2/): explain Todd Motto's style guide and ng6 starter
- [D3 Charts, Linear options](http://www.d3noob.org/2013/01/smoothing-out-lines-in-d3js.html). Apply them to [NVD3](https://krispo.github.io/angular-nvd3) inserting `interval: value` inside chart object options.

#### Style Guide
- [John Papa style guide](https://github.com/johnpapa/angular-styleguide) (prefer)
- [Todd Motto style guide](https://github.com/toddmotto/angular-styleguide): explain how to structure an application in the Angular 2 (based components) way
- [Official Git Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#)

#### Form validation
- [Learn basic validation](http://tutsnare.com/form-validation-with-angularjs/)

#### Security
- [Authentication routing](http://www.sitepoint.com/implementing-authentication-angular-applications/)
- [OAuth2 with Angular, the right way](https://jeremymarc.github.io/2014/08/14/oauth2-with-angular-the-right-way/)
- [Token Based Authentication for Single Page](https://stormpath.com/blog/token-auth-spa/)

#### Testing
- [Unit test for promises](http://www.bradoncode.com/blog/2015/07/13/unit-test-promises-angualrjs-q/)

### Angular

- [Angular awesome](https://github.com/AngularClass/awesome-angular2/blob/gh-pages/README.md#angular-2-features)
- [Angular 2 education](https://github.com/timjacobi/angular2-education)
- [Best practice change detector - Lucidchart](https://www.lucidchart.com/techblog/2016/05/04/angular-2-best-practices-change-detector-performance/?platform=hootsuite)
- [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)
- [Angular compiler](https://medium.com/@urish/a-deep-deep-deep-deep-deep-dive-into-the-angular-compiler-5379171ffb7a)

#### Immutability

- [Immutability and Encapsulation by Victor Savkin](http://victorsavkin.com/post/133936129316/angular-immutability-and-encapsulation)
- [Immutable.js and Redux with Angular 2](https://houssein.me/angular2-hacker-news): article with a tutorial to make a contact list following Redux's pattern and use Immutable structures

#### Change Detection

- [A gentle introduction into change detection in Angular - Max Koretskyi - 2018.12.08](https://blog.angularindepth.com/a-gentle-introduction-into-change-detection-in-angular-33f9ffff6f10)

#### CDK

- [Official Page](https://material.angular.io/cdk/categories)
- [Context Menu made easy - Netanel Basal - 2019.01.08](https://netbasal.com/context-menus-made-easy-with-angular-cdk-963797e679fc)

#### Observable

- [Taking andvantage of Observable](http://blog.thoughtram.io/angular/2016/01/06/taking-advantage-of-observables-in-angular2.html): article about why use Obsearvable instead of Promise. I don't like the way that he uses two obsearvable instead only one in WikipediaService. For me he can use **debounceTime** directly in search method.
- [Reactive programming for Angular 2](http://blog.angular-university.io/functional-reactive-programming-for-angular-2-developers-rxjs-and-observables/): post that it is going to go over the concept of Functional Reactive Programming from the point of view of an Angular 2 developer
- [Angular 2 and Functional Programming](http://blog.wolksoftware.com/the-rise-of-functional-programming-and-the-death-of-angularjs)

#### Manage State

- [Manage Shared Module - Best Practice](https://www.gurustop.net/blog/2017/02/14/shared-modules-in-angular-apps-providers-best-practices-and-what-does-forroot-do/)
- [Comprehensive Introduction to @ngrx/store](https://gist.github.com/btroncone/a6e4347326749f938510)
- [Managing state with Redux](https://medium.com/front-end-hacking/managing-state-in-angular-apps-with-ngrx-store-and-ngrx-effects-part-1-a878addba622): it shows how to manage the state using @ngrx/store and @ngrx/effects
- [Different type of state's application](https://blog.nrwl.io/using-ngrx-4-to-manage-state-in-angular-applications-64e7a1f84b7b)
- [Angular 2 with @ngrx](http://onehungrymind.com/build-better-angular-2-application-redux-ngrx/): old but good article to understand the different components involved;

#### Testing

- [Testing Recepies](http://slides.com/gerardsans/odessajs-testing-recipes#/4/12)

#### Tool
- [Compodoc to generate documentation from annotation](https://github.com/compodoc/compodoc)
- [NgRev for reverse engeneering of Angular applications](https://github.com/mgechev/ngrev)

#### Video
- [Thinking in Angular 2](https://www.youtube.com/watch?v=XlqoPpLMdwY): an overview of key Angular 2.0 concepts for Angular 1.0 and traditional javascript developers - with Rangle's Angular 2 Team


### Deploy

- [Deploy Angular app in S3 bucket](https://medium.com/wolox-driving-innovation/deploy-your-angularjs-app-to-aws-s3-with-ssl-3635a62533ab#.4o5fpn4fu)
