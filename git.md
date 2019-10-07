# Comandos de git
## Local
- Inicializar un repositorio(control de versiones en un proyecto)
  1. asegurarse de que la terminal esta activa en el directorio que deseamos convertir en repositorio.
  2. ```bash
      git init
      ```

- Verificar el estado actual del repositorio
```bash
git status
```

- Agregar un archivo al repositorio para darle seguimiento a sus versiones
  ```bash
  git add <nombre_del_archivo>
  ```
  por comodidad podemos utilizar
  ```bash
  git add .
  ```

- Hacer una instantánea del código actual(revisión o versión) de tu proyecto.
```bash
 git commit -m "Si estoy en esta versión, la funcionalidad que veré es:"
```

## Remoto(Github)
- Conectar mi repositorio local con el de la nube
  1. Crear un repositorio en la nube, sin README ni archivos .ignore
  2. Agregar la dirección remota a nuestro repositorio.
  ```bash
  git remote add origin <url_del_proyecto_de_github>
  ```

- Subir mis cambios a la nube
```bash
git push origin master
```

- Bajar cambios desde la nube
```bash
git pull origin master
```

- Clonar un proyecto anteriormente respaldado en la nube
```bash
git clone <url_del_repositorio>
```
