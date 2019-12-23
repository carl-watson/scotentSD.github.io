---
layout: page
title: Help
permalink: /help/
---

## Blog
The Blog page has code to display any posts in the **posts** folder. The default layout is in the **Layout** folder: post.html

![alt text](https://github.com/scotentSD/scotentSD.github.io/blob/master/images/blogpost-code.PNG "lines of code to display each blogpost")

## Creating a Blog post
Create a markup file in the posts folder and name it in the format :

**yyyy-mm-dd-title.md**

This date will be used to create the line at the bottom of your post:

Written on dd mmm, yyyy

At the top of your file, add the following lines:  

```
---
layout: post
title: Welcome to this new blog
---
```

This will give the correct layout for your post, and use that title for the blog post itself and for it to be listed with the other blog post on the main blog page.

If an excerpt marker is defined in the `\_config.yml` file then you can mark a section of the post as the excerpt. 
Everything above the  `<!—more—> `code will be the summary we can see on the main blog page. Anything below can only be seen if you click on the blog post link.

```
<!--more--> 
```

Add this line to the `_config.yml` to enable the excerpt marker:

``` 
excerpt_separator: "<!--more-->" 
```

## Structure
- Home
- About
- Blog
- Help

**From the homepage:**

**Worstreams**
- SEP
- International Networks

**Learning, resources and techniques**
- Practice and Techniques
- Posters
- Resources
- Feedback
- Personas

<br><br>
<div>Last updated: {{site.time | date_to_string}}</div>


