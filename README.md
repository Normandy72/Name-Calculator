### Sequence:
1. add main files (index.html, app.js, angular.min.js)
2. add script tags in html file
3. add h1 and divs
4. create IIFE in app.js and add 'use strict'
5. create angular.module('name_of_module', array) without semicolon 
6. create .controller('name_of_controller', function($scope){...})
7. add attribute ng-app=""name_of_module" into tag body
8. add attribute ng-controller="name_of_controller" into tag div
9. add property name of $scope (equal empty string)
10. add property totalValue (initial value is 0)
11. add totalValue in tag div (in double curly braces)
12. add attribute ng-model="name" into tag input
13. add attribute ng-keyup="name_of_function();" into tag input - when key is up function is calling
14. define dispalyNumeric function into .controller function
15. create function that calculate total value