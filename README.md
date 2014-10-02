hello-world
===========

just another repository
lalala lalala lalala 

blablabla-blablabla
<div></div>
cx.,m.b,mzb.
<!DOCTYPE html>


<html ng-app>
  <head>
    <meta charset="utf-8">
    <script src="js/angular.js"></script>
    <script src="js/upp.js"></script>
    <link href="css/s.css" rel="stylesheet" />

  </head>
  <body ng-controller="MainCtrl">         
    <h1> Привет, {{houseGroup.name}}!</h1>
    <ul ng-repeat="event in houseGroup.events">
      <li ng-click="notify(event.description);">{{event.name}}</li>
    </ul>
    <div>{{houseGroup.age}}</div> 
    <ol  ng-repeat="food in houseGroup.foods | limitTo: 3">
      <li ng-click="notify(food.description);">{{food.name}}</li>
    </ol> 

  </body>
</html>
