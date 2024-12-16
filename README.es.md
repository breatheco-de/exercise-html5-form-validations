<!--hide-->
# Validaciones de formulario HTML5
<!--endhide-->

Después de crear el HTML y el CSS para este formulario, debemos asegurarnos de que evite que el usuario envíe un formulario con la información o el formato incorrectos. En el desarrollo web, lo llamamos: Validación de formularios. Dale un vistazo a la [documentación oficial](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation).

Para evitar que se envíe un formulario, tenemos que escuchar el evento "enviar" que se activa con el formulario cuando el usuario presiona: la tecla Intro / Retorno o el botón Enviar.

Si quieres saber más sobre como prevenir los eventos: [https://www.youtube.com/watch?v=I_fVO_NzT2g&t=401s](https://www.youtube.com/watch?v=I_fVO_NzT2g&t=401s)

![Form Validations Preview](https://raw.githubusercontent.com/breatheco-de/exercise-html5-form-validations/master/preview.gif)

<onlyfor saas="false" withBanner="false">
 
## 🌱  Cómo iniciar este proyecto

No clones este repositorio porque usaremos una plantilla diferente.  

Recomendamos abrir la plantilla `vanillajs boilerplate`, utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes [clonar el repositorio de GitHub](https://4geeks.com/how-to/github-clone-repository) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
$ git clone https://github.com/4GeeksAcademy/vanillajs-hello
```

💡 Importante: Recuerda crear un nuevo repositorio, actualizar el remoto (`git remote set-url origin <tu nueva url>`), y subir el código a tu nuevo repositorio utilizando `add`, `commit` y `push`.  

</onlyfor>

## Instrucciones

Luego de que el usuario presione el botón de submit:
1. Asegúrate de detener el flujo del envío utilizando `preventDefault ()`, [aquí hay un poco más sobre preventDefault ()](https://www.youtube.com/watch?v=3SNyh57XSIA).
2. Después de evitar el envío, asegúrese de que todos los valores de entrada sean correctos y tengan el formato correcto.
3. Si hay una o más entradas con un valor no válido, muestre un error claro en la parte superior del formulario con un mensaje muy explícito sobre lo que sucedió.
4. Cambie el color de fondo de las entradas relevantes (las que tienen datos incorrectos).

## ¿Qué hacer si estás atascado?

¡No te sientas frustrado y pide ayuda! Después de probarte por tu cuenta durante 20 minutos, es hora de dejar de trabajar y pedir ayuda.

## :superhero: ¿Te sientes confiado?

Este requerimiento adicional no es necesario para completar el proyecto:

 Haz que los errores del formulario se visualicen arriba de cada input en lugar de mostrarlos en la parte de arriba del formulario. Si el error está en el correo electrónico entonces el mensaje de error debería aparecer justo arriba del input para correo electrónico, de esa forma el usuario entenderá más rápidamente donde está el problema.
