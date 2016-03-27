This project would help AspNet developers to jump start with a blank Angular application with login/registration support.

This is forked from the wonderfull work by [chasakell] (https://github.com/chsakell/aspnet5-angular2-typescript) fixing bugs and removing EF 7 dependency.


Frameworks, IDE & plugins
====================
* Visual studio 2015
* Angular 2 beta
* AspNetCore (aka Asp Net 5 or vNext) which targets both .Net Core & .Net 4.5.1
* Bootstrap 3
* Alertify for notifications
* Fancybox for login/registration modals
* Automatic node package restore for client side libraries with Visual Studio 2015
* Automatic bower package restore for client side libraries with Visual Studio 2015
* gulp to compile typescript, minify, uglify, generate source maps for debugging typescipt on browser etc
* Task explorer to watch and compile typescript with gulp during development and during build process
* System.Js as module loader with support for dynamic asynchronous on demand loading of js modules.

![alt tag](https://raw.githubusercontent.com/justcoding121/AspNetCore-Angular2-Seed/master/screenshots/Capture.PNG)

Features
=======
* AspNetCore (aka Asp Net 5 or vNext) as server side framework with purely REST services (JSON)
* Angular 2 beta as a pure single page application with static typings using typescript for client side code.
* Angular 2 PathLocationStrategy implemented with URL rewrite on server side. This will help to implement server side rendering for faster initial page loads in future.
* Cookie authentication seed for login/logout/registration

Future updates
=============
* Seed multilevel rest style routing (for example user/{userId}/account/{accountid}
* Seed multi-level side bar menu
* Seed a paged grid
