
# MetaTag [..tag]

## what is it?

Metatags **adds an additional dimension to tagging** while also tightening up the tag format.

It is well-suited for adding quite complex metadata in a fast, free-flow sort of way.

### Value proposition
- saving seconds adding tag information
- adding additional information using "tag structure" in a naturally flowing way
- tightening multiple tags up format-wise, single-string format
- adding tags anywhere text goes (e.g. in file titles or in-text)

### basically just tags and tagged tags
Metatags includes ordinary tagging functionality:

    . (dot) is the normal tag operator

and also allows for tagging tags:

    .. (dot dot) is the metatag operator

(Only one tag can be tagged per dimension. Seems to work nicely in practice.)

## example please


### basic syntax
A normal collection of tags looks like so

**..food.podcast.spaghetti_related**

to signify the hash tags

    #food
    #podcast
    #spaghetti_related

(Note the `..` signifying the start of a metatag)

### full syntax

A metatag utilizing the dimensional aspect (tags tagging tags) looks like so

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

To describe a complex self-contained string and/or escape `.` (dot) interpretation use sharp parentheses. Examples include `[url.com]`,`[v0.1.2]`,`[hmm...]`. Used below to include a full URL:

**..youtube_video..math.calculus_1.lecture_series.url..[https://youtu.be/rR8imSHCuFk]**

signifying in hash-tag notation

    #youtube_video
    #youtube_video/math
    #youtube_video/calculus_1
    #youtube_video/lecture_series
    #youtube_video/url https://youtu.be/rR8imSHCuFk





