If you’re opening an issue to report `Error creating pull request: Unprocessable Entity (HTTP 422)` in `cask-repair`:

1. [Test your ssh connection to GitHub](https://help.github.com/articles/testing-your-ssh-connection/).
2. Add the following to your `~/.ssh/config` file (correct the last line with the actual path):

```git
Host github.com
Hostname github.com
User git
IdentityFile /path/to/ssh/key
```

---

If reporting any other issue, delete this template and go ahead.
