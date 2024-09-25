
# Resumen de Comandos

## Crear repositorio:
![Crear repositorio](./inicioRepo.png)

## Instalar plugin de Git IV:
```bash
cd ~/bin # O cualquier otro directorio en el path de ejecución
wget https://raw.githubusercontent.com/JJ/IV/master/scripts/git-iv # O bajar el URL a ese directorio de cualquier otra manera
chmod +x git-iv
```

## Enlazar el nuevo repositorio :
```bash
git remote add origin https://github.com/pablotl0/cafeteria.git
```

## Crear rama para el objetivo:
```bash
git iv objetivo 0
```

## Editar el archivo `README.md` con la descripción del problema.

## Confirmar cambios:
```bash
git add README.md
git commit -m "Añadido el README con la descripción del problema a resolver en la asignatura"
```

## Empujar los cambios:
```bash
git push origin objetivo-0
```




