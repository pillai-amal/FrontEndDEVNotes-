## Types of combinators 
1. Descendent combinator
	This type of combinator will added styling to all of the desendents of particular selector. 
	```css
		footor p {
			color: green;
		}
	```
	This will add  color to all `<p>` under `<footor>` tag.

2. Direct descendent combinator 
	- only to direct decendents 
	```css
	footor > p{
		color: red;
	}
```
	This will add  color ONLY DIRECT Descendents `<p>` under `<footor>` tag.

3. Immediate Relative 
	- only to immediate/adjecent relative 
	```css
	h2 ~ p{
		color: red;
	}
```
	This will add color to only those paragraphs which is immediate next to a `<h2>` tag.
	