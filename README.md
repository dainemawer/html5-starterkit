# 🔥 HTML 5 StarterKit with OpenGraph, Schema.org and Aria
---

[![Follow Daine Mawer On Twitter](https://flat.badgen.net/twitter/follow/dainemawer)](https://twitter.com/dainemawer)
[![Issues on Github](https://flat.badgen.net/github/issues/dainemawer/schema-html-document)](https://github.com/dainemawer/schema-html-document/issues)
![Last Commits](https://flat.badgen.net/github/last-commit/dainemawer/schema-html-document)


I can't count on my fingers the amount of times I've trawled the web looking
for good Schema.org snippets that actually makes sense. Im hoping this template
will save time for everyone out there looking to get a solid start to a new project.

### 🤷‍♂️ Unopinionated
---
`Santize.css` is used as an alternative to `Normalize.css`. I wanted to be as unopinionated as possible, so I've
left most of the decisions about scripts and css files, up to you. I've made provisions for simple site layout, as well as
if you were planning on using this within a React context.

### 🗜 Browser Outdated and NoScript Notices
---
I've added in conditional placeholders for NOJS and outdated browsers. Just for consistency sake.

### 📰 HTML 5 Ready
---
HTML 5 is the latest in the spec, so Im using it. The markup has been validated against the W3C.
The boilerplate uses 100% semantic tags, follows a heading order and leaves out unnecessary attributes on meta
tags thats are no longer required.

### 📇 Heavily Commented
---
I've made a good point about commenting as much as I can, in order to mkae motivations clear.
You can find the slimmed down version in the `dist` folder.

### 🔍 Ready for Sharing
---
Depending on your use case, there may be a plugin that does all this for you, but incase you're handling
a static site, I've included important OpenGraph Meta tags that will make your site look pretty good across
social media platforms.

### 📑 Structured Data
---
I've included and validated `schema.org` attributes so that markup is more descriptive. Please note that this is not a
one size fits all solution, depending on the type of website, this will more than likely need to change. If anything, you can use the attributes created for general site areas like `<header>`, `<footer>`, `<main>`, `<nav>`, `<aside>`.

### 👓 Aria Roles
---
I've added the releveant aria roles to markup. These attributes are incredibly important to `a11y`.
It should be noted that the `role=""` attribute on HTML 5 semantic elements like `<header>`, `<footer>`, `<main>`, `<nav>`, `<article>`, `<section>` and `<aside>` is not required. In the boilerplate itself I have included them so you can see where they should be placed.
If, for whatever reason, you are not using sematic elements, and instead are using a `<div>`, please ensure that you add the correct `role=""` values.

### 📋 Manifest
---
A site manifest file provides more detail to browser that support Progressive Web Apps. You can customize the `manifest.json` file in the static folder.

### 👫 Humans.txt
---
`humans.txt` is similiar to `robots.txt` however, the `humans.txt` file simply describes the people behind the site. Those who built it, contributed, etc.

### 📸 Site Images
---
I've provided placholder images at the correct sizes.

### License
---
MIT
