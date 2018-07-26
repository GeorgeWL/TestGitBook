---
description: Test Page with all the default settings
---

# Initial page

## Links

{% page-ref page="second-page.md" %}

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

