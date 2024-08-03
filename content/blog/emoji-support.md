---
author: "Hugo Authors"
title: "कम्बल वितरण"
date: "2019-03-05"
description: "सर्दियों के दौरान सड़कों पर ठिठुरते हुए गरीब और भिक्षुकों को कम्बल बांटने का कार्य भी हमारी समिति नियमित रूप से करती है। इस सेवा से हम उनकी ठंड से राहत दिलाते हैं और उनके जीवन में थोड़ी सी गर्माहट लाने का प्रयास करते हैं।"
tags: ["emoji","markdown", "css", "html", "themes"]
categories: ["themes", "syntax"]
ShowRelated: false
showToc: false
ShowBreadCrumbs: false
---

Emoji can be enabled in a Hugo project in a number of ways.

<!--more-->

The [`emojify`](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes).

To enable emoji globally, set `enableEmoji` to `true` in your site's [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.

{{< rawhtml >}}

<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>

{{< /rawhtml >}}

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

---

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.

```html
.emoji {
font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
}

```

```css

<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>

```
