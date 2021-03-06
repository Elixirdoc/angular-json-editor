# angular-json-editor

json editor with angular.

This directive make you easier to work with [json-editor] (https://github.com/jdorn/json-editor)

## Usage

get js from `./lib/dist/angular.json.editor.js`

```javascript
angular.module('myApp', ['json-editor'])
        .controller('myCtrl', function('$scope'){
           $scope.options = { /* JSON data */ };
           $scope.data = { /* JSON data or API */ };
        })
```
and in html again you can use it like:

```html
<script src="./bower_components/angular/angular.js"></script>
<script src="./bower_components/angular-route/angular-route.js"></script>
<script src="./lib/dist/angular.json.editor.js"></script>

<div ng-app='myApp'>
    <div ng-controller='myCtrl'>
        <json-editor id="json_editor" options='options' data='data'></json-editor>
    </div>
</div>
```

## Options

Please reference [json-editor] (https://github.com/jdorn/json-editor).

## License

MIT

