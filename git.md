### How to undo a git commit --amend
	git reset --soft HEAD@{1}
	git commit -C HEAD@{1}
