# HTMLPlaceholder
Program to add text in a boilerplate HTML document.
The Javascript program adds certain text or code in between an already existing HTML file via placeholders.
Just enter the HTML Boiler plate, with placeholders marked as <!--Placeholder#1--> and it will generate input fields for those placeholders.
This is suited for writing the same HTML document with just different text, eg: in a blog with over 100 articles or so.
Eg:

HTML Boilerplate (initial input):
<html>
<head>
.....
<!--Placeholder#head-->
</head>
<body>
....
....
<p class="blog-article">
<!--Placeholder#paragraph-->
</p>
...
...
</body>
</html>

The program will analyse and ask the following after initial input:

State what do you want to add at these placeholders:
head: [insert input here]
paragraph: [insert input here]

Final output:

<html>
<head>
.....
<!--Placeholder#head-->
[your input here]
</head>
<body>
....
....
<p class="blog-article">
<!--Placeholder#paragraph-->
[your input here]
</p>
...
...
</body>
</html>

I am new to GitHub so please excuse my newbie way of writing and explaining this ReadMe.md file. Suggestions would be appreciated.
