# helloa9
hello arm9

https://help.github.com/articles/markdown-basics/

Paragraphs

On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.

On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.


# The largest heading (an h1 tag)
## The second largest heading (an h2 tag)
…
###### The 6th largest heading (an h6 tag)

Blockquotes

In the words of Abraham Lincoln:
> Pardon my french
>
> rogers

Styling Text

*This text will be italic*
**This text will be bold**

**Everyone _must_ attend the meeting at 5 o'clock today.**

Lists

Unordered lists by 
* item
* item
* item

Unordered lists by 
- item
- item
- item

Ordered lists by num

1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
  * This is indented four spaces, because it's two spaces further than the item above.
  * You might want to consider making a new list.
3. Item 3


Code formatting

Inline format

Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

Mutliple lines

```
x = 0
x = 2 + 2
what is x
```

Links

[Visit GitHub!](https://www.github.com)


https://help.github.com/articles/github-flavored-markdown/

Underscores won't be italics

wow_great_stuff

do_this_and_that_and_blah blah

URL autolinking

http://example.com


Strkethrough

~~strkie this thru~~ does it work?


Fenced code blocks
```
function test() {
  console.log("notice the blank line before this function?");
}
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

``` js
function test() {
  console.log("notice the blank line before this function?");
}
```

Tables

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |


| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |



https://help.github.com/articles/writing-on-github/

Newlines

Roses are red
Violets are blue


Tasks lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

- [ ] a bigger project
  - [ ] first subtask #1234
  - [ ] follow up subtask #4321
  - [ ] final subtask cc @mention
- [ ] a separate task


References

* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26



