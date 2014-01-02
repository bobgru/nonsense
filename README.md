# Playing with Markdown
Bear with me while I get comfortable with this
## Second-level header
### Third-level header

Another Main Heading
====================

Lesser Heading
--------------
* Top level of list
* Still at top level
    + Now down a level
    + One more
* And back up

*Sooner or later* I need to add some _content_. ***Really!***

OK. Now I want to add some code:

    sum = fold (+) 0
    product = fold (*) 1
    and = fold (&&) True
    or = fold (||) False

I'm getting all this from [Markdown](http://en.wikipedia.com/wiki/Markdown).
Enough for now. Let's commit this and see what happens.

### More
Above I inserted some code as a block, but it could have been done inline. For instance, I could have said something about `fold` having wide applicability in implementing functions such as `sum = fold (+) 0` or `product = fold (*) 1`.

> Block quotes are supposed to reflow as the window resizes. To demonstrate this I need a long line of text long line of text long line of text long line of text, etc. See [Markdown reference][Markdown].

There are various ways to create a horizontal rule. *Wikipedia* says they are all equivalent, but it also says the "Markdown spec" is vague and implemented in different ways. Let's try some.

* * *
- - -
*****
-----------
There were four different styles above.
[Markdown]: http://en.wikipedia.com/wiki/Markdown "Markdown Wikipedia entry"

Now I'll test inclusion of an image inline:
![Image of wreath lamp walk](https://github.com/bobgru/nonsense/blob/master/tour15.jpg  "Wreath lamp walk")