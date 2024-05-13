# Tutorial de Comandos Básicos de Terminal con Ejemplos

1. **pwd** (Print Working Directory)

   - Descripción: Este comando muestra la ruta completa del directorio en el que te encuentras actualmente.
   - Ejemplo:

   ```bash
   pwd
   ```

   Salida:

   ```bash
   /home/usuario
   ```

2. **ls** (List)

   - Descripción: Este comando lista los archivos y carpetas en el directorio actual.
   - Ejemplo:

   ```bash
   ls
   ```

   Salida:

   ```bash
   example
   ```

3. **mkdir** (Make Directory)

   - Descripción: Este comando crea un nuevo directorio con el nombre especificado.
   - Ejemplo:

   ```bash
   mkdir example
   ```

4. **cd** (Change Directory)

   - Descripción: Este comando se utiliza para moverse entre diferentes directorios en el sistema de archivos.
   - Ejemplo:

   ```bash
   cd example
   ```

5. **touch**

   - Descripción: Este comando crea un nuevo archivo vacío con el nombre especificado.
   - Ejemplo:

   ```bash
   touch file.txt
   ```

6. **cat** (Concatenate)

   - Descripción: Este comando muestra el contenido de un archivo en la terminal.
   - Ejemplo:

   ```bash
   cat file.txt
   ```

   Salida:

   ```bash
   (no hay contenido)
   ```

7. **nano**

   - Descripción: Nano es un editor de texto en la terminal. Permite editar archivos de texto directamente desde la terminal.
   - Ejemplo:

   ```bash
   nano file.txt
   ```

   (Editar el archivo y luego guardar y salir con `Ctrl+X`, luego presiona `Y` para confirmar los cambios y finalmente `Enter` para salir)

8. **vim** (Vi IMproved)

   - Descripción: Vim es un editor de texto avanzado en la terminal, similar a nano pero con más características.
   - Ejemplo:

   ```bash
   vim file.txt
   ```

   (Editar el archivo y luego guardar y salir con `:wq` y `Enter`)

9. **cp** (Copy)

   - Descripción: Este comando copia archivos o directorios.
   - Ejemplo:

   ```bash
   cp file.txt file2.txt
   ```

10. **mv** (Move)

    - Descripción: Este comando mueve o renombra archivos o directorios.
    - Ejemplo:

    ```bash
    mv file.txt ../
    ```

11. **rm** (Remove)

    - Descripción: Este comando elimina archivos o directorios.
    - Ejemplo:

    ```bash
    rm file2.txt
    ```

12. **grep** (Global Regular Expression Print)

    - Descripción: Este comando es para buscar patrones en archivos. En este caso, buscamos un patrón específico en un archivo de texto.
    - Ejemplo:

    ```bash
    grep Lucy file.txt
    ```

    Salida:

    ```bash
    Lucy
    ```

13. **man** (Manual)

    - Descripción: Este comando muestra el manual de referencia para un comando específico. Proporciona información detallada sobre cómo usar un comando en particular, incluyendo sus opciones y argumentos.
    - Ejemplo:

    ```bash
    man grep
    ```

14. **clear**
    - Descripción: Este comando limpia la pantalla de la terminal, eliminando el historial de comandos anteriores.
    - Ejemplo:
    ```bash
    clear
    ```

```bash
vim file.txt
```

Lucy
Javi
Hamtarina

```bash
grep Lucy file.txt
```

```bash
grep -h
```

```bash
man grep
```

```bash
grep -n Lucy file.txt
```

```bash
touch pets.txt
```

Lucypan
Javita

```bash
grep -n Lu *
```

```bash
clear
```

```

```
