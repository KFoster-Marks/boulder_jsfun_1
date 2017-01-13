#HTML Foundations

---

#Draw and label an html element.

---

<br>

#[fit]
```html

<h1 class=“title”>Awesome Title</h1>
```

<br>
- tag
- attribute
- element

---

## Describe the basic structure of an HTML document.

---


<br>

```html
<!DOCTYPE html>
<html>
	<head>
   		<title>Page Title</title>
	</head>
	<body>
   		<p>This is unformatted text that is the only item of content
   		within the body of this simple web page.</p>
	</body>
</html>
```
---

## Name 5 semantic HTML structure elements.


---

```html

<body>
	<nav></nav>
 
  	<header></header>
  
  	<main>
    	 <div></div>
  	</main>
  
  	<footer></footer>
 
</body>

```

---

##Write markup for an 
##image that links to another site.


---
<br>

```html
<a href="http://www.site.com/">
  <img src=“images/pic.png”>
</a>
```
---

## Create an element that allows user input.

---

<br>

```html
<form>
    <label>First name:</label>
    <input type="text" name=“first-name” />
</form>
```
---

#CSS Foundations

---

## Identify the parts of a CSS rule.

---

<br>

```CSS

input {
	width: 20px;
}

- selector
- property
- value
- declaration

```

---

## Explain three ways in which CSS can be applied to HTML.

---

## external css

```html


<head>
  <title>Page Title Here<title>
  <link rel="stylesheet" href="style.css" />
</head>

```

---

## internal css

```html


<!doctype html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Internal CSS StyleSheet</title>
 
    <style> 
      p {
        color: red;
      }
    </style>
 
  </head>

```

---

<br>
## inline css

```html

<p style="color: red">Red text</p>

<div style=“width: 50%”>Red text</div>

```

---

## Describe how cascading works with CSS

---


## 1. Browser default
## 2. External style sheet
## 3. Internal style sheet
## 4. Inline style

---

## Write examples of the 3 kinds of css selectors/identifiers.

---

<br>

```CSS

h1 {
	width: 20px;
}

.error {
	color: red;
}

#nav-button {
	border: 2px solid gray;
}
```

---

## Write an example that groups three selectors with a single rule.

---

<br>

```CSS

h1, p, #secondary-text {
	text-align: center;
}


```

---

<br>

```css

main p {  
	color: black; 
}

footer p { 
	color: white; 
}

```
---


<br>

```CSS

a {
  font-family: Arial, sans-serif;
  font-size: 20px;
}

a:hover {
	color: white;
	background-color: black;
}

```


---

## Google Fonts 

---

<br>

```css
@import 'https://fonts.googleapis.com/css?family=Loved+by+the+King';


h1 {
  font-family: 'Loved by the King', cursive;
  font-size: 3rem;
}

```

---

## The importance of indentation.

---


## Show how to write comments in both HTML and CSS documents.

---

<br>

```CSS

input {
	/* width: 20px; */
}

```
<br>

```html
<div>
	<!—- html comments —->
</div>
```



