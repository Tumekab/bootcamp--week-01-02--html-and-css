# CSS: Cascading Style Sheets

Note:
For styling the html. Style sheets, we'll cover the cascade more as we go through
---

### We do this by

- Selecting the HTML element we want to style
- In a variety of ways |
- And add defined properties |
- Give these properties a value

Note:
About 438 properties & counting
Maintained list here: [https://meiert.com/en/indices/css-properties/](https://meiert.com/en/indices/css-properties/)

---

@snap[north-west span-40]
#### Let's take a look

A standalone piece of content (always has header)
@snapend

@snap[east span-70]
```css
body {
	background-color: red;
}

selector {
	property: value;
}
```
@snapend

Note:
Every character makes a difference

---

#### Selectors

- elements
- classes
- ids

Note:
Explain all - we tend to use classes. Only one id per page

---

#### Where CSS?

- inline
- in a `<style>` element
- in a separate file

Note:
Show all. We'll be putting it in a file. &lt;link rel="stylesheet" href="css/main.css">

---

## Whitespace matters in values

Note:
But no where else

---

@snap[north-west span-40]
#### Comments

@snapend

@snap[east span-70]
```css
/* This is a comment */
```
@snapend

---
