1) `git diff`
2) `git status`
3) `git add . && git commit -am "some changes"`
4) `git status`
5) `git push -u origin master`

![img_2.png](img_2.png)

Конфликт решила путем применения команды `git reset 21651a20fb735d6a5ffc8dc2466cdb9c7fd69f12`, откатилась до последнего коммита и исправила разницу в файлах вручную.
далее `git merge develop` и `git push`
