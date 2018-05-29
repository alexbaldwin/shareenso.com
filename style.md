---
title: Style guide
date: 2018-05-29 01:31:00 Z
permalink: "/style/"
layout: post
hide: true
how_it_works:
  features:
  - image: "/img/self-hug.jpg"
    title: Share your heartbeat
    text: |
      Hold Enso in your palm. It senses your heartbeat. You feel the gentle pulse in your hand.

      Then the magic happens.

      When you give Enso to someone, they will feel your heartbeat in their hand.

      Use Enso to say I love you.

      Save the heartbeats of people you love... and carry them with you.
---

<h1 class="h1 serif mb2">Style guide</h1>

---
## Hide a page from search engines

```
---
hide: true
---
```

In the frontmatter of a document, add a true boolean to the hide field.

---

## Buy button

{% include buy.html %}

```
{% raw %}
{% include buy.html %}
{% endraw %}
```

You can add a buy button by including the above code anywhere.

---

## Feature up

{% include feature-up.html data=page.how_it_works large_format=true %}

```
{% raw %}
{% include feature-up.html data=page.how_it_works large_format=true %}
{% endraw %}
```

Using the `large_format` flag, you can make the images a full width square.
---
