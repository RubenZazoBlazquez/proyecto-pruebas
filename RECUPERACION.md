# Recuperación de errores en Git

## Error simulado
Eliminé el archivo errores.sh y confirmé el cambio con un commit.

## Comandos utilizados
- rm errores.sh
- git add .
- git commit -m "Borrar errores.sh por error"
- git checkout HEAD~1 -- errores.sh
- git add errores.sh
- git commit -m "Recuperar archivo eliminado"

## Aprendizaje
He aprendido que Git guarda el historial completo de los archivos y permite recuperarlos incluso después de haberlos eliminado y confirmado el cambio.
