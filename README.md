# [ng-context-menu](http://ianwalter.github.io/ng-context-menu/)
**An AngularJS directive to display a context menu when a right-click event is triggered**

#### Step 1: Install ng-context-menu

Install using Bower:

```
bower install ng-context-menu --save
```

Include ng-context-menu.min.js in your app.

#### Step 2: Load the ng-context-menu module

```javascript
var app = angular.module('menu-demo', ['ngRoute', 'ng-context-menu'])
```

#### Step 3: Add the context-menu directive to a DOM element

```html
<div context-menu class="panel panel-default" data-target="myMenu"
     ng-class="{ 'highlight': highlight, 'expanded' : expanded }">
  ...
</div>
```

**Note:** The position of the dropdown menu can get a little out of whack if you place the dropdown
menu in a container with padding/margin/etc so it's best to place it as a direct child of the body element as is
shown in this example.

That's it, I hope you find this useful!

«–– [Ian](http://ianvonwalter.com)
