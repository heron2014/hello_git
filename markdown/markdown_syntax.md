##How to make italic and bold

To make a phrase _italic_ in Markdown, you can surround words with an underscore (_ )

Similarly, to make phrases **bold** in Markdown, you can surround words with two asterisks ( ** )

Mixing both together, italic and bold:

**_This is awesome_**


##How to make headers

For example, for a header one, you'd use one hash mark (# Header One),
while for a header three, you'd use three (### Header Three).

#Header one
##Header two
###Header three
####Header four
#####Header five
######Header six

##How to make links to other web sites

The first link style is called an **inline link**. To create an inline link, you wrap the link text in brackets ( [ ] ),
and then you wrap the link in parenthesis ( ( ) )

Examples:
[Visit GitHub!](www.github.com)

[You're **really, really** going to want to see this.]( www.dailykitten.com)

####The Latest News from [the BBC](www.bbc.com/news)

The other link type is called a **reference link**. As the name implies, the link is actually a reference
to another place in the document.

**Example:**

Do you want to [see something fun][a fun place]?

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com

##How to create images
The difference is that an image is prefaced with an exclamation point ( ! ), followed by the same two brackets,
and a pair of parentheses containing the image URL. Within the image brackets, you can place some "alt text," which is
a phrase or sentence that describes the image for the visually impaired.

Images also have two styles, just like links. To create an inline image, you'll use the same syntax as an inline link.

**Examples:**

![A representation of Octdrey Catburn](http://octodex.github.com/images/octdrey-catburn.jpg)

For a reference image, you'll follow the same pattern as a reference link. You'll precede the Markdown with an 
exclamation point, then provide two brackets for the alt text, and then two more for the image tag. At the bottom of 
your Markdown page, you'll define an image for the tag.

[The first father]![First Father](http://octodex.github.com/images/founding-father.jpg)

##Markdown's blockquote syntax

> In a few moments he was barefoot, his stockings folded in his pockets and his
  canvas shoes dangling by their knotted laces over his shoulders and, picking a
  pointed salt-eaten stick out of the jetsam among the rocks, he clambered down
  the slope of the breakwater
  

> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.

##How to create list in Markdown

To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ). 
Each list item also gets its own line.

**Example:**

* Flour
* Cheese
* Tomatoes

An ordered list is prefaced with numbers, instead of asterisks.

**Example:**

1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour

* Calculus
 * A professor
 * Has no hair
 * Often wears green
* Castafiore
 * An opera singer
 * Has white hair
 * Is possibly mentally unwell
 
 1. Cut the cheese
 
  Make sure that the cheese is cut into little triangles.
 
 2. Slice the tomatoes
  
  Be careful when holding the knife.
 
  For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.
  
##How to format paragraph

There are two ways : hard break (each sentence in new line) and soft break (two spaces after each line).

**Example:**

1. Crack three eggs over a bowl.

 Now, you're going to want to crack the eggs in such a  
 way that you don't make a mess.  
 If you _do_ make a mess, use a towel to clean it up!  

2. Pour a gallon of milk into the bowl.

 Basically, take the same guidance as above: don't be messy,  
 but if you are, clean it up!  
   
   
