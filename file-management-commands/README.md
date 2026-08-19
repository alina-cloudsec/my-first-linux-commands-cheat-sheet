# File Management Commands

## What I Did

I made a new file called `notes.txt` using `touch`. I tried to add
text into it using `echo`, but I made a typo in the filename and
accidentally typed `notrs.txt` instead of `notes.txt`. This created a
second, separate file with my text inside it, while `notes.txt`
stayed empty the whole time.

When I ran `cat notes.txt`, it showed nothing, since the file was
actually empty because of that typo. I did not catch this mistake
during the session, so it also shows up in `cp`, since I copied the
empty `notes.txt` file, not the one with real text in it.

I renamed the copy using `mv`, then deleted it using `rm`. The
`notrs.txt` file with the actual typo'd text is still there in the
final listing, since I never went back to clean it up.

**What I learned:** a small typo in a filename does not throw an
error, it just quietly creates a new file. This taught me to always
double check filenames with `ls` right after running a command,
instead of assuming it worked.
