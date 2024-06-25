# Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: 
mkdir python-final
3. Entramos en ella: 
cd python-final
4. Iniciamos el repositorio:
git init
5. Creamos un archivo:
touch finales.py
6. Abrimos VSC:
code .
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
python -V
python3 -V
8. Creamos el entorno virtual en Python:
python3 -m venv venv #Creamos el entorno virtual
9. Activamos el entorno virtual:
source venv/bin/activate #Activamos el entorno virtual en Linux
venv/scripts/activate #En windows
10. Hacemos actualización del pip de Python
python3 -m pip install --upgrade pip #Actualizamos el pip
11. Investigar ¿Qué es el pip y porque lo actualizamos?
12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.

## Respuesta 11
### ¿Qué es pip y por qué lo actualizamos?

¿Qué es pip?
pip es un acrónimo de "Pip Installs Packages". Es la herramienta de gestión de paquetes utilizada en Python, la cual permite instalar y gestionar bibliotecas y paquetes que no forman parte de la biblioteca estándar de Python. pip facilita el proceso de instalar, actualizar y desinstalar paquetes desde el índice de paquetes de Python (PyPI) y otras fuentes.

Funcionalidades de pip:
Instalar paquetes: Puedes instalar cualquier paquete disponible en PyPI.
Actualizar paquetes: Permite mantener los paquetes instalados a sus versiones más recientes.
Desinstalar paquetes: Puedes eliminar cualquier paquete que ya no sea necesario.
Gestionar dependencias: pip se asegura de que todas las dependencias de un paquete se instalen correctamente.
¿Por qué actualizamos pip?
Actualizar pip es importante por varias razones:

Nuevas características: Las nuevas versiones de pip a menudo incluyen características adicionales que mejoran su funcionalidad y facilidad de uso.
Mejoras de seguridad: Las actualizaciones pueden corregir vulnerabilidades de seguridad que podrían ser explotadas en versiones anteriores.
Corrección de errores: Las actualizaciones corrigen errores y fallos de versiones anteriores, mejorando la estabilidad y fiabilidad de pip.
Compatibilidad: Mantener pip actualizado asegura la compatibilidad con las nuevas versiones de Python y otros paquetes.
Mejor rendimiento: Las nuevas versiones pueden incluir optimizaciones que mejoran la velocidad y eficiencia de las operaciones de pip.
¿Cómo actualizar pip?
Para actualizar pip, se puede usar el siguiente comando en la línea de comandos:

sh
Copiar código
python -m pip install --upgrade pip
Este comando descarga e instala la última versión de pip, asegurando que se tenga acceso a las últimas mejoras y correcciones.

Resumen
pip es una herramienta esencial para la gestión de paquetes en Python. Mantener pip actualizado es crucial para aprovechar las nuevas funcionalidades, mejorar la seguridad, corregir errores, asegurar la compatibilidad y mejorar el rendimiento. Actualizar pip regularmente garantiza que las operaciones de gestión de paquetes sean lo más eficientes y seguras posibles.
