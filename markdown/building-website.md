# Building a Simple Website

When it comes to a software engineer's portfolio, the first thing that comes to my mind is "what does their website contain?" To me, this seems to be the first place to display our work (as a software engineer). We want to show others of what we are capable of.

For me, this is just a little tutorial to build a simple website that will help myself remember certain techniques, but I hope that this will help you also.

## 1. Template

When it comes to writing the index for the HTML you are going to have the basic layout as everyone else writing HTML (I am assuming), so the first thing we are going to do is download a HTML boilerplate extension on VSCode and type `!`. This will build this basic layout:

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Title</title>
</head>
<body>

</body>
</html>
```

Where we see `<title>` we can type what we want the tab to display. I am going to name this HTML file `index.html` as this will be the landing page for my site. A little background for the naming of `index.html` is that the server will first look for this file and then it'll display it. Most servers are set up to look for the `index.html` file to display the content and then the user and can explore from there. *Note: some servers can be set up to have a different default than `index.html`, but it's a good choice to always use `index.html`*

## 2. The Navbar

This is going to be one of the most important items on a webpage. The user is going to go to this to navigate the page and find other items they want to see. For `<nav>` this is the usual layout:

```HTML
<header>
    <div class="navbar">
        <nav>
            <h1>Michael's Headspace</h1>
            <ul>
                <li>Home</li>
                <li>Notes</li>
                <li>Blog</li>
            </ul>
        </nav>
    </div>
</header>
```

We are placing the `<nav>` inside of the `<header>`. Placing the `<nav>` tags here tells the browser that this is for navigation links. Now we will place some `<h1>` tags to make our "logo" and then we are going to wrap our navigation in a unordered list and a ordered list inside of it.