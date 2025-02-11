---
marp: true
lang: en-US
title: "Marp Document Template"
theme: custom
size: a4
paginate: true
headingDivider: 3
---

# Title Page
<!-- _paginate: skip -->

Version: {{ process.env["TAG"] }}

## Another Page

### And Another

#### This does not make a new page

---

But three lines does

## Basics

This is a paragraph

This is *italics* and **bold**

- This is
- a list

1. This is
2. a numbered
3. list

> And this is a
> blockquote!

<!-- This is a comment, it won't appear! -->

<!-- Don't edit these lines! -->
{{ `<script src="script.js?v=${process.env["TAG"]}"></script>` }}
{{ `<style>@import url("style.css?v=${process.env["TAG"]}");</style>` }}