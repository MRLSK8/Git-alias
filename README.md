### Git-alias

## [alias]
- ci = commit -m
	- st = status -sb
	- undo = checkout --
	- rollback = reset --soft 
	- rmao = remote add origin
	- pom = push -u origin master
	- sf = show --name-only
	- unstage = reset HEAD --
	- co = checkout
	- cm = checkout master
	- cb = checkout -b
	- db = checkout -D 
	- lg = log --pretty=format:'%Cred%h%Creset %C(bold)%cr%Creset %Cgreen<%an>%Creset %s' --max-count=30
	- incoming = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' ..@{u})
	- outgoing = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' @{u}..)
