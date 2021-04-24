# Singeton Design Pattern

## Description :
### When creating objects, especially in modularized applications such as Node.js apps, we often need a singular instance of an object to be available across all modules/functions. A Singleton helps us achieve that.
***

## Singleton in Node.js

* _The Node.js module system, incidentally, provides a basic framework for creating a rudimentary singleton. Let's say you have a module that exports two functions, as you can see here. When this module is imported across multiple files or multiple times in an application, only a single instance is created and referred to. This is because the module system caches the module the moment it is accessed using a require statement for the very first time. Thereafter, the same instance is referred to everywhere. No matter how many times you import this module across your application, it will access the same cached and common instance._

* _In singleton pattern, objects in classes can only have a single and common instance, with a single point of access. The module system in Node caches a module, then accessed for the first time using a require statement. Thereafter, the same instance is returned._

***

## Usage

Run `node app.js` command to execute the code.