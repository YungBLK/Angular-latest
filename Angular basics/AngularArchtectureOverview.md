# Angular Architecture Overview

You write Angular applications by composing HTML templates, writing component classes to manage those templates, adding application logic in services, and boxing components and services in modules.

![architeture overview by image](https://miro.medium.com/max/700/0*lQaPheoHIZpLtzVw.png)

# Main building blocks of an Angular application:
 - Modules
 - Angular Libraries
 - Components
 - Templates
 - Metadata
 - Data binding
 - Directives
 - Services
 - Dependency injection


- # Modules
  Every angular app has a root module, conventionally named AppModule, wich provides
  the bootstrap mechanism that launches the application. An app typically contains many functional modules.

  Ex: BroserModules, NgModule, AppRoutingModule.

  If we want to use another custom Angular module, then we need to register that module inside the app.module.ts file. Organinzing code into distinct functional modules helps in mananging the development of complex applications, and in designing for re usability. 

- # Angular Libraries
   Angular has a colletion of JavaScript modules. You can think of them as library modules.

   Each Angular library name begins with the @angular prefix.

   For example, import Angular’s Component decorator from the @angular/core library like this:

   import { Component } from '@angular/core';

- # Components
    Every angular project has at least one component, the root component
    connects the component hierarchy with a page document object model (DOM).

    Each component defines the class that contains application data and logic, and it is associated with the HTML template that defines the view to be displayed in a target app. A component controls a patch of screen called a view.


    The @Component decorator identifies the class immediately below it as the component and provides the templete and related component-specific metadata.

- # Templates
    The angular template combines the HTML with Angular markup that can modify HTML elements before they are displayed. Template directives provde prgram logic, and binding markup connects your aapplication data and the DOM. There are two types of data binding

    - ## Event binding: Lets your app respond to user input in the target environment by updating tou application data.

    - ## Property binding: lets you interpolate values that are computed from your application data into the HTML.
