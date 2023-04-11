These are programs that I have converted to run on the [Agon
Light](https://www.thebyteattic.com/p/agon.html)
computer which uses BBC BASIC. These come from my collection, which is
mostly centered around Microsoft-Based dialects. So these programs
required just a little tweaking to run. I also have some original 
code which I have written.

I have presented them in both tokenized and text form, and I will
continue to add to this repository as my collection grows.

Converted Programs
==================
* __LANDER__ - You are descending toward the moon with limited fuel. The
  objective is to enter fueld commands to land the LEM! This program
  was originally from the IMSAI corporation and written in 1977. I had
  to make some minor adjustments, mostly involving the default number
  printing and TAB handling. By default, BBC BASIC puts left padding
  on numbers, and that was throwing off the table. Include TAB(0) will
  fix it. I also had to close a few quotations and zero a couple of
  variables to avoid undefined variable errors.

* __NIM__ - I have had this basic program for years, but I don't know
  where it came from because the source was listed as unknown at the
  top. All I had to do with this one was throw a little DIM at the top
  for the S array. MS BASIC is rather forgiving about undeclared
  variables and arrays!

* __WUMPUS__ - This is the original "Hunt the Wumpus" game written by 
  Gregory Yob in 1972. I did a few things to make this program work on
  the Agon Light. First, I decided to modernize it a little.
  I converted its subroutines to BBC BASIC procs so that I could
  follow the logic of the program better. The reason I did this is the
  original code would occasionally fail with a "no subroutine" error
  on return statements. I worked out most of these, but two remained
  that I could not figure out. These were in the move and arrow
  routines. Fortunately, both were called from only one location in
  the program and so I turned them into gotos with returns simply
  jumping back to the appropriate line. The game works now, so enjoy
  hunting some wumpii!

* __SNOOPY__ - This is a program that draws an ASCII art image of Snoopy
  kicking a football. All I did to this program was add a MODE 0 to it
  because you can't see the whole image in mode 1. (The width is fine,
  but the height is not.) The original program was designed to run on
  a teletype so it produced a nice printout. I had this program on
  several computers, and even have it on a roll of paper tape! 


Original Programs
=================
* __MONITOR__ - Ok, so this is both an original program and a conversion.
  I wrote this program back in the late 1980s (maybe early 1990s) on
  my Commodore 64. I wrote this program because I could not get my
  hands on a monitor or assembler and I wanted to play with machine
  code. I really converted this one just to get a feel for BBC BASIC.
  On the Agon light, this program is not as needed because BBC BASIC
  has a built-in assembler and there is also the wonderful
  [ez80asm](https://github.com/envenomator/agon-ez80asm)
  program which is even better. Still, it can be fun to poke around in
  HEX. Perhaps I will write my own assembly language monitor for the
  Agon Light someday.
