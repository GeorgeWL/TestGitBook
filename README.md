---
description: Test Page with all the default settings
---

# Initial page

## Links

{% page-ref page="api.md" %}

{% page-ref page="changelog.md" %}

{% page-ref page="faq.md" %}

## Getting Super Powers

Becoming a super hero is a fairly straight forward process:

```
$ give me super-powers
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world:

```
// Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```

## h1

### h2

#### h3

## Lists

### bullet

* Item
* Another Item

### ordered

1. One
2. Two

### tasks 

* [ ] Do this
* [ ] Do That
* [x] Done That

## Code block

### can be supplied language for context

```javascript
let items = ['test','testing','testing2']
console.log('items',items)
```

### Or just be generic

```text
let items = ['test','testing','testing2']
console.log('items',items)
```

## Hint Block

for important messages and hints

### info

{% hint style="info" %}
info
{% endhint %}

### warning

{% hint style="warning" %}
warning
{% endhint %}

### danger

{% hint style="danger" %}
danger
{% endhint %}

### success

{% hint style="success" %}
success
{% endhint %}

these can have children of H1, H2,H3, Task List and P nested inside of them.

{% hint style="info" %}
## Info

Some Paragraph

### Wowzers

Yep

#### Tasks

* [ ] Do this
* [ ] Do that
{% endhint %}

{% api-method method="post" host="" path="" %}
{% api-method-summary %}
API Method
{% endapi-method-summary %}

{% api-method-description %}
Method
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="order" type="string" required=false %}
enum, expects 'asc' or 'desc'
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}

{% api-method-body-parameters %}
{% api-method-parameter name="name" type="string" required=true %}
expects the name of a user
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## Embeds

### codepen

{% embed data="{\"url\":\"https://codepen.io/ainalem/full/XBgJYP/\",\"type\":\"rich\",\"title\":\"XOR\",\"icon\":{\"type\":\"icon\",\"url\":\"https://codepen.io/favicons/favicon-192x192.png\",\"width\":192,\"height\":192,\"aspectRatio\":1},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://s3-us-west-2.amazonaws.com/i.cdpn.io/449845.XBgJYP.small.34d483ed-f81a-4dff-b439-85160741ac83.png\",\"width\":384,\"height\":225,\"aspectRatio\":0.5859375},\"embed\":{\"type\":\"app\",\"url\":\"https://codepen.io/ainalem/embed/preview/XBgJYP?height=300&slug-hash=XBgJYP&default-tabs=css,result&host=https://codepen.io&embed-version=2\",\"html\":\"<iframe src=\\\"https://codepen.io/ainalem/embed/preview/XBgJYP?height=300&amp;slug-hash=XBgJYP&amp;default-tabs=css,result&amp;host=https://codepen.io&amp;embed-version=2\\\" style=\\\"border: 0; width: 100%; height: 300px;\\\" allowfullscreen></iframe>\",\"height\":300,\"aspectRatio\":null}}" %}

### youtube

{% embed data="{\"url\":\"https://www.youtube.com/watch?v=C0DPdy98e4c\",\"type\":\"video\",\"title\":\"TEST VIDEO\",\"description\":\"COUNTING LEADER AND TONE\",\"icon\":{\"type\":\"icon\",\"url\":\"https://www.youtube.com/yts/img/favicon\_144-vfliLAfaB.png\",\"width\":144,\"height\":144,\"aspectRatio\":1},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://i.ytimg.com/vi/C0DPdy98e4c/hqdefault.jpg\",\"width\":480,\"height\":360,\"aspectRatio\":0.75},\"embed\":{\"type\":\"player\",\"url\":\"https://www.youtube.com/embed/C0DPdy98e4c?rel=0&showinfo=0\",\"html\":\"<div style=\\\"left: 0; width: 100%; height: 0; position: relative; padding-bottom: 75.0019%;\\\"><iframe src=\\\"https://www.youtube.com/embed/C0DPdy98e4c?rel=0&amp;showinfo=0\\\" style=\\\"border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;\\\" allowfullscreen scrolling=\\\"no\\\"></iframe></div>\",\"aspectRatio\":1.3333}}" %}

### github

{% embed data="{\"url\":\"https://github.com/pixelinspiration\",\"type\":\"link\",\"title\":\"Pixel Inspiration\",\"description\":\"GitHub is where people build software. More than 28 million people use GitHub to discover, fork, and contribute to over 85 million projects.\",\"icon\":{\"type\":\"icon\",\"url\":\"https://github.com/fluidicon.png\",\"aspectRatio\":0},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://avatars0.githubusercontent.com/u/11177372?s=280&v=4\",\"width\":73,\"height\":73,\"aspectRatio\":1}}" %}

## Tabs content

{% tabs %}
{% tab title="First Tab" %}
tab content 1
{% endtab %}

{% tab title="Second Tab" %}
tab content 2
{% endtab %}
{% endtabs %}

## Maths

### uses standard maths

$$
7 + 1 = 8
$$

### uses LaTeX

$$
\int \zeta^{2}(x) \, dx
$$

## File Download

{% file src=".gitbook/assets/thumbsup.png" caption="image download" %}

