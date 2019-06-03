---
layout: step
number: 3
part: 0
title: Congratulations
permalink: step3/
---

Wow!  You now know the basic foundations of HTML & JavaScript. 

![I know kung-fu](../assets/neo-kungfu.gif){:class="img-responsive"}

We don't yet have the code to persist our todo items into a database.  That means that when we close down our page our items are gone and we have to start again.  

If you experiment with Glitch you'll find that there is a starter template project for a database backed project.  Just go to the main page of Glitch and select `New Project` and then `Sqlite`.

If you're ahead of the curve why not make a nice background for your page.

<h3><i class="fa fa-hand-pointer-o " aria-hidden="true"></i> CSS Rules for our ToDo App</h3>

Add this code at the top of your `style.css` file:

```CSS
.todobackground {
  background: url("https://cdn.glitch.com/e517ff0c-694a-4b4a-80ab-58fb8df850f7%2Fanete-lusina-609852-unsplash.jpg") no-repeat center center fixed; 
-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover;
background-size: cover;
}
```

Edit the `body` tag of your html file so it looks like this:

```html
<body class="todobackground">
```

We are using a photo from Unsplash so make sure you go ahead and credit that artist for their photo by adding the following html near the bottom of the `index.html` file like this:

```html
    <!-- https://unsplash.com/photos/2JknzBYDu6k -->
    <small>Image credit: <a href="https://unsplash.com/@anete_lusina">Anete Lusina on Unsplash</a></small> 
```

If you want to get your own photo or one from Unsplash, and use it in your page - feel free to do so!  Just drop the photo into the assets folder.  Once its uploaded, click on it to get the URL to it, which you can then paste into the
URL argument of your `background` attribute in the `.todobackground` CSS code above.