# Maximum Achievers Educational Services

## Where to See the Website

The website has two addresses:
- [http://maximumachievers.in](http://maximumachievers.in)
- [http://maximumachievers.github.io](http://maximumachievers.github.io)


## How to Update the Website

There are a couple of places where the contents of the website can be edited. Generally, this requires no programming
knowledge to do (depending on how extensive your changes are).

### Title, Slogan, Description, Slide Show, and Colors
[Edit the _config.yml file](http://prose.io/#maximumachievers/maximumachievers.github.io/tree/master/_config.yml) to 
change the title, slogan, or description on the website. This is also where you can change the pictures shown in the
slide show on the home page. If you're feeling more industrious (and understand hex codes for colors) you can also 
update the colors used throughout the website.

### Posts
To add a new featured "about" section to the website (or to edit an existing one), 
[open up the _posts folder](http://prose.io/#maximumachievers/maximumachievers.github.io/tree/master/_posts)
and create a new file, or edit an existing one. The file names must take the form of "#-01-01-Title". The number must
be unique, and controls the ordering of the posts -- that is, each must have a unique number, such as 1, 2, 3, and so
on. Each post must contain roughly the following:

```
---
layout: default
img: /img/photos/BTH 2 communication pics 017.JPG
description: Living life to the fullest involves the ability to communicate effectively in different environments.
---

Living life to the fullest involves the ability to communicate effectively in different environments. MAES offers 
several different types of communication training for companies, schools, organizations and individuals. We specialize
in training for public speaking.

```

Let's take a moment to explain what the various parts of this file do:
- "layout:default" specifies that the normal layout should be used. This generally doesn't need to be trifled with.
- "img: ..." specifies the path to an image to associate with the post. These should be square, 400x400 images.
- "description: ..." specifies the text to display on the home page under the picture.
- After the second "---", you can specify any text you want, using the special "markdown" format (prose.io helps you with this). All this will be displayed on the details page for the post.


## How to Add Photos

To add photos, [open the img folder](http://prose.io/#maximumachievers/maximumachievers.github.io/tree/master/img) and
click the "Add" button. Upload an image either in to the "img" folder directly, or in to one of the sub folders (keeping
these folders organized will help you in the future).

Before uploading an image, you should resize it to the size it
will be on the website. Most pictures out of cameras are very large, and will slow down the website considerably.


## How to Change the Domain Name

Changing the domain name requires changes in two places:
- [Edit the "CNAME" file](http://prose.io/#maximumachievers/maximumachievers.github.io/tree/master/CNAME) to the new domain name.
- Through the website where the domain was purchased (most likely GoDaddy), create a CNAME record pointing at "maximumachievers.github.io". 
