# Introducing jQuery

JavaScript is a scripting language developed by Netscape to allow basic dynamic operations to be performed in browsers. Originally created to be easily learned by web developers to add basic interactivity to an HTML page, JavaScript has since evolved into a tool most developers can't live without. However, because of various cross browser and legacy issues, many operations programmers would consider simple in environments such as app development are comparatively complex.

### Enter jQuery.

jQuery offers the JavaScript developer more power and flexibility while simplifying and reducing the amount of code required. Started as a way to simplify object selection by John Resig back in 1995, jQuery has become an indispensible tool for any JavaScript developer.

jQuery is designed to offer cross browser support, allowing you to write your code once and have it run properly on every browser. jQuery makes it much easier to perform operations such as selecting individual or groups of items for manipulation, changing elements or the entire DOM in an HTML page, or making calls to the server to access remote resources.

---

### The magic of the $
In jQuery, the $ character is the shortcut to the jQuery factory, meaning that it provides access to the jQuery object and all of the power that jQuery offers. You can use the $ to access global objects and functions, and, more commonly, elements and other components in the DOM.

The first operation you'll typically perform in any page that uses jQuery is to register a document.ready event handler. The document.ready event handler executes after everything on the page has loaded, ensuring that the entire DOM is now in memory, and the jQuery library is now available.

There are a couple of ways to register this event handler. The first is to access the document object in jQuery, and register an event handler with the jQuery ready event.

```jQuery
$(document).ready(function() {
	// code here
});
```

Because registering an event handler with jQuery is so common, jQuery provides a shortcut. Simply passing a function into the constructor will register that function as the event handler for document.load.

```javascript
$(function() {
	// code here
});
```

Both of the code blocks above are semantically identical.


