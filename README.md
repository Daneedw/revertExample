# Git revert example

Here lets do a git revert on the first commit. First lets do a

    git log

to find out where the problematic commit is.

Then we can checkout the code at different locations to see when the problem occurred.

    git checkout <hash>

when you have figured out when the problem was created, lets checkout the main again.

    git checkout main

lets revert that change now!

    git revert <hash>