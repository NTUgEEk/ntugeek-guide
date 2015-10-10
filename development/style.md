# Coding style guideline

基本上 follow [google styleguide][google-styleguide]
下面簡略說明

## Python

照著 [pep8][pep8] 寫

## Javascript

寫法上：

- 使用 `'use strict';`
- 儘可能不要 expose global variable
- 可以的話使用 ES6 的寫法

格式上：

- indent: 2 spaces
- Always use `;`
- Class: FooBar
- variable: fooBar
- function: getFooBar
- `_` prefix 來表示 private or internel
- `() [] {}` 寫法很像 pep8，範例如下:
```javascript
// style 1
let arr = [1, 2, 3,
           4, 5, 6];
let arr = [ 1, 2, 3,
            4, 5, 6 ];
someFunc(param1, param2,
         param3);
// style 2
let obj = {
  test: 'asdf',
  asdf: 'test',
};
someFunc(
  param1,
  param2,
  param3
);
```

[google-styleguide]: https://github.com/google/styleguide
[pep8]: https://www.python.org/dev/peps/pep-0008/
