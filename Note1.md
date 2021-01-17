* 수업소개
    * Javascript
    * WEB
    * HTML
    * 정적, 동적

* 수업의 목적
    * Javascript는 사용자와 상호작용 하는 언어
    * night 버튼을 눌렀을 때 배경이 검은색이 아닌 회색으로 바뀌도록 만들고 싶다면, 어떻게 하면 될까요?
        ```js
        document.querySelector('body').style.backgroundColor='gray'
        ```

* HTML과 JS의 만남 : script 태그
    ```html
    <script>
        document.write('hello, world!');
    </script>
    ```
    * HTML : 정적
    * JavaScript : 동적

* HTML과 JS의 만남 : 이벤트

* HTML과 JS의 만남 : 콘솔

* 데이터 타입(문자열과 숫자)

* 변수와 대입연산자
    ```js
    var x = 1;
    var y = 1;
    var x + y;
    ```

* 웹브라우저 제어
    ```html
    <body>
    <body style="background-color: black; color: white;">
    ```

* CSS기초(style 속성)
    ```html
    <h1 style="color: blue">Javascript<h1>
    ```

* CSS기초(style 태그)
    ```html
    <head>
    <style>
        .js {
            font-weight: bold;
        }
    </style>
    </head>
    ```

* CSS기초(선택자)
    ```html
    <style>
    .js {
        color: red;
    }
    </style>
    ```
    ```html
    <style>
    #first {
        color: green;
    }
    </style>
    ```