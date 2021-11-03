# Links
A key idea in [[Obsidian]] is the notion of Links. ^3b1d6c

A link is exactly what it sounds like: a connection between two different files. It is exactly like a link on the web.
- Links are visualized in the [[Graph View]]. Wowie!

Links can be written in two different ways:e
- [[Markdown]] syntax: `[displayed text](fileaddress)` - ie [Outline](Workshop%20Outline)
- Wikilink syntax `[[Name of file]]` ie [[Workshop Outline]]

## Creating New Links
Just type `[[` and then type the name of the page. 
If it exists, select and hit return. 
If it doesn't then just hover and Command-click or hit `opt-return`

[[New Page]]

## Section Links
Links can also be used to refer to specific sections in a document:
`[[Workshop Outline#Intro]]` creates a link to the Intro section of the Outline File: [[Workshop Outline#Intro]]

## Block References
These are a liiiitttle confusing, but basically you can also link to any block of text which is any chunk of words seperated by carrige returns. The syntax for that is:
`[[File Name^block name]]` 
You can search the entire vault with`[[^^block name]]` (a little buggy with large vaults?)

[[#^3b1d6c]]

## Aliases
[[#^3b1d6c]] is nota very pretty link, so you can give any link an alias with a `|` ie
`[[name of file| displayed text]]` ie [[README|Please read me!]]
## Embedding Links
But we can do even MORE with links- we can EMBED them. To do that just add and `!` in front like this: `![[filename]]`

eg:
![[Workshop Outline]]
![[Workshop Outline#Intro]]
![[Workshop Outline#^a0a783]]

# Backlinks
Backlinks are another super helpful way of seeing your connections. Backlinks are all the links TO the page you are on.

They can be found in the backlinks pane.

