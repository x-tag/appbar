# About

The Application Bar provides the standard top header and navigation layout that is typical for Web Applications on mobile devices.  You can use any elements in place of the ```<div>``` tags in the example below.  The header element is required and will be created automatically if you're creating this tag using ```document.createElement('x-appbar')```;


# Syntax

```html
<x-appbar subheading="(2)">
  <div>=</div>
  <h2>Email</h2>
  <div>+</div>
  <div>?</div>
</x-appbar>
```
```javascript

var appbar = document.querySelector('x-appbar');
// Set the header message.
appbar.heading = "Messages";

// Set the subheading with the unread message count.
appbar.subheading = "(3)";

```


