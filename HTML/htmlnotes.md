html:

1.what is html ?
	-> It stands for "Hypertext markup language".
	-> It is used for creating the structure of webpage.
	-> The Structure we want to create for that we have many tags in html.

2. What is hypertext?
	Any text that contains link of any other webpage is called as hypertext.

3. Why it is called markup language?
	Because by using html we are not writing any logics only we are creating structure.

4. What is Tags?
	->Tag is pre-defined words enclosed with angular braces.
	->In html, we have two types of tags:
			1.paired Tags
			2.unpaired/ self closing Tags
Paired Tags:
	Any tag that having both opening tag and closing tag is called as Paired tag.
	E.g:
		<h1>Welcome to html session </h1>
	syntax:
		<tagname> </tagname>
Unpaired tags:
	Any tag that have only the opening tag, there is no closing tag is called as Unpaired tag.
	Syntax:
		<tagname>
	E.g:
		<br>,<hr>,<img>,<meta>,<iframe>

Structure of Html code:
<!DOCTYPE html>
<html lang="en">
<head>
        <title></title>
</head>
<body>

    </body>
</html>

<!DOCTYPE html>
It is used to tell the browser which version of html we are using.
Currently we are using html version 5.

<html></html>
It is root tag of html structure.
All the content should be inside this root tag.

<head></head>
It is used to provide the meta information

<title></title>
it show the information in browser.

<body></body>
the content we want to display in the browser, everything should be written inside this tag.

heading tags:
------------
	In html, for providing headlines (heading/subheading) use heading tags.
	There are 6 heading tags in html.
	<h1></h1> to <h6></h6>
	heading tags are paired tags.
	heading tags are block level elements.

	eg: <body>
			<h1>This is Heading 1</h1>
			<h2>This is Heading 2</h2>
			<h3>This is Heading 3</h3>
			<h4>This is Heading 4</h4>
			<h5>This is Heading 5</h5>
			<h6>This is Heading 6</h6>

Notes:
------
	<h1></h1> tag is the biggest and <h6></h6> is the smalllest.
	the default size of<h1></h1> tag is 32 px.

paragraph tag:
--------------
		In html, if we want to wrie any text content that should be written by using paragraph tag.
		paragraph tag is denoted by <p></p>
		this is paired tag
		it is block level elements
		default size of <p></p> tag is px.

Formating tags:
---------------
		* It is used to change the appearance or format of the text content.

		1.<b></b>
			*It is used to make the content bold.
		2.<strong></strong>
			* It is also used to make the content bold but this tag having **higher priority** compare to <b> tag.
		3.<i></i>
			* It is used to make the content italic.
		4.<em></em>
			This tag is used to make the content italic same as <i></i>.
		5.<u></u>
			This tah is used to provide underline for the text.
		6.<ins></ins>
			It is also used to provide underline for the text.

		7.<mark></mark>
			It is used to provide highlight for the text.
		8.<sup></sup>
			It is used to write any content to the power.

		9.<sub></sub>
			It is used to write the content in the base.
		10.<q></q>
			It is used to provide double quotes around the text.
		11.<pre></pre>
				It is pre formatting tag, inside this tag how we will write the content it will display as it is.
		12.<del></del>
				It is used to give strike through the text
---------------------------------------------------------------------------------------------------------
**<br>
-------
	-> This tag is used to break the line.
	-> It helps to move the content in the next line.
	-> It is unpaired tag

**<hr>
-------
	-> It is used to provide horizontal line.
	-> It is unpaired tag.

**Element:-
---------
1. what is Element ?
		Element is the combination of the tags and the content inside the tags.
	
2. How many types of Element ?
	We have 3 types of Element:
		1. Block level Element
		2. Inline level Element
		3. inline Block Element


**Block level Element:-
---------------------
		-> These Elements will be taking full width of its parent and all are them display in next line.
		-> We can provide **height and width** for these element.
		Eg:
			Headings tag,<p></p>,<div></div>

**Inline level Element:-
-----------------------
		-> These elements will be displaying in same line.
		-> We cannot provide height and width for these.
		-> it occupy only the content area.
		Eg:
			<b></b>,<i></i>,<u></u>,<span></span>


**Inline block level Element:-
----------------------------
		-> It is combination of inline and block level element.
		-> These elements will display in same line but we can't provide height and width.
		Eg:
			<button></button>, <input></input>, <img>.

**Marquee tag:-
--------------
		-> It is used to make any content scrollable on the web page.
		-> By default content will scoll from left to right side.

	**attributes of marquee tag:-
	---------------------------
		1. scrollamount:-
				-> It is used to determine the speed of the scrolling content.
				-> By default values is '6'.

		2. direction:-
				-> It is used to determine the direction of the scrolling content.
				-> value:=>'left','right','up','down'.

		3. Behaviour:-
				-> It is used to determine how the scrolling content will behave.
				-> value => 'scroll','slide','alternate'.

		4. Loop:-
				->It determine how many times the content should scroll.
				
		5. Height, Width:-
				-> It used to resize the marque tag area.


