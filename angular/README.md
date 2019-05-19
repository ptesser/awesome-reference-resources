# Angular / AngularJS References and Resources

## Angular

- [Angular awesome](https://github.com/AngularClass/awesome-angular2/blob/gh-pages/README.md#angular-2-features)
- [Angular 2 education](https://github.com/timjacobi/angular2-education)
- [Best practice change detector - Lucidchart](https://www.lucidchart.com/techblog/2016/05/04/angular-2-best-practices-change-detector-performance/?platform=hootsuite)
- [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)
- [Angular compiler](https://medium.com/@urish/a-deep-deep-deep-deep-deep-dive-into-the-angular-compiler-5379171ffb7a)

#### Immutability

- [Immutability and Encapsulation by Victor Savkin](http://victorsavkin.com/post/133936129316/angular-immutability-and-encapsulation)
- [Immutable.js and Redux with Angular 2](https://houssein.me/angular2-hacker-news): article with a tutorial to make a contact list following Redux's pattern and use Immutable structures

#### Change Detection

- [Angular Change Detection - How Does It Really Work? - Angular University Blog - 2018.12.10](https://blog.angular-university.io/how-does-angular-2-change-detection-really-work/)
- [A gentle introduction into change detection in Angular - Max Koretskyi - 2018.12.08](https://blog.angularindepth.com/a-gentle-introduction-into-change-detection-in-angular-33f9ffff6f10)
- [Change Detection in Angular: Everything You Need to Know - Maximus Koretskyi - 2018.05.01](https://www.sitepoint.com/change-detection-angular/)
- [A Comprehensive Guide to Angular onPush Change Detection Strategy - Netanel Basal - 2018.05.01](https://netbasal.com/a-comprehensive-guide-to-angular-onpush-change-detection-strategy-5bac493074a4)

#### CDK

- [Official Page](https://material.angular.io/cdk/categories)
- [Context Menu made easy - Netanel Basal - 2019.01.08](https://netbasal.com/context-menus-made-easy-with-angular-cdk-963797e679fc)

#### Dependency Injection

- [Writing Configurable Modules - Michele Stieven - 2018.02.21](https://medium.com/@michelestieven/angular-writing-configurable-modules-69e6ea23ea42)
- [Total Guide To Angular 6+ Dependency Injection — providedIn vs providers: - Tomas Trajan - 2018.11.06](https://medium.com/@tomastrajan/total-guide-to-angular-6-dependency-injection-providedin-vs-providers-85b7a347b59f) 
- [Configurare le dipendenze utilizzando useFactory - Fabio Biondi - 2018.07.07](http://training.fabiobiondi.io/2018/07/07/angular-configurare-le-dipendenze-utilizzando-usefactory/)


#### Directives

- [Everything you need to know about <ng-template>, <ng-content>, <ng-container> and *ngTemplateOutlet in Angular - Prateek Mishra - 2018.10.28](https://medium.freecodecamp.org/everything-you-need-to-know-about-ng-template-ng-content-ng-container-and-ngtemplateoutlet-4b7b51223691)
- [Creating Reusable Components with NgTemplateOutlet in Angular - Mark P. Kennedy](https://alligator.io/angular/reusable-components-ngtemplateoutlet/)
- [The Power of Structural Directives in Angular - Netanel Basal - 2017.05.22](https://netbasal.com/the-power-of-structural-directives-in-angular-bfe4d8c44fb1)

#### Forms

- [Make Your Angular Form’s Error Messages Magically Appear - Netanel Basal - 2019.01.22](https://netbasal.com/make-your-angular-forms-error-messages-magically-appear-1e32350b7fa5)

#### Life Cycle Hooks

- [Creatively Decouple ngOnChanges - Siyang Kern Zhao - 2019.01.07](https://blog.angularindepth.com/creatively-decouple-ngonchanges-fab95395cc6e)

#### Observable

- [RxViz - Tool to show streams as a marble diagram animated](https://rxviz.com/)
- [Taking andvantage of Observable](http://blog.thoughtram.io/angular/2016/01/06/taking-advantage-of-observables-in-angular2.html): article about why use Obsearvable instead of Promise. I don't like the way that he uses two obsearvable instead only one in WikipediaService. For me he can use **debounceTime** directly in search method.
- [Reactive programming for Angular 2](http://blog.angular-university.io/functional-reactive-programming-for-angular-2-developers-rxjs-and-observables/): post that it is going to go over the concept of Functional Reactive Programming from the point of view of an Angular 2 developer
- [Angular 2 and Functional Programming](http://blog.wolksoftware.com/the-rise-of-functional-programming-and-the-death-of-angularjs)
- [Unsubscribe pipe operator - Netanel Basal](https://github.com/NetanelBasal/ngx-take-until-destroy)
- [RxJS: Avoiding takeUntil Leaks - Nicholas Jamieson - 2018.05.27](https://blog.angularindepth.com/rxjs-avoiding-takeuntil-leaks-fb5182d047ef)

#### Pipes

- [Memoized pipe functions in templates - Artem Lanovyy - 2019.01.23](https://medium.com/@ineedsomemeat/angular-optimization-memoized-pipe-functions-in-templates-75f62e16df5a)

#### Manage State

- [5 Tips to improve User Experience of your Angular app with NgRx - Alex Okrushko - 2018.12.17](https://blog.angularindepth.com/5-tips-to-improve-user-experience-of-your-angular-app-with-ngrx-6e849ca99529)
- [Manage Action Flow in @ngrx with @ngrx/effects - Anonymous - 2017.08.20](https://blog.nextzy.me/manage-action-flow-in-ngrx-with-ngrx-effects-1fda3fa06c2f)
- [Manage Shared Module - Best Practice](https://www.gurustop.net/blog/2017/02/14/shared-modules-in-angular-apps-providers-best-practices-and-what-does-forroot-do/)
- [Sign In with Google Social](https://codinglatte.com/posts/angular/sign-in-with-google-angular/)
- [Comprehensive Introduction to @ngrx/store](https://gist.github.com/btroncone/a6e4347326749f938510)
- [Managing state with Redux](https://medium.com/front-end-hacking/managing-state-in-angular-apps-with-ngrx-store-and-ngrx-effects-part-1-a878addba622): it shows how to manage the state using @ngrx/store and @ngrx/effects
- [Different type of state's application](https://blog.nrwl.io/using-ngrx-4-to-manage-state-in-angular-applications-64e7a1f84b7b)
- [Angular 2 with @ngrx](http://onehungrymind.com/build-better-angular-2-application-redux-ngrx/): old but good article to understand the different components involved;

#### Organizing Application

- [Organizing Angular Applications - Michele Stieven - 2017.11.11](https://medium.com/@michelestieven/organizing-angular-applications-f0510761d65a)
- [Becoming an Angular Environmentalist - Todd Palmer - 2018.07.19](https://blog.angularindepth.com/becoming-an-angular-environmentalist-45a48f7c20d8)

#### Testing

- [Testing Recepies](http://slides.com/gerardsans/odessajs-testing-recipes#/4/12)

#### Tool
- [Compodoc to generate documentation from annotation](https://github.com/compodoc/compodoc)
- [NgRev for reverse engeneering of Angular applications](https://github.com/mgechev/ngrev)


## AngularJS
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

## Deploy

- [Deploy Angular app in S3 bucket](https://medium.com/wolox-driving-innovation/deploy-your-angularjs-app-to-aws-s3-with-ssl-3635a62533ab#.4o5fpn4fu)


