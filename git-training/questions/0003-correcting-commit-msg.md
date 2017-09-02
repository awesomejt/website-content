# Correcting Commit message

## Question

Hello Mr. Taylor,

first of all, I would like to thank you for the great course.

When I wrote a commit message, I made a typing mistake. Would I be possible to correct it?

Thank you in advance

## Answer

Yes, you can use the --amend option with the commit command to fix the last commit message like this:

```
git commit --amend -m "Updated commit message"
```

If you need to correct commit messages further back, you will need to use interactive rebase.

Atlassian's [Git Rebase][rebase] tutorial covers it very well.

[rebase]: https://www.atlassian.com/git/tutorials/rewriting-history#git-rebase-i
