---
description: This is not an exhaustive list.
---

# Paragraph Styles

### Paragraph styles are _rules_.

A paragraph style determines what font, size, leading, spacing, etc. applies to a given paragraph of text. They tend to be named for the purpose that type of paragraph serves: Heading, List, Body.

**Every paragraph in your document should have a paragraph style applied.**

{% hint style="info" %}
A paragraph is all the characters between two hard returns. Hard returns are marked by this symbol when you turn on the Show Hidden Characters feature: ¶
{% endhint %}

<details>

<summary>_Body</summary>

This is the base style for all body content in your documents.&#x20;

* **Font family:** NB International Pro
* **Weight:** Light
* **Size:** 9pt
* **Leading:** 12pt
* **Hyphenation:** none
* **Space after:** 0.0625 in <img src="../../.gitbook/assets/Screenshot 2025-12-29 at 10.01.16 AM.png" alt="" data-size="line">

**If needed in your document, you can change the \_Body style to 8pt size and 10pt leading.** This will allow you to fit more content on the page. Do not go below 8pt for body copy. You can go as small as 7pt for labels, table content, or other small chunks of text.

#### Dependencies

Other body styles (\_Body NoSpace) and list styles are based on the _\__&#x42;ody paragraph style. What this means: If you change the size of the _\__&#x42;ody paragraph style to 8pt, other Body styles and list styles will adjust accordingly.

#### [GREP](./#grep)

The following GREP automations are applied whenever this paragraph style is used:

* **Apply style:** <mark style="background-color:$primary;">NoBreak</mark> **to text:** <mark style="background-color:$primary;">Robins & Morton</mark>
* **Apply style:** <mark style="background-color:$primary;">Superscript</mark> **to text:** <mark style="background-color:$primary;">®</mark>
* **Apply style:** <mark style="background-color:$primary;">NoBreak</mark> **to text:** <mark style="background-color:$primary;">.{12}$</mark> _(the last 12 characters of the paragraph; this helps avoid_ [_runts_](https://en.wikipedia.org/wiki/Widows_and_orphans)_)_
* **Apply style:** <mark style="background-color:$primary;">Flag</mark> **to text:** <mark style="background-color:$primary;">XX</mark>
* **Apply style:** <mark style="background-color:$primary;">Flag</mark> **to text:** <mark style="background-color:$primary;">xx</mark>
* **Apply style:** <mark style="background-color:$primary;">Flag</mark> **to text:** <mark style="background-color:$primary;">\\\[.\*?\\]</mark> (any text between two brackets)





</details>

