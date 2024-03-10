# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

###  Adding a remote

A remote can be added with the `git remote add` command, followed by ther name and location of the remote. 

The nanme is a local name, meaning it's your label and doesn't impact the actual remote whatsoever.

``` 
git remote add origin https://github.com/elevenfiftyacademy/gitfundamentals.git
```

### Removing a remote
a remote can be removed with the `git remote remove` command, followed by the name of the remote

```
git remote remove origin
```

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)
