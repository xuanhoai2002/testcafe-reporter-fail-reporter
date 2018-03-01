# testcafe-reporter-fail-reporter
[![Build Status](https://travis-ci.org/xuanhoai2002/testcafe-reporter-fail-reporter.svg)](https://travis-ci.org/xuanhoai2002/testcafe-reporter-fail-reporter)

This is the **fail-reporter** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/xuanhoai2002/testcafe-reporter-fail-reporter/master/media/preview.png" alt="preview" />
</p>

## Install

```
npm install testcafe-reporter-fail-reporter
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter fail-reporter
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('fail-reporter') // <-
    .run();
```

## Author
fjn_diem_ntt (https://github.com/xuanhoai2002)
