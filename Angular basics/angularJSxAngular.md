Article wich this md is based:
    https://www.upgrad.com/blog/angular-vs-angularjs/


# Angular
Angular = Typescript based alternative to AngularJS, used to create 
dynamic web applications.

- It is the most used "Angular" today.
- Based on Typescript
- Modular design, significantly faster in comparison with AngularJS.
- Uses Hierarchy of components
- UI is defined as a component and then composed

# AngularJS

AngularJS = Javascript written open-source single-page applications framework.

- Has unique features such as the ability to change static HTML to dynamic HTML.
- Uses scope and controllers.
- Implements standard directives diferently.
- UI is defined using component directives

## Major Differences Between Angular and AngularJS

- Language

    The most basic difference between the two open-source frameworks is that
    Angular is Typescript-based (superset of ES6) while AngularJs is based on
    Javascript.

- Components and Directives

    Another crucial distinction is that Angular's operation is based on a hierarchy
    of components while angularJS has a pack of directives wich enable code
    reusability and writing distinct codes. It also uses scope and controllers.

    Angular components play a huge role in building user interfaces.
    Each portion of the UI is defined as a component and then composed.

    In AngularJS, the UI is defined using component directives that exclusively
    define all the same angular components such as templetes,
    input/output bindings, etc.

- Based On Architecture 

    Angular’s framework primarily uses components including structural directives
    and attributive directives which come with templates.

    In Angular’s approach, the functional and logical components are divided
    as per their purposes and can serve the application better. 

    While the former is used in the modification of the DOM layout,
    the latter is responsible for altering the behaviour of the DOM. 


    Angular JS, on the other hand, operates on the model-view-controller (MVC)
    framework where, as the Controller, it plays a central role in
    managing data, rules, receiving the input and processing it into commands
    to be sent to the Model and View.
    
    It also managers how applications behave. 

- Dependency Injection 
    
    While AngularJS doesn’t employ DI (it uses directives), Angular has a hierarchical DI system to enhance performance. 

- Routing

    AngularJS uses @routeProvider.when to define routing information. Angular, on the other hand, uses a URL to imitate a directive to get to the client-view. Here, @Route configuration is used for routing information. This gives Angular an edge over AngularJS. 

- Performance And Speed
  
    AngularJs has a separate two-way binding feature which means less time and effort invested. Angular has a better structure which becomes crucial in enhancing the speed and performance of its operations. 

    In the case of AngularjS, you have the ng-bind for one-way binding and the ng-model for two-way binding. In Angular, ngModel does both. It uses symbols to denote the type of binding:

    One-way binding – []
    Two-way binding – [()]
    Event binding – ()
    Property binding – []

 - Testing And Tools
    AngularJs relies on IDE and Webstorm, third-party Javascript tools, for building applications and testing for errors. 

    Angular again scores for using Command Line Interface (CLI) for project building. The added benefit is that this results in reduced time, and greater accessibility when it comes to testing. 

- Management 
    Angular projects are easier to manage than AngularJS projects because of how structured they are. This is especially a plus when it comes to bigger applications. 
    $note: This is kinda of a opnion, why is easy ?

- Detecting Changes 
    AngularJS uses scope.$apply() to manually or by default make changes in data bindings after every event. 

    Angular doesn’t need scope.$apply() function. Since it runs in the Angular zone, Angular is always aware when a certain code ends. In this manner, it initiates the change detection process.

## Angular vs Angular JS: Final Thoughts
    While both Angular vs Angular JS have distinct benefits to offer developers, Angular comes on the top in several categories. Also, Angular’s dynamic web and single-page applications are extremely mobile-friendly. AngularJS code, on the other hand, doesn’t support mobile applications and this is possibly the biggest advantage Angular has over AngularJs. So, that’s about it in the Angular vs Angular JS debate. 
