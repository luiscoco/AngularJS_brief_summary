# AngularJS: a brief introduction

## 1. Introduction

**AngularJS** is a structural framework for dynamic web applications

It was developed by **Google** and first released in **2010**

**AngularJS** allows developers to use HTML as a template language and extend HTML's syntax to express application **components** clearly and succinctly

It simplifies the development and testing of **single-page applications (SPAs)** by providing a client-side **MVC (Model-View-Controller)** architecture, **data binding**, and **dependency injection**

**Key Features of AngularJS**

**Data Binding**: AngularJS provides **two-way data binding**, which means any changes in the **model** are reflected in the **view** and vice versa

This makes **synchronization** between the model and the view automatic and seamless

**Dependency Injection**: AngularJS has a built-in dependency injection mechanism that makes it easy to manage dependencies and implement modular code

It allows you to **inject services** like $http to make HTTP requests or custom services that you define

**Directives**: Directives are special tokens in the markup that tell the library to **do something to a DOM element** (e.g., ng-model, ng-bind, ng-repeat)

**Custom directives** can also be created to encapsulate and **simplify DOM manipulation**

**Controllers**: Controllers are **JavaScript functions** that are used to build the **business logic** of the application

They **control** the **data** that **flows** between the model and the view

**Services**: AngularJS comes with several built-in services like $http to make HTTP requests, $route for routing, and $timeout for delaying code execution. You can also create custom services

**Filters**: Filters format the value of an expression for display to the user. For example, the currency filter formats a number as a currency string

**Routing**: The $routeProvider service allows you to create different routes for your application, making it easy to navigate between different views

**Templates**: AngularJS uses plain HTML as its template language. The templates contain AngularJS-specific elements and attributes, which AngularJS processes and then renders

**Modules**: Modules are containers for different parts of your application (controllers, services, filters, directives, etc.). They help in keeping the code organized

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



## 3. 
