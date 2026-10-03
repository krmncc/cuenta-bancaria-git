# Cuenta bancaria — Git y pull requests

**Autor:** Maria del Carmen Chavez Conde

## Cómo correr

    ./correr.sh

## Mis pull requests

| # | Qué cambió |
|---|---|
| 1 | El estado de cuenta muestra cuántos retiros se hicieron y cuántos fueron gratis |
| 2 | README y evidencia de la práctica |

## Boleto de salida

1. ¿Qué diferencia hay entre `git add` y `git commit`?

   Respuesta: git add->Prepara todos los archivos para el siguiente commit.
   git commit->Guarda lo preparado en la historia.

2. ¿Por qué después del merge en GitHub tu `main` de Ubuntu no tenía el cambio hasta que hiciste `git pull`?

   Respuesta: porque se lo pedí con ese git pull en el main de mi computadora

3. Abriste un PR y después hiciste otro commit en la misma rama. ¿Qué pasó con el PR?

   Respuesta:No hubo problemas de merge

4. ¿Por qué en un equipo nadie hace cambios directamente en `main`?

   Respuesta: Porque se hace una rama para que todos los desarrolladores hagan cambios, pruebas, etc... y los errores se corrigen en esta rama y solo el encargado del subir los cambios al main puede subirlos.