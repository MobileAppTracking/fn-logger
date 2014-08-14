Fn-logger
=========

A customized logger for front end debugging


Required bower packages
-----------------------
- jquery
- angular
- angular-sanitize
- lodash
- taffydb

Demo
----
- Demo can be found at http://mobileapptracking.github.io/fn-logger/

Getting started
----------------
1. Link scripts:
```
<script src="../fn.logger.js"></script>
```

2. Prepare the call of fn-logger

```
angular.module('testApp', ['fn.logger']).controller('TestController', function($scope, $log) {
  $log.warn(default, 'test');
});
```






