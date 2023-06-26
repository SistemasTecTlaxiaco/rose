# Módulo 2.4 Asignación

En esta lección, aprendió acerca de los conflictos de fusión. Para completar esta tarea, creará un archivo "README.md" que diga "Hola mundo". Copie y pegue los siguientes comandos en su línea de comando, luego presione Entrar:

''
mkdir MergeConflict
cd MergeConflict /
git init
toque README.md
echo "echo Hola"> README.md
git add.
git commit -m "primer compromiso con el maestro"
git checkout -b nueva rama
echo "Hola mundo"> README.md
git add.
git commit -m "primer compromiso en nueva rama"
maestro de git checkout
echo "Hola"> README.md
git add.
git commit -m "segundo compromiso en el maestro"
git fusionar nueva rama
''

Este "script" creará un conflicto de fusión. Resuelva el conflicto de fusión para que el texto en `README.md` sea` "Hola mundo" `.

## Sumisión
Para enviar esta tarea, cree un problema titulado "Asignación del módulo 2.4" en este repositorio. En el problema, proporcione una captura de pantalla de su línea de comandos que muestre los comandos que usó para resolver el conflicto de fusión en esta asignación, luego continúe con el siguiente módulo.
