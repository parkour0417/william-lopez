# william-lopez
este es mi presentacion
  git clone https://github.com/TU_USUARIO/actividad-2-git.git
cd actividad-2-git
git config --global user.name "william lopez"
git config --global user.email "lopez.william2@uniagraria.edu.co"
echo "Primera línea" > notas.txt
git add notas.txt
git commit -m "Agrega notas.txt con la primera línea"

echo "Segunda línea" >> notas.txt
git commit -am "Añade segunda línea a notas.txt"

echo "Contenido" > tareas.txt
git add tareas.txt
git commit -m "Crea tareas.txt con contenido inicial"
git push origin main
