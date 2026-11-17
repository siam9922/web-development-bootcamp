# Project: Gotham City Headquarters

**Difficulty:** Beginner  
**Technologies:** HTML5 and CSS3  
**Project Type:** Multi-page static website  
**Goal:** Review HTML fundamentals and practise basic CSS independently.

---

## 1. Project Overview

You have been hired to build a fictional website for **Gotham City Headquarters**.

The website will display information about Gotham City's heroes, criminal activity, and active missions.

Your website will contain three pages:

1. **Homepage** — Introduces Gotham City Headquarters.
2. **Characters Page** — Displays hero profiles with images and descriptions.
3. **Missions Page** — Displays missions, objectives, and progress.

You must build everything using HTML and CSS.

No JavaScript, frameworks, Flexbox, or CSS Grid are required.

## 2. Project Folder Structure

Create the following folders and files in VS Code.

```text
Gotham-Headquarters/
│
├── index.html
│
├── pages/
│   ├── characters.html
│   └── missions.html
│
├── assets/
│   └── images/
│       ├── gotham.jpg
│       ├── batman.jpg
│       ├── nightwing.jpg
│       └── robin.jpg
│
└── css/
    └── styles.css
```

Download four suitable images and save them using the filenames shown.

You are responsible for connecting all files using correct relative paths.

---

## 3. Part One — Homepage

**File:** `index.html`

Your homepage introduces visitors to Gotham City Headquarters.

### HTML Requirements

- Create the complete HTML boilerplate.
- Set the document language to English.
- Include UTF-8 and viewport meta tags.
- Set the browser tab title to "Gotham City Headquarters".
- Create an `<h1>` containing the website name.
- Create an `<h2>` titled "Welcome to Gotham".
- Write two paragraphs introducing the organization.
- Display the `gotham.jpg` image with suitable alternative text.
- Add an unordered list containing three reasons Gotham needs its heroes.
- Separate two sections using `<hr>`.
- Include a line break using `<br>` where appropriate.
- Include navigation links to the Characters and Missions pages.
- Create one external link to a relevant website.
- Add a `<footer>` containing a fictional copyright notice.

### CSS Requirements

- Give the main heading a colour.
- Change the background colour of the webpage.
- Centre the main heading.
- Change the paragraph font size.
- Resize the Gotham City image.

**Skills reviewed:** Boilerplate, headings, paragraphs, void elements, lists, images, anchors, external CSS, and file paths.

---

## 4. Part Two — Character Profiles

**File:** `pages/characters.html`

Create a page displaying information about three heroes:

- Batman
- Nightwing
- Robin

### HTML Requirements

For each character, include:

- An `<h2>` containing their name.
- An image of the character.
- A paragraph describing the character.
- An unordered list containing their abilities, equipment, and location.

Additional requirements:

- Add a main `<h1>` called "Gotham Heroes".
- Separate each character profile using `<hr>`.
- Give all three profiles the same `class` attribute.
- Give Batman's profile a unique `id` attribute.
- Make at least one character image clickable using an anchor element.
- Include navigation links back to the homepage and to Missions.

### CSS Requirements

Practise these selectors:

**Element Selector**
- Change the colour of every `<h2>` element.

**Class Selector**
- Use a shared class to style all three character profiles.

**ID Selector**
- Give Batman's profile a different background colour.

**Universal Selector**
- Apply a common font family to all elements.

**Skills reviewed:** Classes, IDs, CSS selectors, links, image paths, nesting, and styling.

---

## 5. Part Three — Mission Board

**File:** `pages/missions.html`

Create a mission board showing the current operations of Gotham City Headquarters.

### Mission Information

Create three fictional missions:

**Mission 1: Arkham Investigation**

Batman is investigating suspicious activity at Arkham Asylum.

**Mission 2: Gotham Patrol**

Nightwing and Robin are patrolling Gotham City.

**Mission 3: Criminal Investigation**

The team is gathering evidence against organized criminals.

### HTML Requirements

- Create an `<h1>` called "Active Missions".
- Give each mission an `<h2>` heading.
- Write a short description for every mission.
- Use an ordered list for the steps of one mission.
- Add a nested unordered list containing additional equipment needed for one step.
- Add a paragraph with `draggable="true"`.
- Include a `<label>` and `<progress>` element showing fictional mission progress.
- Separate the missions using `<hr>`.
- Add links to the other two pages.

### CSS Requirements

**Attribute Selector**
- Target only the paragraph with `draggable="true"` and change its text colour.

**Inline CSS**
- Apply one CSS style directly to an HTML element.

**Internal CSS**
- Use a `<style>` element inside `<head>` to style one part of the mission page.

**External CSS**
- Continue using your existing `styles.css` file for shared website styling.

**Skills reviewed:** Ordered lists, nested lists, attributes, inline CSS, internal CSS, external CSS, and attribute selectors.

The mission progress is static. You don't need JavaScript to update it.

---

## 6. CSS Styling Requirements

Your website should demonstrate the following CSS properties:

| Property | What you should practise |
|---|---|
| `color` | Change text colours |
| `background-color` | Change backgrounds |
| `font-size` | Change text size |
| `font-weight` | Make text bold |
| `text-align` | Align headings and text |
| `width` | Adjust image width |
| `height` | Adjust image height |

You should also demonstrate all five CSS selector types:

1. Element selector
2. Class selector
3. ID selector
4. Attribute selector
5. Universal selector

Use a consistent colour theme across your website.

**You do not need to make the website visually perfect.** Simple styling is enough.

---

## 7. Final Project Checklist

### HTML

- [ ] All three pages contain valid HTML boilerplate.
- [ ] Headings and paragraphs are organized correctly.
- [ ] Ordered and unordered lists work.
- [ ] Nested lists are structured correctly.
- [ ] Images display with meaningful `alt` text.
- [ ] Internal and external links work.
- [ ] Relative paths work across different folders.
- [ ] HTML attributes are used correctly.
- [ ] HTML comments are included where helpful.
- [ ] Footer and progress elements are included.

### CSS

- [ ] External CSS is connected to all three pages.
- [ ] Inline CSS is demonstrated.
- [ ] Internal CSS is demonstrated.
- [ ] All five selector types are used.
- [ ] Text and background colours are applied.
- [ ] Font sizes and weights are adjusted.
- [ ] Image sizes are changed.

### Testing

- [ ] Open `index.html` in your browser.
- [ ] Navigate between all three pages.
- [ ] Verify that every image loads.
- [ ] Check that your CSS changes appear.
- [ ] Make sure you can return to the homepage from every page.

---

## 8. Project Rules

1. **Write the HTML yourself.** Refer to your previous projects and notes when necessary.
2. **Look up syntax when you forget it.** You are practising development, not memorization.
3. **Build the HTML structure before styling it.**
4. **Test each page in your browser** before moving to the next.
5. **Don't add JavaScript or advanced CSS.** Stay within what you've already studied.
6. **Keep the website functional and simple.** Completing the requirements matters more than making it beautiful.

## 9. Completion Goal

By the end of the project, you should be able to:

- Create a complete HTML document.
- Organize content using HTML elements.
- Navigate through folders with relative paths.
- Link different HTML pages together.
- Connect an external CSS stylesheet.
- Understand how different CSS selectors target HTML elements.
- Apply basic styling without relying entirely on tutorials.

**Project complete when:** All three pages work, navigation is functional, images display, and the required CSS styles are applied.

You don't have to remember every line of code. You should understand what the code accomplishes and how to find the syntax when needed.