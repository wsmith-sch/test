# This is a test

Create orphan branch:
- call it "just-tex" or something
- remove all the files overleaf shouldn't see
    - (it will probably have to live with the .gitignore)
- add overleaf remote https://git@git.overleaf.com/project
- push like

    > git push overleaf just-tex:master

  etc

Merge changes like:

    > git merge just-tex --allow-unrelated-histories -X theirs
