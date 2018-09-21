1. git clone git@bitbucket.org:orbisunt/orbis-example-training.git para clonar el repositorio
2. git remote show origin
3. git remote set-url origin [repo-github]
4. git push origin master
5. git filter-branch --tree-filter 'rm -f sc.16.tar.gz' HEAD
6. git push origin master
7. git rebase -i HEAD[colita de chancho]6
8. git count-objects -v 
	size: 150749
9. rm -Rf .git/refs/original
10. rm -Rf .git/logs/
11. git count-objects -v
	size: 150303 
