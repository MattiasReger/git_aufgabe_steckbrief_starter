#Kontrollfragen:


F. Was ist der Unterschied zwischen Working Directory, Staging Area und Repository?
    A.  Working Directory: an Dateien arbeiten und Änderungen vornehmen
        Staging Area: hier landen Änderungen, die man mit git add für den nächsten commit vorgemerkt hat
        Repository: hier werden Änderungen dauerhaft gespeichert, nachdem man git commit ausgeführt hat

F. Woran erkennst du, ob ein Merge Fast-Forward war?
    A.  Ein Merge war ein Fast-Forward-Merge, wenn kein zusätzlicher Merge-Commit erstellt wurde und Git den Branch-Zeiger nur auf den neueren Commit verschiebt. Oft erscheint dabei die Meldung "Fast-forward"

F. Warum kann git merge --ff-only manchmal fehlschlagen?
    A.  git merge --ff-only schlägt fehl, wenn kein Fast-Forward-Merge möglich ist.
        Das passiert, wenn beide Branches eigene neue Commits haben und die Historie auseinanderläuft.

F. Was ist der Vorteil, Änderungen zuerst auf einem Branch wie dev zu machen?
    A.  Der Vorteil ist, dass Änderungen getestet und entwickelt werden können, ohne den Hauptbranch (main) zu beeinflussen.

F. Mit welchem Befehl siehst du den aktuellen Branch?
    A.  git branch

F. Mit welchen Befehlen machst du Änderungen sichtbar und dauerhaft (Stichworte: Staging & Commit)?
    A.  Mit git add werden Änderungen in die Staging Area übernommen. Mit git commit werden die gestagten Änderungen dauerhaft im Repository gespeichert.