---
author: Hugo Authors
title: गरीब बच्चों के लिए स्कूल ड्रेस
date: 2019-03-08
description: शिक्षा का अधिकार हर बच्चे का है, और हमारी समिति इस दिशा में महत्वपूर्ण कदम उठा रही है। हम हर साल गरीब बच्चों को स्कूल ड्रेस प्रदान करते हैं, ताकि वे स्कूल जाकर शिक्षा प्राप्त कर सकें और समाज की मुख्यधारा में शामिल हो सकें। यह पहल उनकी आत्म-गौरव और शिक्षा के प्रति उत्साह को बढ़ावा देती है।


tags: ["math","markdown", "css", "html", "themes"]
categories: ["themes", "syntax"]
math: true
ShowBreadCrumbs: false
---

Mathematical notation in a Hugo project can be enabled by using third party JavaScript libraries.

<!--more-->

In this example we will be using [KaTeX](https://katex.org/)

-   To enable KaTex globally set the parameter `math: true` in a project's configuration (`config.yml`)
-   To enable KaTex on a per page basis include the parameter `math: true` in content files

**Note:** Use the online reference of [Supported TeX Functions](https://katex.org/docs/supported.html)

### Examples

Inline math:
{{< rawhtml >}}

<p>
\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\)
</p>

{{< /rawhtml >}}

Block math:

$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
