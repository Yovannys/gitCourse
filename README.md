# Archivo Readme con Mark Down

# git init: inicializa un repo y prepara el working area
# git add : adiciona al staging area
# git commit: adiciona al repository area

# Hay tres modos de deshacer cambios:
   * git reset --soft IDCommit: pone el archivo en staging area
   * git reset --mixed IDCommit: pone el archivo en working area
   * git reset --hard IDCommit: limpia working directory y staging area y deja un estado estable. Si alguien echo a perder una rama y se quiere regresar
   
# git brach [nombre rama]: agregar rama

# git brach: lista las ramas ( con asterisco, la rama actual)

# Se debe usar las ramas: cada desarrollo independiente o version (trabajo con angular en la rama master y quiero empezar con vue js en otra rama)

# Para mezclar Ramas:
  - Posicionarte en la rama final (donde quieres dejar el codigo final usando git checkout).
  - Hacer merge con la rama que estes interesado (los commits deben estar hechos o el working directory limpio)
  - git merge [rama-interes] :  git merge add-boostrap
  
# git flow: por cada caracteristica nueva se abre una nueva rama que son llamadas features branches:
  - La rama master es la estable y contiene el codigo de produccion
  - Se pueden tener ramas de release, hot fix, bugs

# work flow: utilizado en entornos mas reales, es una nomclatura o convencion de nombres para ramas: 

# pull request: contribucion o ayuda de codigo a alguien que lo necesite

# git remote -v : Para ver los repositorios remotos