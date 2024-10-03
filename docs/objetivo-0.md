# Creación de Par de Claves (Pública/Privada) y Subida de Clave Pública a GitHub

## Genero un nuevo par de claves:

```bash
ssh-keygen -t rsa -b 4096 -C "pablotl@correo.ugr.es"
```

## Especifico la ruta de almacenamiento
Acepto la ubicación predeterminada (`~/.ssh/id_rsa`).

## Agrego la clave SSH al agente SSH
Me aseguro de que el agente SSH esté en ejecución y agrego la clave privada:

```bash
eval "$(ssh-agent -s)"
sh-add ~/.ssh/id_rsa
```


## Subo la Clave Pública a GitHub

Una vez que haya generado mis claves, debo subir la clave pública a GitHub para autenticar el repositorio.
1. En  **Settings** selecciono **SSH and GPG keys**.
2. Hago clic en el botón **New SSH Key** y pego el contenido de mi clave pública en el campo.
3. **Add SSH Key** para guardar.

# Configuro Nombre y Correo Electrónico para los Commits

Para que el nombre y correo electrónico aparezcan correctamente en tus commits, necesitas configurarlo globalmente en Git.

### Paso 1: Configuro el nombre

```bash
git config --global user.name "Tu Nombre Completo"
```

### Paso 2: Configuro el correo electrónico

```bash
git config --global user.email "tu_correo_electrónico@ejemplo.com"
```
