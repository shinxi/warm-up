Popular FE Frameworks
===================
----------

ExtJS
-------------
[Official website](https://www.sencha.com/products/extjs/#overview)

> Sencha Ext JS is the most comprehensive MVC/MVVM JavaScript framework for building feature-rich, cross-platform web applications targeting desktops, tablets, and smartphones. Ext JS leverages HTML5 features on modern browsers while maintaining compatibility and functionality for legacy browsers.

> Ext JS features hundreds of high-performance UI widgets that are meticulously designed to fit the needs of the simplest as well as the most complex web applications. Ext JS templates and layout manager give you full control over your display irrespective of devices and screen sizes. An advanced charting package allows you to visualize large quantities of data. The framework includes a robust data package that can consume data from any backend data source. Ext JS also offers several out-of-the-box themes, and complete theming support that lets you build applications that reflect your brand. It also includes an accessibility package (ARIA) to help with Section 508 compliance.

* ExtJS is not used in internet exposed sites due to its heaviness. It is mostly used in websites which are intranet facing "corporate" websites.
* ExtJS has its own stack of technologies starting from the build process (Sencha CMD) going up to the less & compass generators, themes, and widgets.
* ExtJS is a big + for corporates because it has a very good set of built in widgets which are sufficient for any normal corporate application.
* The only 2 sources of getting your questions answered are the Sencha forums or StackOverflow in case of ExtJS
* Sencha expects payment for applications that you make money off of, though they also provide an OSS version in case your project is also open source
* ExtJS was not designed with Responsive Web Design in mind
* ExtJS will create a more consistent look-and-feel so both have their advantages.

----------


AngularJS
-------------------

[Github README](https://github.com/angular/angular.js)

>AngularJS lets you write client-side web applications as if you had a smarter browser. It lets you use good old HTML (or HAML, Jade and friends!) as your template language and lets you extend HTML’s syntax to express your application’s components clearly and succinctly. It automatically synchronizes data from your UI (view) with your JavaScript objects (model) through 2-way data binding. To help you structure your application better and make it easy to test, AngularJS teaches the browser how to do dependency injection and inversion of control.  
>AngularJS is the next generation framework where each component is designed to work with every other component in an interconnected way like a well-oiled machine. AngularJS is JavaScript MVC made easy and done right. (Well it is not really MVC, read on, to understand what this means.)  
> **MVC, no, MV`*` done the right way!**  
>MVC, short for Model-View-Controller, is a design pattern, i.e. how the code should be organized and how the different parts of an application separated for proper readability and debugging. Model is the data and the database. View is the user interface and what the user sees. Controller is the main link between Model and View. These are the three pillars of major programming frameworks present on the market today. On the other hand AngularJS works on MV*, short for Model-View-Whatever. The Whatever is AngularJS's way of telling that you may create any kind of linking between the Model and the View here.  
> **Interconnection with HTML at the root level**  
>AngularJS uses HTML to define the user's interface. AngularJS also enables the programmer to write new HTML tags (AngularJS Directives) and increase the readability and understandability of the HTML code. Directives are AngularJS’s way of bringing additional functionality to HTML. Directives achieve this by enabling us to invent our own HTML elements. This also helps in making the code DRY (Don't Repeat Yourself), which means once created, a new directive can be used anywhere within the application.  
>**Data Handling made simple**  
>Data and Data Models in AngularJS are plain JavaScript objects and one can add and change properties directly on it and loop over objects and arrays at will.  
>**Two-way Data Binding**  
>One of AngularJS's strongest features. Two-way Data Binding means that if something changes in the Model, the change gets reflected in the View instantaneously, and the same happens the other way around. This is also referred to as Reactive Programming, i.e. suppose a = b + c is being programmed and after this, if the value of b and/or c is changed then the value of a will be automatically updated to reflect the change. AngularJS uses its "scopes" as a glue between the Model and View and makes these updates in one available for the other.  
>**Less Written Code and Easily Maintable Code**
>Everything in AngularJS is created to enable the programmer ends up writing less code that is easily maintainable and readable by any other new person on the team. Believe it or not, one can write a complete working two-way data binded application in less than 10 lines of code. Try and see for yourself!  
>**Testing Ready**  
>AngularJS has Dependency Injection, i.e. it takes care of providing all the necessary dependencies to its controllers whenever required. This helps in making the AngularJS code ready for unit testing by making use of mock dependencies created and injected. This makes AngularJS more modular and easily testable thus in turn helping a team create more robust applications.

* AngularJS is an MVC framework that is particularly helpful for building applications.  It helps give structure and tools for the program that controls the web app.
* Enforces structure and best practices
* Lots of documentation available
* Dependency injection makes testing much, much easier
* Makes it easier to build large, complex applications in JavaScript
* Has essentially every basic piece needed for modern web applications (data binding, routing, etc)
* Steep learning curve!
* Can be difficult to debug at first
* Overkill for simple pages

----------


Bootstrap
-------------

[official website](http://getbootstrap.com/)
> Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.
> Bootstrap makes front-end web development faster and easier. It's made for folks of all skill levels, devices of all shapes, and projects of all sizes.

* **Preprocessors**: Bootstrap ships with vanilla CSS, but its source code utilizes the two most popular CSS preprocessors, Less and Sass. Quickly get started with precompiled CSS or build on the source.
* **One framework, every device**: Bootstrap easily and efficiently scales your websites and applications with a single code base, from phones to tablets to desktops with CSS media queries.
* **Full of features:** With Bootstrap, you get extensive and beautiful documentation for common HTML elements, dozens of custom HTML and CSS components, and awesome jQuery plugins.
* Easy to get started
* Great grid system
* Base styling for most HTML elements(Typography,Code,Tables,Forms,Buttons,Images,Icons)
* Extensive list of components
* Bundled Javascript plugins

----------

