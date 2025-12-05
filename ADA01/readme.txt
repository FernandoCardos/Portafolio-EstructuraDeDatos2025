Indicaciones para compilar y ejecutar la aplicación:

1.  Asegúrate de tener todos los archivos (.c y .h) en la misma carpeta.
2.  Abre una terminal o línea de comandos.
3.  Usa el siguiente comando para compilar:
    gcc InfijoAPostfijoApp.c lector_archivos.c conversion.c evaluacion.c pila.c -o InfijoAPostfijoApp
    
    Este comando compila todos los archivos de código fuente y crea un ejecutable llamado "InfijoAPostfijoApp".

4.  Crea un archivo de entrada llamado 'exp_infijas.txt' en la misma carpeta con las expresiones que deseas evaluar, por ejemplo:
    2+3;
    2*(3+4);
    ((2+4)*7)+3*(9-5);

5.  Ejecuta el programa desde la terminal de la siguiente manera:
    ./InfijoAPostfijoApp exp_infijas.txt

6.  El programa generará un archivo de salida llamado 'exp_postfijas.txt' con los resultados.
