## Respuestas git

1. ¿Qué diferencia existe entre git add y git commit?
   git add elige qué cambios quiero guardar, como meterlos en una caja. git commit cierra la caja y la guarda en el historial con un mensaje.

2. ¿Qué hace git push y por qué puede ser rechazado?
   git push sube mis commits de mi ordenador a GitHub. Puede ser rechazado si en GitHub hay cambios nuevos que yo todavía no tengo.

3. ¿En qué se diferencian git fetch y git pull?
   git fetch solo mira si hay cambios nuevos en GitHub, pero no los trae a mis archivos. git pull los trae y los junta con mi trabajo.

4. ¿Qué significa origin/main?
   Es la copia de la rama main que está en GitHub (origin es el nombre del repositorio remoto).

5. ¿Qué muestra git status antes y después de git add?
   Antes de git add muestra los archivos como modificados y sin preparar. Después de git add los muestra como preparados para hacer commit.

6. ¿Para qué sirve git diff --cached?
   Para ver los cambios que ya preparé con git add y que se guardarán en el próximo commit. Sirve para revisar antes de confirmar.

7. ¿Qué indica git log --oneline HEAD..origin/main?
   Muestra, en una línea cada uno, los commits que están en GitHub y que yo todavía no tengo en mi ordenador. Si no sale nada, estoy al día.

8. ¿Por qué conviene realizar commits pequeños y descriptivos?
   Porque así es más fácil entender qué se cambió y cuándo, encontrar errores y volver atrás si algo sale mal. Los mensajes claros ayudan a mí y a otras personas.

9. ¿Cómo resolví el push rechazado y por qué no utilicé --force?
   Hice git fetch para ver qué había nuevo, y luego git pull --no-rebase origin main para traer esos cambios y juntarlos con los míos. Después hice git push origin main y funcionó. No usé --force porque obliga a GitHub a aceptar mis cambios y puede borrar el trabajo de otra copia.

10. ¿Qué diferencia hay entre un diagrama de clases y un diagrama de secuencia?
    El diagrama de clases muestra cómo está organizado el programa: las clases, sus datos y cómo se relacionan. El diagrama de secuencia muestra qué ocurre paso a paso, en qué orden se envían mensajes los elementos del programa.

11. ¿Qué utilidad tienen los breakpoints durante una depuración?
    Permiten parar el programa en una línea concreta para ver el valor de las variables y avanzar paso a paso. Así se encuentra más fácil dónde está el error.

12. ¿Por qué son importantes las pruebas antes y después de refactorizar?
    Refactorizar es mejorar el código sin cambiar lo que hace. Las pruebas antes demuestran que funciona, y las pruebas después confirman que sigue funcionando igual.

13. ¿En qué carpeta y ventana de IntelliJ estaba cuando se rechazó el push?
    Estaba en la carpeta ~/git/dam-ets-equipo2, en la ventana de IntelliJ del proyecto dam-ets-equipo2.