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

```c
#include <msp430.h>
#include <energia.h>
#define ABC
struct MyStruct {
  int flag;
};
int main(void) {
  return 1;
}
```

```cpp
#include <msp430.h>
#include <energia.h>
#define ABC
class MyObj {
  int foo() {
  return 1;
  }
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



Also, https://guides.github.com/features/mastering-markdown/

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

And, of course emoji! :sparkles: :camel: :boom:






## Mathematical formulae

Inline math `$E = mc^2$`, another one: `$\dfrac{ \tfrac{1}{2}[1-(\tfrac{1}{2})^n] }{ 1-\tfrac{1}{2} } = s_n$`.

```math
\oint_C x^3\, dx + 4y^2\, dy

2 = \left(
 \frac{\left(3-x\right) \times 2}{3-x}
 \right)

\sum_{m=1}^\infty\sum_{n=1}^\infty\frac{m^2\,n}
 {3^m\left(m\,3^n+n\,3^m\right)}
 
\phi_n(\kappa) =
 \frac{1}{4\pi^2\kappa^2} \int_0^\infty
 \frac{\sin(\kappa R)}{\kappa R}
 \frac{\partial}{\partial R}
 \left[R^2\frac{\partial D_n(R)}{\partial R}\right]\,dR
```

[Mathematical Formulae Syntax](http://meta.wikimedia.org/wiki/Help:Displaying_a_formula)


## Flowcharts

```
graph TD
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```

[Flowchart Syntax](http://knsv.github.io/mermaid/flowchart.html)


## Sequence diagrams

```
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you?
    alt is sick
        Bob->>Alice: Not so good :(
    else is well
        Bob->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        Bob->>Alice: Thanks for asking
    end
```

[Sequence Diagram Syntax](http://knsv.github.io/mermaid/sequenceDiagram.html)


## Gantt diagrams

```
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1, 20d
    section Another
    Task in sec      :2014-01-12, 12d
    anther task      : 24d
```

[Gantt Diagram Syntax](http://knsv.github.io/mermaid/gantt.html)



https://github.com/chjj/marked

https://github.com/tylingsoft/markdown-plus


https://github.com/github/markup

https://github.com/evilstreak/markdown-js

