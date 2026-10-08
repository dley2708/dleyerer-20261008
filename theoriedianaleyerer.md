# Befehle

1. git clone https://github.com/dley2708/dleyerer-20261008.git

2. Textdatei lokal erstellt und mit VS geöffnet

3. PS C:\Users\leyer\Git\dleyerer-20261008> git add dianaleyerer.md

4.  PS C:\Users\leyer\Git\dleyerer-20261008> git commit -m "text added"
    [main (root-commit) e952cc9] text added
    1 file changed, 2 insertions(+)
    create mode 100644 dianaleyerer.md

5.  PS C:\Users\leyer\Git\dleyerer-20261008> git checkout -b feature/dianaleyerer
    Switched to a new branch 'feature/dianaleyerer' 

6.  PS C:\Users\leyer\Git\dleyerer-20261008> git add .
    PS C:\Users\leyer\Git\dleyerer-20261008> git commit -m "branch erstellt und hinein geschrieben"
    [feature/dianaleyerer 19aaae7] branch erstellt und hinein geschrieben
     1 file changed, 3 insertions(+), 1 deletion(-)

7. PS C:\Users\leyer\Git\dleyerer-20261008> git checkout main
Switched to branch 'main' 

8. PS C:\Users\leyer\Git\dleyerer-20261008> git merge feature/dianaleyerer
Updating e952cc9..19aaae7
Fast-forward
 dianaleyerer.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

 9. PS C:\Users\leyer\Git\dleyerer-20261008> git status
On branch main
nothing to commit, working tree clean

10. PS C:\Users\leyer\Git\dleyerer-20261008> git log
commit 19aaae755f3acc5bcc5b1328cedc1e2da7a9e6a3 (HEAD -> main, feature/dianaleyerer)
Author: Diana Leyerer <leyererdiana@gmail.com>
Date:   Thu Oct 8 08:05:33 2026 +0200

    branch erstellt und hinein geschrieben

commit e952cc93848583d3f0a9ae00af57f6ddb66a4683
Author: Diana Leyerer <leyererdiana@gmail.com>
Date:   Thu Oct 8 08:00:50 2026 +0200

    text added

## Merge Konflikte

1. Wenn man mehrere Branches hat unt einer den anderen versucht zu überschreiben
2. 