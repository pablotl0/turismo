# Creación de Par de Claves (Pública/Privada) y Subida de Clave Pública a GitHub

## Ejecuta el siguiente comando para generar un nuevo par de claves:

```bash
ssh-keygen -t rsa -b 4096 -C "pablotl@correo.ugr.es"
```

## Especificar la ruta de almacenamiento
Cuando te pida una ubicación para guardar la clave, acepto la ubicación predeterminada (`~/.ssh/id_rsa`).

## Agregar la clave SSH al agente SSH
Me aseguraro de que el agente SSH esté en ejecución y agrego la clave privada:

```bash
eval "$(ssh-agent -s)"
sh-add ~/.ssh/id_rsa
```


## Subir la Clave Pública a GitHub

Una vez que haya generado mis claves, debo subir la clave pública a GitHub para autenticar el repositorio.
1. En  **Settings** selecciono **SSH and GPG keys**.
2. Haz clic en el botón **New SSH Key** y pego el contenido de mi clave pública en el campo.
3. **Add SSH Key** para guardar.

# Configuración de Nombre y Correo Electrónico para los Commits

Para que tu nombre y correo electrónico aparezcan correctamente en tus commits, necesitas configurarlos globalmente en Git.

### Paso 1: Configurar el nombre

```bash
git config --global user.name "Tu Nombre Completo"
```

### Paso 2: Configurar el correo electrónico

```bash
git config --global user.email "tu_correo_electrónico@ejemplo.com"
```





Con esto, ya habrás configurado correctamente tu entorno de Git y GitHub para trabajar de forma adecuada en la asignatura.
```

Este archivo contiene los pasos necesarios para la generación de un par de claves SSH, su subida a GitHub, la configuración de los detalles de usuario para los commits y la edición de perfil en GitHub. Puedes copiar y pegar este texto en un archivo `.md`.
