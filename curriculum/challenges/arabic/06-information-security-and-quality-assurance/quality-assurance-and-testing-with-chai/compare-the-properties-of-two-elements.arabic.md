---
id: 587d824c367417b2b2512c4d
title: Compare the Properties of Two Elements
challengeType: 2
videoUrl: ''
localeTitle: ''
---

## Description
undefined

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=7").then(data => {assert.equal(data.state,"passed"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=7").then(data => {  assert.equal(data.assertions[0].method, "isAtMost", "5 is at most (<=) 5"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=7").then(data => {  assert.equal(data.assertions[1].method, "isAbove", "1 is greater than 0"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=7").then(data => {  assert.equal(data.assertions[2].method, "isAbove", "Math.PI = 3.14159265 is greater than 3"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: ''
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=7").then(data => {  assert.equal(data.assertions[3].method, "isAtMost", "1 - Math.random() is > 0 and <= 1. It is atMost 1 !"); }, xhr => { throw new Error(xhr.responseText); })'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
