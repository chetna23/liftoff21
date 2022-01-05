# FOR GENERATING DOCUMENTATION ONLY
*You will need to download this file or view it in Raw mode in order to see the Markdown being referenced*

<hr>

# Heading

# This is an `<h1>` tag
## This is an `<h2>` tag
###### This is an `<h6>` tag

<hr>

# Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

~~This will be stricken~~

<hr>

# Lists
## Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b

## Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

<hr>

# Images
![GitHub Logo](/images/logo.png)

Format: ![Alt Text](url)

<hr>

# Links

http://github.com - automatic!

[GitHub](http://github.com)

<hr>

# Blockquotes

Someone quotable said:

> This is a sample inline blockquote.

<hr>

# Inline Code

I think you should use an
`<addr>` element here instead.

<hr>

# Syntax Highlighting

Using backticks
```typescript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

Using four-space indentation (No highlighting)

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }

<hr>

# Task Lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

<hr>

# Tables

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

<hr>

# SHA References

Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac

mojombo@16c999e8c71134401a78d4d46435517b2271d6ac

mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

<hr>

# Issue references within a repository

Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1

mojombo#1

mojombo/github-flavored-markdown#1

<hr>

# Username @mentions

Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

<hr>

# Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

<hr>

# Emoji
GitHub supports emoji!

To see a list of every image we support, check out the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).