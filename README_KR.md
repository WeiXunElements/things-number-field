# \<things-number-field\>

필드에 숫자 형식의 값을 넣어 정의한 설정에 따라서 포맷한다.

입력값 |  Value |  포맷 후
--|---|--
10000| '0,0.0000'| '10,000.0000'
10000.23| '0,0'| '10,000'
-10000| '0,0.0'| '-10,000.0'
10000.1234| '0.000'| '10000.123'
-10000| '(0,0.0000)'| '(-10,000.0000)'
-0.23| '.00'| '-.23'
-0.23| '(.00)'| '(.23)'
0.23| '0.00000'| '0.23000'
1230974| '0.0a'| '1.2m'
1460| '0a'| '1k'
-104000| '0a'| '-104k'
1| '0o'| '1st'
52| '0o'| '52nd'
23| '0o'| '23rd'
100| '0o'| '100th'

## Element 설명

Example:

```html
    <things-number-field format-with="#,###.000"></things-number-field>
```
*****

Example:

```html
    <things-number-field format-with="#,###.000">
      <h2>Hello things-number-field format</h2>
    </things-number-field>
```
*****

## Polymer-CLI 설치

먼저 [Polymer CLI](https://www.npmjs.com/package/polymer-cli)가 설치되어 있는지 확인한다. 다음, `polymer serve`를 실행하여 로컬에서 응용 프로그램을 제공한다.

## Application 보기

```
$ polymer serve
```

## Application 빌드

```
$ polymer build
```

이렇게 하면, `bundled/`와 `unbundled/` 하위 폴더가 있는 `build/` 폴더가 생성된다.
이 중에는 번들된 (Vulcanized) 빌드와 번들되지 않은 빌드가 모두 포함되어 있으며, 모두 HTML, CSS 및 JS 최적화 도구를 제공한다.

`polymer serve`에 게재할 폴더를 제공하여 빌드된 버전을 제공할 수 있다.

```
$ polymer serve build/bundled
```

## Tests 실행

```
$ polymer test
```

이미 [web-component-tester](https://github.com/Polymer/web-component-tester)를 통해 application을 테스트하도록 설정되어 있다. `polymer test`를 실행하여 로컬에서 application의 테스트 스위트를 실행한다.
