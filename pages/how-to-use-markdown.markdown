---
layout: page
title: "How to use markdown - a Beginner's Guide"
published: true
---


that stuff up there is called the front matter. it dictates how this file is rendered to the static website.

the date is when the post was published.


you can copy this, into your new file. just make sure the date is correct, and the add the `category: "2018 Rover Ruckus"` to it somewhere.


# Headers

you can make things headers using the `#` character. examples bellow.
```
# header 1
## header 2
### header 3
#### header 4
##### header 5
###### header 6
```

these headers get smaller the larger number they have.

you can also mark headers by putting `====` under a line. example bellow.
```
A header 1
==========
```

# Styling Text

you can bold things like this: `**this is bold**`

bold things can be put **anywhere** in a sentence.

italics are equally as simple: `*italics.*`

we *can combine* ***italics and bold*** if we want.

strike-through stuff with double `~~like this~~`.

like bolding things, ~~strike-through can also be~~ in the middle of sentences

## Links

you build a link like this: `[what the link displays](http://the.link.goes.here)`
example bellow links to google.

[this goes to google!](https://google.com)


## photos and images

you can embed a photo by using this template: `!()[link/to/the/image]`

as images go in the `assets/img/` folder, an example would be like this:

`![](/assets/img/knight-medium.png)`

![](/assets/img/knight-medium.png)

you can change the height and width of the image like so:

`![](/assets/img/shield.png){: height="300px"}`

![](/assets/img/shield.png){: height="300px"}

you can set both `height` and `width`, or one or the other.

**the above also works with videos, although those should go on youtube. see bellow.**

## Videos  


you can embed a youtube video with the following code:
{%raw%}
`{%- include widgets/youtube-player.html video='the video's ID' -%}`
{%endraw%}
	{%- include widgets/youtube-player.html video='rR4gR4l2XA8' -%}
