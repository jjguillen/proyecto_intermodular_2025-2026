### Resumen comandos git

git config --global user.name "nombre"   # Configura tu nombre de usuario en git
git config --global user.email "email"   # Configura tu correo electrónico en git
git clone URL-del-repositorio            # Clona el repositorio remoto en tu equipo
git status                               # Muestra el estado actual del repositorio y archivos
git add archivo.ext                      # Añade cambios de un archivo al área de preparación (staging)
git commit -m "mensaje"                  # Crea un commit con los cambios preparados
git push origin rama                     # Sube tus commits a la rama remota
git pull origin rama                     # Descarga y fusiona los cambios de la rama remota
git branch                               # Lista las ramas existentes y la rama activa
git checkout nombre-rama                 # Cambia a la rama especificada
git checkout -b nueva-rama               # Crea y cambia a una nueva rama
git merge nombre-rama                    # Fusiona la rama indicada con la actual
git log                                  # Muestra el historial de commits
git diff                                 # Muestra las diferencias entre estado actual y último commit
git branch -d nombre-rama                # Elimina una rama local ya fusionada
git push origin --delete nombre-rama     # Elimina la rama remota en el servidor
git checkout HASH-del-commit             # Te mueve al commit indicado (modo detached HEAD) (HEAD~2 hace referecia a hace dos commits)
git commit --amend                       # Corrige el mensaje o añade archivos al último commit local, antes de hacer push
git reset --soft HEAD~1                  # Deshace el último commit local y conserva los cambios en staging (sin perderlos)
git reset --hard HEAD~1                  # Elimina el último commit local, perdiendo los cambios también en el directorio de trabajo
git revert HASH                          # Deshace (revierte) un commit específico creando uno nuevo contrario; usado si ya hiciste push
