some configs
```
git config user.name "XXX"
git config user.email "XXX"
```

logout
```
git credential-osxkeychain erase
host=github.com
protocol=https
<press return>
```

undo last commit (e.g. forgot to exclude some files through .gitignore)
```
git reset HEAD~
```

merge message (e.g. after pull)
```
<press i>
<type your message>
<press esc>
:w
<press return>
:q
<press return>
```
