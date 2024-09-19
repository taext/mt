
# MetaTag [..tag]

## what is it?

The meta-tag **adds an additional dimension to tagging** while also tightening up the format.

It includes ordinary tagging functionality

    . (dot) is the normal tag operator

and also allows for tagging other tags

    .. (dot dot) is the meta-tag operator

## example please


### basic syntax
A normal collection of tags looks like so

**..food.podcast.spaghetti_related**

to signify the hash tags

    #food
    #podcast
    #spaghetti_related

(Note the `..` signifying the start of a meta-tag)

### full syntax

A meta-tag utilizing the dimensional aspect (tags tagging tags) looks like so

**..text..freewriting.danish.short_form.funny..not_haha.dark.british**

which corresponds to these hash tags when expanded

    #text
    #text/freewriting
    #text/dansk
    #text/short_form
    #text/funny/not_haha
    #text/funny/dark
    #text/funny/british

### another example

**..mp3..metal.90s.mood..fist_date.last_date**

corresponds with these hash tags

    #mp3
    #mp3/metal
    #mp3/90s
    #mp3/mood/fist_date
    #mp3/mood/last_date

## complex tags using `[]`

To describe a complex self-contained string and/or escape `.` (dot) interpretation, use sharp parantheses `[url.com]` like so

**..youtube_video..math.calculus_1.lecture_series.url..[https://youtu.be/rR8imSHCuFk]**







