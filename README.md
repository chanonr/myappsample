#HEADERS

# This is an <h1> for myApp

## This is an <h2> for myApp

###### This is an <h6>

#EMPHASIS

*Here is some italicized text*
_Here is some more italicized text_
**Here is some bold text**
__Here is some bold text__

*You **can** combine them*

#BLOCKQUOTES

As Mark Twain said:

>History doesn't repeat itself,
>but it rhymes.

#LISTS

*Unordered*

* Item 1
* Item 2
  * Item 2a
  * Item 2b

*Ordered*

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

#BACKSLASH ESCAPES

Markdown allows you to use backslash escapes to generate
literal characters, which would otherwise have special meaning
in Markdown's formatting syntax

\*literal asterisks\*

Markdown provides backslash escapes for the following characters:

\  backslash                 () parentheses
`  backtick                  # hashmark
*  asterisk                  + plus sign
_  underscore                - minus sign (hyphen)
{} curly braces              . dot
[] square brackets           ! exclamation point

GitHub.com uses its own version of the Markdown syntax, GFM, that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

USERNAME @MENTIONS
Typing an @ symbol, followed by
a username, will notify that person
to come and view the comment.
This is called an “@mention”,
because you’re mentioning the
individual. You can also @mention
teams within an organization.

ISSUE REFERENCES
Any number that refers to an Issue or
Pull Request will be automatically
converted into a link.

#1
github-flavored-markdown#1
defunkt/github-flavored-markdown#1

EMOJI
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat:
GitHub supports emoji!
To see a list of every image we
support, check out
__www.emoji-cheat-sheet.com__

FENCED CODE BLOCKS
```javascript
function test() {
 console.log("look ma’, no spaces");
}
```

    function test() {
      console.log("look ma’, no spaces");
    }

Markdown coverts text with four leading spaces into a code block; with GFM you can
wrap your code with ``` to create a code block without the leading spaces. Add an
optional language identifier and your code will get syntax highlighting.

TASK LISTS
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)

TABLES
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

First Header Second Header
Content cell 1 Content cell 2
Content column 1 Content column 2
You can create tables by assembling
a list of words and dividing them
with hyphens - (for the first row),
and then separating each column
with a pipe | :