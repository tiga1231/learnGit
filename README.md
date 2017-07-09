Logs
```
# see diff
git log -p
git log --pretty=format:"%h %s" --graph
git log --pretty=format:"%Cgreen %h %Creset %s %C(dim cyan) %an (%ar)" --graph
```

Tagging
```
# list tags
git tag

# add anotated tag to current node
git tag -a v1 -m 'tag comments'
# add light weight tag to current node
git tag v2
# add tag to other nodes
git tag <commit hash>

#push a tag
git push origin v1
#push all tags
git push origin --tags
```

Aliases
```
git config --global alias.cm commit
git config --global alias.unstage 'reset HEAD --'
git config --global alias.last 'log -1 HEAD'
```
