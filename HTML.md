HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

### Special Elements 

- hr - can be used to make a horizontal line 
- abbr - To write abbreviations![[Pasted image 20230905214923.png]]
- Address Tag : italics the address ![[Pasted image 20230905215154.png]]

### HTML Entities 
###### Reserved characters in HTML must be replaced with character entities.

![[Pasted image 20230905214658.png]]


## LISTS 

	Ordered List 
	<ol>
		<li><li>
	<ol>

![[Pasted image 20230905220631.png]]

	unordered List
		<ul>
		<li><li>
		<ul

![[Pasted image 20230905220652.png]]

	Description List 
		<dl>
		<dd><dd> //Description Details
		<dt><dt> //Description Term
		<dl>

![[Pasted image 20230905220441.png]]


## LINKS 

Link to another webpage :

	<a href="(link)">Placeholder Text</a> 
	<a> stands for anchor tag 

Link to a section of the page :

	<section id = id_name>blah blah blah </section>
	you can point to this section by creating a <nav></nav>, which is a symentic element of html.
		<a href="#id_name">Placeholder</a> 

Link to download something : 

	<a href="html.png" download >Placeholder</a>

Link which redirects someone to send a mail : 

	<a href="mailto:priyanshu.singhcs11@gmail.com">sdfadad</a>

Link for a phone number : 

	<a href="tel:8145353535">adfa</a>

Link to open up a page in a new tab : 

	<a href="google.com" target="_blank">adfa</a>