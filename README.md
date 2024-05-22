# AngularJS: a brief introduction

https://angularjs.org/

## 1. Introduction

**AngularJS** is a structural framework for dynamic web applications

It was developed by **Google** and first released in **2010**

**AngularJS** allows developers to use HTML as a template language and extend HTML's syntax to express application **components** clearly and succinctly

It simplifies the development and testing of **single-page applications (SPAs)** by providing a client-side **MVC (Model-View-Controller)** architecture, **data binding**, and **dependency injection**

![image](https://github.com/luiscoco/AngularJS_brief_summary/assets/32194879/3f59e139-74ef-4832-b454-eef45be6fd87)

### Key Features of AngularJS

**1. Data Binding**: AngularJS provides **two-way data binding**, which means any changes in the **model** are reflected in the **view** and vice versa

This makes **synchronization** between the model and the view automatic and seamless

**2. Dependency Injection**: AngularJS has a built-in dependency injection mechanism that makes it easy to manage dependencies and implement modular code

It allows you to **inject services** like $http to make HTTP requests or custom services that you define

**3. Directives**: Directives are special tokens in the markup that tell the library to **do something to a DOM element** (e.g., ng-model, ng-bind, ng-repeat)

**4. Custom directives** can also be created to encapsulate and **simplify DOM manipulation**

**5. Controllers**: Controllers are **JavaScript functions** that are used to build the **business logic** of the application

They **control** the **data** that **flows** between the model and the view

**6. Services**: AngularJS comes with several built-in services like $http to make HTTP requests, $route for routing, and $timeout for delaying code execution. You can also create custom services

**7. Filters**: Filters format the value of an expression for display to the user. For example, the currency filter formats a number as a currency string

**8. Routing**: The $routeProvider service allows you to create different routes for your application, making it easy to navigate between different views

**9. Templates**: AngularJS uses plain HTML as its template language. The templates contain AngularJS-specific elements and attributes, which AngularJS processes and then renders

**10. Modules**: Modules are containers for different parts of your application (controllers, services, filters, directives, etc.). They help in keeping the code organized

## 2. How to install AngularJS

The latest version of AngularJS is 1.8.3

If you are using Angular Framework higher versions you should first uninstall it from your computer

```
npm uninstall -g @angular/cli
```

![image](https://github.com/luiscoco/AngularJS_brief_summary/assets/32194879/b5706ba3-81c3-4721-a823-efa8abf93680)

Now we install the AngularJS in our laptop. Run this command

```
npm install -g angular@1.8.2
```

![image](https://github.com/luiscoco/AngularJS_brief_summary/assets/32194879/617ec53f-ce30-4b18-8c82-4cee87afc305)

![image](https://github.com/luiscoco/AngularJS_brief_summary/assets/32194879/10e372fa-f4b2-4666-a398-687e833658e8)

## 3. Basic Example

Here is a simple example of an AngularJS application:

**HTML (index.html)**

```html
<!DOCTYPE html>
<html ng-app="myApp">
<head>
  <meta charset="UTF-8">
  <title>AngularJS App</title>
  <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.8.3/angular.min.js"></script>
  <script src="app.js"></script>
</head>
<body>
  <div ng-controller="MainController as mainCtrl">
    <h1>{{ mainCtrl.message }}</h1>
  </div>
</body>
</html>
```

**JavaScript (app.js)**
```javascript
// Define a module
var app = angular.module('myApp', []);

// Define a controller
app.controller('MainController', function() {
  this.message = 'Hello, AngularJS!';
});
```

### Advantages of AngularJS

**Declarative Code**: AngularJS lets you declare what you want to do without worrying about the underlying implementation

**Modular Development**: Its modular architecture allows you to create reusable components

**Community and Support**: As a Google-developed framework, AngularJS has strong community support and extensive documentation

### Limitations

Performance: AngularJS can be slower for applications with a large amount of data and complex bindings.

Learning Curve: AngularJS has a steep learning curve for beginners due to its complexity and wide array of features.

Legacy: AngularJS is now considered a legacy framework, with Angular (also known as Angular 2+) being the recommended version for new projects.

### Conclusion

AngularJS revolutionized web development by introducing a comprehensive framework for building dynamic **single-page applications**

Although its support has ended, it laid the foundation for modern front-end frameworks and continues to be a valuable tool for learning the concepts

of client-side MVC, data binding, and dependency injection

For new projects, it is recommended to use the modern Angular framework, which offers improved performance, scalability, and support
