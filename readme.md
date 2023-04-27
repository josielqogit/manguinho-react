```git config --global --edit```
```git config --global core.editor code```

```
[user]
	name = Josiel Quennehen de Oliveira
	email = josielqo@gmail.com
[core]
	autocrlf = false
	safecrlf = false
	editor = code --wait
[push]
	followTags = true
[alias]
	c = !git add --all & git commit -m
	l = !git log --pretty=format:'%C(red)%s: %C(cyan)%cn %C(green) %cr %C(white)%d %C(yellow)%h'
	s = !git status -s
	amend = !git add --all & git commit --amend --no-edit
	addorigin = !git remote add origin
	count = !git shortlog -s --grep
	publish = !git push --set-upstream origin
```
