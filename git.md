## git flow process

### Initialization

```bash
git flow init
```

- command for git flow init
- After execute this command, you can set branch naming convetion.(Recommanded default value)


### Develop new feature
```bash
git flow feature start MY_FEATURE
```

- make new branch for new feature.
- new branch name: feature/MY_FEATURE

```badh
git flow feature fininsh MY_FEATURE
```

- after develop new feature, merge feature branch to develop branch
- change this branch  to develop branch.
- merge feature branch to develop branch.
- remove feature branch.
