---
id: a6b0bb188d873cb2c8729495
title: Convert HTML Entities
isRequired: true
challengeType: 5
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
    testString: 'assert.match(convertHTML("Dolce & Gabbana"), /Dolce &amp; Gabbana/, "<code>convertHTML("Dolce & Gabbana")</code> should return <code>Dolce &&#8203;amp; Gabbana</code>.");'
  - text: ''
    testString: 'assert.match(convertHTML("Hamburgers < Pizza < Tacos"), /Hamburgers &lt; Pizza &lt; Tacos/, "<code>convertHTML("Hamburgers < Pizza < Tacos")</code> should return <code>Hamburgers &&#8203;lt; Pizza &&#8203;lt; Tacos</code>.");'
  - text: ''
    testString: 'assert.match(convertHTML("Sixty > twelve"), /Sixty &gt; twelve/, "<code>convertHTML("Sixty > twelve")</code> should return <code>Sixty &&#8203;gt; twelve</code>.");'
  - text: ''
    testString: 'assert.match(convertHTML("Stuff in "quotation marks""), /Stuff in &quot;quotation marks&quot;/, "<code>convertHTML(&apos;Stuff in "quotation marks"&apos;)</code> should return <code>Stuff in &&#8203;quot;quotation marks&&#8203;quot;</code>.");'
  - text: ''
    testString: 'assert.match(convertHTML("Schindler"s List"), /Schindler&apos;s List/, "<code>convertHTML("Schindler&apos;s List")</code> should return <code>Schindler&&#8203;apos;s List</code>.");'
  - text: ''
    testString: 'assert.match(convertHTML("<>"), /&lt;&gt;/, "<code>convertHTML("<>")</code> should return <code>&&#8203;lt;&&#8203;gt;</code>.");'
  - text: ''
    testString: 'assert.strictEqual(convertHTML("abc"), "abc", "<code>convertHTML("abc")</code> should return <code>abc</code>.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function convertHTML(str) {
  // &colon;&rpar;
  return str;
}

convertHTML("Dolce & Gabbana");

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
