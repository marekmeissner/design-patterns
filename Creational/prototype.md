### **Prototype**

* Used to create clones of exact same object.
* Objects that have method to clone themselves are called "prototypes".
* Thanks to that method we are able to clone even private fields.
* That way we can clone and add new methods to prototype.
* It is very flexible pattern, extremaly useful in some cases\
e.g. having a base configured class you don't have to double it when you need to use the same base, you can just clone and expand it.
* JavaScript uses prototypal inheritance, every JS function has it's prototype by default.
* Every instance of prototype has common expanded properties, only one instane occurs in memory.
