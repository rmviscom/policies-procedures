# Tutorials and Troubleshooting

<details>

<summary>Layers</summary>

Our templates contain 3 distinct layers:

1. **Artboard notes:** This is a [non-printing layer](https://helpx.adobe.com/indesign/using/layers.html#set_a_layer_as_nonprinting). These are notes from the graphics team to help you use the template. You can hide the layer from the Layers panel if you prefer not to see them.
2. **Header Footer:** This layer is above the Content layer so that the header and footer (including page numbers) always appear on top of whatever graphic or images you put there.
3. **Content:** This layer is where all of your content should go.

You can add layers to your document as needed.

</details>

<details>

<summary>Printed proposals</summary>



</details>

<details>

<summary>Covers</summary>

**Automations:** The **Project Name** is automatically inserted in the footer of the following pages in your document. [Learn more about text variables.](https://helpx.adobe.com/indesign/using/text-variables.html)

**Cover designs:** Find additional cover designs in Egnyte. To use an alternate cover design, select the page in the pages panel, right click, select Move...

</details>

<details>

<summary>Table of Contents</summary>

Our templates include a Table of Contents that can be updated to automatically show the Section Headers from tab pages along with their correct page numbers.&#x20;

When the TOC is automatically generated and you export the document as an interactive PDF, the TOC items will be clickable.

[Learn more about Table of Contents.](https://helpx.adobe.com/indesign/using/creating-table-contents.html)

The Table of Contents can also be created manually by typing in your section titles and the correct page numbers. If you manually type in the TOC items and page numbers, they will not be clickable in an interactive PDF.

### How to update the automatically generated PDF

Go to the menu: Layout > Update Table of Contents.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-12-07 at 12.27.34 AM.png" alt="" width="152"><figcaption></figcaption></figure>

InDesign searches the document for text using the Section Header paragraph style and inserts that text in to the TOC along with the appropriate page number.

The items in the TOC use the TOC1 paragraph style.

### Troubleshooting

* If you update the Table of Contents and the styles look wrong (text in different colors, etc.) select the text, go to Character Styles, and click \[None]
* If items are missing from the TOC after updating, check the tab pages and make sure your section headers are using the Section Header paragraph style.
* If items you don't expect are in the TOC after updating, find the text in your document and change the paragraph style to something other than Section Header.

{% hint style="warning" %}
Updating the Table of Contents should be the last thing you do before exporting.
{% endhint %}

</details>

<details>

<summary>Tab pages</summary>

Tab pages separate sections of your document.&#x20;

**Automations:** Section Headers on tab pages are used to dynamically generate the Table of Contents - if you delete all of your tab pages, your TOC will be empty. [Learn more about generating TOCs in InDesign.](https://helpx.adobe.com/indesign/using/creating-table-contents.html)

{% hint style="info" %}
The details below refer to section divider pages included in our InDesign templates. To order Robins & Morton branded physical tabs with numbered or alphabetical tab label, visit the Index Tabs section of our [Hemlock portal](https://order.hemlock.com/robinsmorton).
{% endhint %}

{% hint style="success" %}
## Best practice

When creating your proposal document, select a tab page layout, then duplicate that page to create other tab pages.
{% endhint %}

### Default Tab Pages

<div align="center"><figure><img src="../../../.gitbook/assets/Screenshot 2025-12-04 at 4.26.20 PM.png" alt="" width="271"><figcaption><p>Example: vertical tab page</p></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot 2025-12-04 at 4.44.39 PM.png" alt="" width="362"><figcaption><p>Example: horizontal tab page</p></figcaption></figure></div>

**Size:** 8.5"x11"

**When to use:** Standalone tab pages are best when you do not have a hard page limit, or it's explicitly stated that tab pages do not count towards the overall page count.

**Section Header:** Replace this text with the title of your section. **This text (using the Section Header paragraph style) is used to automatically generate the Table of Contents.** If you change the paragraph style to something other than Section Header, it will not appear in the TOC.&#x20;

The running section headers on your content pages also update automatically based on the last Section Header paragraph style.&#x20;

<div data-full-width="false" data-with-frame="true"><figure><img src="../../../.gitbook/assets/Screenshot 2025-12-04 at 4.17.13 PM.png" alt=""><figcaption><p>Running Section Header on content page - this text will automatically update to match the text in the last used Section Header paragraph style (used on tab pages).</p></figcaption></figure></div>

**Other content:** Tab pages can be used to emphasize your hook, show photos of our people, highlight testimonials, or promote relevant awards.&#x20;

**Layout options:**

**Photography options:** [OpenAsset gallery](https://robinsmorton.openasset.com/Page/Search#currentSearchItems=album%3A0%3D2762)



### Condensed Tab Page

If your proposal has a hard page limit, you may want to use condensed tab pages. These also include a Section Header that pulls into the TOC and flows down to the running section headers - but rather than being a standalone hero page, they allow you to include body content.&#x20;

{% hint style="info" %}
Use a single tab page style throughout your document - either the default page or condensed.
{% endhint %}

<div><figure><img src="../../../.gitbook/assets/Screenshot 2025-12-04 at 4.33.03 PM.png" alt="" width="272"><figcaption><p>Example Vertical Condensed Tab Page</p></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot 2025-12-05 at 8.01.14 AM.png" alt="" width="375"><figcaption><p>Example Horizontal Condensed Tab Page</p></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot 2025-12-05 at 8.03.31 AM.png" alt="" width="375"><figcaption><p>Example 11x17 Condensed Tab Page</p></figcaption></figure></div>

**Size:** 8.5"x11" and 11"x17" (for proposals that are all A3 pages)

**When to use:** Use condensed pages if you have a hard page limit and standalone tab pages are not excluded from the page count.

**Section Header:** Condensed tab pages still include text in the Section Header paragraph style, but the text also has a character style applied to make it smaller and red. As with the default page, if you change the paragraph style to something other than Section Header, your TOC and running page headers will fail to work correctly.

### 9"x11" Vertical Tab Pages

We have a custom parent page that has the same layout as the default tab pages, but the page is slightly wider than the 8.5"x11" content pages. This is for printed tabs that you want to stick out past the content pages when bound.&#x20;

{% hint style="info" %}
If you are printing 9"x11" tabs, have those pages printed on cardstock rather than regular paper.
{% endhint %}

</details>

<details>

<summary>Preflight</summary>

[Learn more about the Preflight Panel.](https://helpx.adobe.com/indesign/using/preflighting-files-handoff.html)

</details>

<details>

<summary>Headings</summary>

<figure><img src="../../../.gitbook/assets/MicrosoftTeams-image-53-2.jpg" alt=""><figcaption></figcaption></figure>

The purpose of headings is to allow readers to skim the page and still understand the overall meaning.&#x20;

The organization of your header styles should correspond to your content outline. Larger headers represent higher level sections, with smaller headings below. This allows the user to visually understand the organization of the content.

| Your outline                                                                                                                                              | Your layout                                                                                                                              |
| --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| <p>I. Our Value<br>      A. Quality<br>      B. Safety<br>      C. Budget<br>            1. Early procurement<br>            2. Target Value Delivery</p> | <div><figure><img src="../../../.gitbook/assets/Screenshot 2025-12-08 at 9.24.00 AM.png" alt=""><figcaption></figcaption></figure></div> |

{% hint style="success" %}
## Best practice

Your readers should understand your most important points even if they only read the headings.=
{% endhint %}

</details>

<details>

<summary>RFP Questions</summary>

Questions are quoted in our proposals to help the client understand the organization of the content.&#x20;

There are multiple paragraph styles designated for quoting the questions found in your RFP. **Question formatting should be consistent within your document** - all of your quoted questions should use the same paragraph style.

</details>

<details>

<summary>Page Numbering</summary>

Page numbering in InDesign can be customized by section. In the Default template, all pages are in a single section beginning with page 1.

To customize page numbering, you can designate any page as the beginning of a new section. However, you cannot have two pages numbered 1, for example - one section must have a different _style_ of numbering (like roman numerals).

#### To change the location of page 1 in your document:

1. **Start by changing the default numbering to roman numerals (i, ii, iii, etc.).** _This ensures you can create a new page 1 without getting the error that there is already a page 1 in your document._
   1. In the Pages panel, right-click or ctrl-click on the cover of your document
   2. Select **Numbering & Section Options...**\
      &#x20;![](<../../../.gitbook/assets/Screenshot 2025-12-21 at 10.16.39 AM.png>)
   3. Under **Page Numbering**, change style to <mark style="color:blue;">i, ii, iii, iv...</mark> \
      ![](<../../../.gitbook/assets/Screenshot 2025-12-21 at 10.19.51 AM.png>)



2. **Create a new section beginning with page 1.**
   1. Right click or ctrl-click on your new page 1 in the pages panel (usually your first tab page).
   2. Select **Numbering & Section Options...**
   3. Check **Start Section**
   4. Select **Start Page Numbering at: 1**&#x20;
   5. Change Style to <mark style="color:blue;">1, 2, 3, 4...</mark>\
      ![](<../../../.gitbook/assets/Screenshot 2025-12-21 at 10.25.40 AM.png>)

</details>

<details>

<summary>Margins, Columns, and Guides</summary>

<figure><img src="../../../.gitbook/assets/Screenshot 2025-12-27 at 10.33.39 AM.png" alt=""><figcaption><p>Types of guides and their default colors in InDesign</p></figcaption></figure>

{% hint style="info" %}
Go to **View > Grids & Guides** to see useful options. It's recommended to leave **Snap to Guides** and **Smart Guides** turned on generally.
{% endhint %}

### Margins

The margins on our templates designated by purple lines, and are set to .75" on the left and right (or inside and outside on facing pages). This is generous, but allows for binding if you need to print your proposal.

**Margins are important for maintaining a clean, professional look - keep content inside the page margins whenever possible.**

### Columns

Each page in our template contains column guides. These are meant to help align your content neatly and can be treated as suggestions - you do not have to align all content to a column guide.

{% hint style="info" %}
You can change the number of columns on a given page to suit your needs by going to **Layout > Margins and Columns...**
{% endhint %}

### Guides

You can add guides to any page by clicking and dragging from the ruler bars on the left and top. These are meant to be helpful and can also be treated as suggestions.





</details>

<details>

<summary>Org Charts</summary>

Org chart elements are made up of a table inside a text frame.

<figure><img src="../../../.gitbook/assets/Screenshot 2025-12-27 at 9.50.13 PM.png" alt=""><figcaption></figcaption></figure>

In addition to paragraph styles for the Role, Name, and Body, the look of Org Chart elements is governed by cell styles. [Learn more about cell style options.](https://helpx.adobe.com/indesign/using/table-cell-styles.html)



</details>

<details>

<summary>Design Templates</summary>

See [Design Templates](design-templates-and-layouts.md)

</details>

<details>

<summary>Matrix Templates</summary>

### Exporting data from Unanet

Our teams frequently want to include a matrix in a proposal showing which team members have worked together before. To simplify this process, follow these steps.

#### Step 1

To create a matrix, start by **exporting the data you need from Unanet**. [A report template has been created for you.](https://services.cosential.com/reports20/ReportsResults.cfm?ReportID=KbRP9DzEHLYWuusGkvUL4lriEgkQ~~\&ReportTypeID=1)

You can customize to add fields you need (currently contains Project Name, Construction Schedule - Calc Start Date, Construction Schedule - Calc End Date, Staff Team Name, Project Number, Size - Building Size, Final (or Current) Contract PC) and on the second page of the customization, you will add your team members here, make sure include in main query is checked as shown:

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Once you've downloaded your report, delete extraneous data from the Excel sheet and share with your team for changes.&#x20;

#### Step 2

Upload to CoPilot or ChatGPT and use this prompt:

_I am uploading a spreadsheet containing \[a list of projects] and \[the teams who have worked on them]. Create a matrix to display which team members have worked on which project. Show the projects as headers in each column, and the team members as headers in each row. Use X to mark the overlap. Provide a downloadable spreadsheet when finished._

#### Step 3

This folder:

{% code overflow="wrap" %}
```
/Shared/Marketing Department/Sales/Templates/Proposal Templates/Matrix Templates
```
{% endcode %}

contains templates for creating a data matrix in InDesign.&#x20;

</details>

<details>

<summary>Book Files</summary>

The Book Files folder is useful if you are working closely with another marketer on an RFP. We can set up each section as its own InDesign file so that two people can work on different parts of the document at the same time. Reach out to the graphics team for support.

</details>

## Troubleshooting

<details>

<summary>InDesign is running slow</summary>

**InDesign features that slow you down, but you can turn them off:**

**Live Preflight** can be turned off by deselecting the On checkbox.

Preferences > General > **Show Home Screen When No Documents Are Open** can be turned off.

Preferences > **Display Performance** > set to Typical renders the images at screen-rez, but sacrifices color management.

Preferences > Interface > Options > **Live Screen Drawing** can be set to Never and it will draw more quickly.

Preferences > File Handling > Saving InDesign files > **Save Preview Images** switches can be set to off.

Preferences > Type > **Smart Text Reflow** could be turned off.

Preferences > Advanced Type > **Type Contextual Controls** are two text switches that can slow down InDesign.

Pages Panel > panel menu button > Panel Options allows you to deselect **Show Thumbnails**.

Hyperlinks > panel menu button > and deselect **Auto Update URL Status**.

**Threaded Textframes**: consider flowing and threading text for only a few pages/frames instead of many.

**Cross-References** will slow down InDesign. Consider saving them for last.

</details>
