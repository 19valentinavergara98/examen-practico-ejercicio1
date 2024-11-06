
1. Instalar Node.js , Instalar Python 

2. g++ -o cgi-bin/funciones.cgi cgi-bin/funciones.cpp -lnetapi32

3. python -m http.server --cgi 8000

4. http://localhost:8000/



para probar directo (con librería netapi32.lib)

g++ nuevoUsuario.cpp -o nuevoUsuario.exe -lnetapi32
g++ eliminaUsuario.cpp -o eliminaUsuario.exe -lnetapi32

Crea una interfaz, con el fondo azul (requisito de la empresa) donde introducir el número de horas en un INPUT tipo texto, así como el botón de CALCULAR.