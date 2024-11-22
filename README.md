# zayd-unix
#### An attempt at Unix: The goal is to create a Unix-like.

The secondary goal is to make it small, mainly in features. Not too much, though, there should still be some functionality.

-

I won't be working on this for a while, becuase I have other things to do.
####
---
*Remember, the **primary goal** is to create a Unix-like. Meaning, as of now, I don't have to make (most) of the programs on here, just the wires that connect it all.*

Right now, there are three things I want to work on, as called as by Wikipedia, "the first three key elements of the Unix operating system":
- ## tcc

  I'm not sure if the capabilities should be extended to ISO99, or if they should be downgraded/truncated to ANSI.

  Credit to [Fabrice Bellard](https://bellard.org)
- ## ed

  Credit to the members of and the group [GNU](http://gnu.mirror.constant.com).
  I might think about recreating ed to minimize it in the future, though.
- ## sh

  Credit to https://github.com/nanafox/simple_shell. Notes are same as ed.

Then, we can work on [Posix](https://en.wikipedia.org/wiki/List_of_POSIX_commands). I can already find that a few of these are redundant, combinable to other commands (ed -s <- sed), or simply bloat.