---
description: >-
  This page will tell you how to setup and format your documentation so you can
  feel empowered to make doc changes and have set guidelines to follow.
---

# Doc Formatting Guide

## Fonts and Headings

## Heading 1 - Use this for main headings

### Heading 2 - Use this for subheadings

#### Heading 3 - Use this for any deeper heading needs, points of emphasis, example titles, and short definitions

Paragraph text - Use this for... well... paragraphs

One important note here is that Heading 1 and Heading 2 will structure your document's right side navigation, so make sure these are used correctly.

All headings also have anchors you can use to help users navigate the documentation.

## Code Blocks and Handling Examples

### Code Block

```text
All code needs to be in a code block
regardless of how small/inconsequential it may seem.
This creates continuity and lets the reader know
what they're looking at prior to actually reading.
```

Please make sure to pick a file type in the upper right corner when editing the code block so that everything remains very explicit for the reader. 

Also, don't use the 'Add filename' button to add more code blocks that are dependent on each other \(ie. examples that require yaml and data service changes\). Those will be handled a little bit differently, which you'll see in the next section. 

![](.gitbook/assets/screen-shot-2019-10-22-at-2.21.32-pm.png)

### Handling Examples

When dealing with inserting examples into the documentation where you need more than one code block, use the 'Tabs' option, have one tab for each file you'll be referencing, and then add a single code block to each tab w/ that piece of the example.

Try to remember to follow smart naming conventions for tab names. At the very least, they should end with '.filetype'.

#### Doc Example Title

{% tabs %}
{% tab title="doc\_example\_title.py" %}
```python
Here be yer python code
```
{% endtab %}

{% tab title="stack.yaml" %}
```yaml
Here be yer yaml code
```
{% endtab %}

{% tab title="doc\_example\_title-template.html" %}
```markup
Here be yer HTML code
```
{% endtab %}
{% endtabs %}

