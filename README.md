# Git revert example

Here lets do a git revert on the first commit. First lets do a

    git log

to find out where the problematic commit is.  

<i>Remember, you can use b to go back and f to go forwards, and q to quit the log.</i>

Then we can checkout the code at different locations to see when the problem occurred.

    git checkout <hash>

when you have figured out when the problem was created, lets checkout the main again.

    git checkout main

lets revert that change now!

    git revert <hash>