List:-
-------
	-> List is used to group the related elements together.
	->In html, we have three types of list.
		1.Ordered list.
		2.Unordered list.
		3.Description list.

Ordered list:-
---------------
		-> Ordered list is used to group and arrange the elements in particular order.
		-> For creating this we need <ol></ol> tag.
		-> Inside <ol></ol> tag for writing the items we need <li></li> tag.
		-> These tags are block level elements.

Attributes in <ol></ol>:-
-------------------------
	1. type:-
		-> This attribute is used to change the list-style.
		-> values are =>1,a,A,i,I
		-> By default it takes number(1).

	2. start:-
		-> This is used to specify the starting value of the list-style.

	3. reversed:-
		-> It is used to display the list style in reversed order.
		eg:
			<ol type="1" start="50" reversed>             otp:-
			<li>java</li>                                       50.java
			<li>python</li>                                     49.python
			<li>js</li>                                         48.js
			</ol>

Unordered list:-
------------------
		-> Unordered list is created by using <ul></ul> tag.
		-> Here, we are grouping the elements together, but they are not arranged in specific order.
		-> Inside <ul></ul> tag for writing the items we need <li></li> tag.
		-> By default it display the list style as disc or bullet point.
		-> Here, we can only provide type attribute.
		-> we can give 'disc', 'square', 'circle', 'none' as value of type attribute.

		eg:-
			<ul type="circle">
				<li>sql</li>
				<li>webtech</li>
				<li>ad.java</li>
			</ul>

Description list:-
-------------------
		-> For creating the description list we need <dl></dl> tag.
		-> Inside that we have to use <dt></dt> and <dd></dd> tag.
		-> <dt></dt> tag is used to provide the description term.
		-> <dd></dd> tag is used to provide description definition for that term.
		eg:-
			<dl>                                                 otp:-
				<dt>html</dt>                                          html
				<dd>Hypertext markup languge</dd>							Hypertext markup language
			</dl>


<audio></audio> tag:-
----------------------
		-> this tag is used to add an audio in webapage.

Attribute:-
-----------
	scr:-
		It is used to provide the path of audio.

	control:-
		If we give this attribute the only audio will be visible in webpage and we also can control audio.
	
	auto plays:
		for this attribute music will start automatically whenever our page will be loading.

	mute:
		it is used to mute the audio.

	loop:
		it is used to play audio continously.


<video></video>
----------------
		This tag is used to display the video in webpage.

	Attributes:
	-----------
		src,contol,loop,autoplay,muted these attributes are same like audio tag.

	poster:
		-> This attribute is used to provide image/ thumbnail for the video.
		-> In this attribute we have to probide tha path of the image.

	heigth, width:
			It used for resizing the video.


<iframe></iframe>:
-------------------
		-> <iframe></iframe> tag is used to add different webpage in our current webpage.

		-> It is inline block level element.

	Attributes:-
	------------
		1.src:
			In this attribute we have to provide the path of this webpage we want to add in our webpage.

		2.frameborder:
			-> It is used to provide outline or border around the content.
			-> By default value is 0. 

		3.heigth, width:
			-> It is used to provide the size of content.


Anchor tag:
-----------
	<a></a>
		-> Anchor tag is denoted by <a></a>
		-> It is used to create hyperlink.
		-> It is a incline level element.

	Attributes:-
		1.href:
			-> It is used to take the path where we want to navigate.
			-> It helps to navigate or redirect from one page to another page or in the same page one section to another section.

		2.target:
			-> By default if we click any hyperlink it will be open in same tab. if we want to open in the different tab use need target attribute.
			-> target="_blank" is used to open in the new tab.

		3.title:
			-> Whenever we hover(keeping mouse cursor on the element) the 'title' attribute helps to display some message.
			eg:
				<a href="https:\\instagram.com/" target="-blank" title ="insta">go to my profile</a>


how to navigate in the same page:
	step1:
		In which tag we want to na=vigate there we have to give 'id' attribute.
	step2:
		Which value we are giving for the id attribute then some value we have to provide in the 'href' attribute with '#' symbol.

attribute for <td></td><th></th>
-----------------------------------

	1.rowspan:
		-> This attribute is used to combine to more than two rows.

	2.colspan:
		-> It is used to combine two or more than two columns.

note:
------
	we have something extra tags in table like <thead></thead>, <tbody></tbody>, <tfoot></tfoot>



<div></div> tag
---------------
	-> It is one block level eleement used to make a division.
	-> Inside this tag we can write inline block and inline-block level elements.
	-> We can provide height and width.

<span></span> tag
-------------------
	-> It is one inline level element used to selectt some part of block level element.
	-> We can't provide height and width.
