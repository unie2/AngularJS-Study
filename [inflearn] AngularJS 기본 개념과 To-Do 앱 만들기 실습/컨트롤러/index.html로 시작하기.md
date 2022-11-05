## ✔ index.html로 시작하기
### 1. 사용할 내장 디렉티브: `ng-app`, `ng-init`
  - ng-app: ng-app이 선언된 부분부터 angular를 사용한다고 알려주는 작업
  - ng-init: Javascript 변수나 함수를 초기화하는 데 사용

```html
<html>
  <head>
    <link data-require="bootstrap@3.3.6" data-semver="3.3.6" rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" />
    <script data-require="bootstrap@3.3.6" data-semver="3.3.6" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
    <script data-require="angularjs@1.5.7" data-semver="1.5.7" src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.7/angular.min.js"></script>
    <link rel="stylesheet" href="style.css" />
    <script src="script.js"></script>
  </head>
  
  <!-- name 이라는 변수에 'Chris'라는 문자열을 할당 -->
  <body ng-app ng-init="name = 'Chris'">
    <h1>Hello World!</h1>
  </body>
</html>
```

- - -
### 2. 표현식(expression)
- 중괄호 2개를 사용해서 변수명을 작성

```html
<body ng-app ng-init="name = 'Chris'">
    <h1>Hello {{name}}!</h1>
</body>
```
![결과](https://user-images.githubusercontent.com/54324782/200098605-dc8b41c1-b469-4ce8-887d-faff6d0638e7.png)
