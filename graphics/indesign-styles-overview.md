---
description: >-
  In InDesign, styles are pre-defined sets of formatting attributes that you can
  apply to text or objects to maintain consistency and save time.
icon: text
---

# InDesign Styles Overview

{% hint style="info" %}
Have questions about InDesign styles? Reach out to [Ginny Fowler](mailto:ginny.fowler@robinsmorton.com) or [Allison Mathews](mailto:allison.mathews@robinsmorton.com).
{% endhint %}

## Types of styles

* Paragraph styles
* Character styles
* Object styles
* Table styles
* Cell styles

### Paragraph and Character Styles

[Basics of pararaph and character styles](https://helpx.adobe.com/indesign/using/paragraph-character-styles.html)

#### Why use styles?

Using styles in InDesign saves time and ensures consistency by allowing you to apply a pre-defined set of formatting rules to text and objects with a single click. This makes global changes simple, as editing a style automatically updates all instances where that style is used, which is especially useful for large documents. Styles also improve workflow by minimizing repetitive manual formatting, reducing errors, and providing a more professional and organized final product.

#### Paragraph styles are _rules_.

A paragraph style determines what font, size, leading, spacing, etc. applies to a given paragraph of text. They tend to be named for the purpose that type of paragraph serves: Heading, List, Body.

**Every paragraph in your document should have a paragraph style applied.**

{% hint style="info" %}
A paragraph is all the characters between two hard returns. Hard returns are marked by this symbol when you turn on the Show Hidden Characters feature: ¶
{% endhint %}

#### Character styles are _exceptions_.

Character styles apply only to selected characters, NOT to the entire paragraph by default. If you wanted to change some of the words in a sentence to bold, you would apply the bold character style to those words.&#x20;

#### When you manually change a feature of the text, it creates an _override_.

Style overrides in InDesign are manual formatting changes to text that are not saved to the original paragraph or character style. You can identify overrides with the "toggle style override highlighter" (a light blue highlight) and clear them by selecting the text and clicking "Clear Overrides in Selection" in the Styles panel, or you can "Redefine Style" to add the overrides to the style's definition

#### Paragraph Styles panel

{% columns %}
{% column %}
<figure><img src="../.gitbook/assets/styles-panel-pcstyles-id.avif" alt=""><figcaption></figcaption></figure>


{% endcolumn %}

{% column %}
A. More options (hamburger menu)

B. [Quick Apply](https://youtu.be/6hWofrThIqo?t=31)

C. [Style Override Highlighter ](https://helpx.adobe.com/indesign/using/paragraph-character-styles.html?x-product=Helpx%2F1.0.0\&x-product-location=Search%3AForums%3Alink%2F3.7.5#style-overrides)

D. [Apply Style Pack](https://helpx.adobe.com/indesign/using/work-with-style-packs.html)

E. [Clear overrides in selection ](https://helpx.adobe.com/indesign/using/paragraph-character-styles.html#style-overrides)

F. [Create new style group](https://helpx.adobe.com/indesign/using/styles.html#group_styles)&#x20;

G. [View Style packs](https://helpx.adobe.com/indesign/using/work-with-style-packs.html)&#x20;

H. Add selected style to my current CC Library&#x20;

I. Existing Style&#x20;

J. Default Style
{% endcolumn %}
{% endcolumns %}



## Overview of RM proposal styles

### \_Body

This is the base style for all body content in your documents.&#x20;

* Font family: NB International Pro
* Weight: Light
* Size: 9pt
* Leading: 12pt

**If needed in your document, you can change the \_Body style to 8pt size and 10pt leading.** This will allow you to fit more content on the page. Do not go below 8pt for body copy. You can go as small as 7pt for labels, table content, or other small chunks of text.

### GREP

[Deep dive into GREP](https://redokun.com/blog/grep-indesign)

A GREP is a formula (an expression) made up of meta-characters that can represent text, conditions or patterns (repetitions).

Paragraph Style GREPs allow you to search for a certain condition and apply formatting to the text found.

This application takes place automatically- as soon as you insert the text that presents the situation described by the GREP, and you associate the Paragraph Style in which you inserted the GREP, InDesign adds the formatting immediately.

The formatting is controlled by a Character Style that you will have to assign when you create the GREP.

{% columns %}
{% column width="58.333333333333336%" %}
**GREP styles that are applied to the \_Body paragraph style in our proposals:**

1. Apply character style **NoBreak** to text **Robins & Morton**\
   &#xNAN;_&#x54;his ensures the full name Robins & Morton is always on the same line._
2. Apply character style **Superscript** to text **®**\
   &#xNAN;_&#x54;his ensures all registration marks are superscripted as you type them._
3. Apply character style **NoBreak** to text **.{12}$**\
   &#xNAN;_&#x54;his forces the last 12 characters in a paragraph to be on one line, with the goal of avoiding_ [_widows_](https://en.wikipedia.org/wiki/Widows_and_orphans) _(a single word on its own line at the end of a paragraph)._

{% hint style="warning" %}
If you have a small block of text and it keeps disappearing because it overflows the text box, delete this GREP rule and it may fix the problem.
{% endhint %}

1. Apply character style **Flag** to text **XX**\
   &#xNAN;_&#x54;his automatically flags any place you've entered XX as a placeholder for content you intend to enter in the future._
2. Apply character style **Flag** to text **xx**\
   &#xNAN;_&#x54;his automatically flags any place you've entered xx as a placeholder for content you intend to enter in the future._
{% endcolumn %}

{% column width="41.666666666666664%" %}
<figure><img src="../.gitbook/assets/Screenshot 2025-11-21 at 9.06.59 AM.png" alt=""><figcaption></figcaption></figure>


{% endcolumn %}
{% endcolumns %}



#### Dependencies

When you create a new paragraph style, you can set it to inherit qualities from another paragraph style. This means that when you change the base style, those changes will flow down to other styles that are "based on" the base style.&#x20;

Our List styles are based on the \_Body style. If you change the font size of the Body style to 8pt, the size of your List styles will also change to 8pt.&#x20;





