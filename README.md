Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o ejecutarlos en una máquina virtual Linux.

## Ejecución

python3 main.py <filename> <dup>
filename: **ruta** al fichero que contiene la lista de palabras, una por línea
dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista

## Ejemplo

Creamos un archivo **words.txt** que va a contener las siguientes palabras:

- ManzanaA
- Piso
- Escalera
- ManzanaA
- Tetera
- Mesa
- Piso

Para la ejecución ejecutamos lo siguiente:

### **WINDOWS**

    python ./main.py words.txt yes

### **LINUX**

    python3 main.py words.txt yes

**words.txt** => hace referencia al archivo creado
**yes** => Para eliminar palabras duplicadas.

### **SALIDA**

    Se leerán las palabras del fichero words.txt
    ['Escalera', 'ManzanaA', 'Mesa', 'Piso', 'Tetera']
