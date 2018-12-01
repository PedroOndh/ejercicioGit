# Respuestas del ejercicio

* **11.** git reset --hard HEAD~1
Con este comando deshacemos el ultimo commit realizado.
* **12.** git reset --hard HEAD@{1} o git reset --hard *"hash del ultimo Commit"*.
Para poder dar un paso atras en el reflog y recuperar asi el ultimo commit.
* **13.** No, pero el branch styled ya tenia todos los commits de la rama master, por lo que realizar este merge no resulta en ningun cambio.
* **19.** Si da un conflicto ya que hay lineas comunes que cambian, cambiamos las lineas en conflicto y a continuacion realizamos un commit para terminar el merge.
* **21.** Este merge resultará en un merge fast forward, por lo que no generará ningún conflicto, ya que todos los commits forman una lista sin ramificaciones en este momento.
* **25.** git log --graph
* **26.** Si, ya que todos los commits forman una lista, por lo que desde master a title no existe ramificación ninguna.
* **27.** git reset HEAD~1
* **28.** git checkout -- git-nuestro.md
* **29.** git branch -D title 
* **30.** git reset --hard HEAD@{1} o git reset --hard *"hash del Commit del merge"*
* **32.** git checkout *"hash del primer commit"*
* **33.** git checkout *"hash del ultimo commit"*