# COMPLETAR  
Durante esta práctica, se logró un avance significativo en la comprensión y manejo de Docker y la creación de contenedores a partir de imágenes personalizadas. Antes de realizar esta práctica, los conocimientos sobre la construcción de imágenes, la creación de contenedores y la resolución de problemas asociados con la configuración de Docker eran limitados o teóricos. A continuación, se destacan los principales aprendizajes y beneficios obtenidos para la formación profesional:

 Se adquirió experiencia práctica en la redacción y estructuración de un Dockerfile, comprendiendo la importancia de cada instrucción, como FROM, RUN, COPY, EXPOSE y CMD, para construir imágenes funcionales basadas en un sistema operativo y servicios específicos.

Un desafío importante que se resolvió fue la dificultad de conectarse a los repositorios de CentOS durante la construcción de la imagen. Esto implicó investigar y aprender sobre cómo manejar los problemas de red en Docker, como configurar la opción --network=host y modificar la configuración de los repositorios para evitar errores de conectividad.

Se comprendió mejor cómo Docker construye imágenes en pasos, cómo se reutilizan los pasos en caché y cómo realizar cambios eficientes en las imágenes para evitar reconstrucciones innecesarias.

Se aprendió a ejecutar contenedores a partir de imágenes personalizadas y a mapear correctamente los puertos entre el contenedor y el host, lo cual es esencial para desplegar servicios web y otras aplicaciones que requieren comunicación con el exterior.

Se obtuvo experiencia en la gestión de contenedores en ejecución, incluidos comandos para listar contenedores (docker ps), detenerlos y eliminarlos, lo cual es clave para mantener un entorno de trabajo ordenado y funcional.

Se aprendió a versionar imágenes de Docker para mantener un control sobre las diferentes iteraciones y mejoras de una aplicación o servicio, asegurando la capacidad de retroceder a versiones anteriores si es necesario.

Uno de los principales problemas enfrentados fue la imposibilidad de acceder a los repositorios de CentOS para actualizar el sistema y realizar instalaciones. Este problema se resolvió investigando y aplicando una solución que implicaba modificar la configuración de red del contenedor y ajustar los repositorios de yum. Este aprendizaje refuerza la capacidad de resolución de problemas y la adaptabilidad ante situaciones inesperadas en el desarrollo de contenedores.

Estos conocimientos y habilidades adquiridos son valiosos para la formación profesional, especialmente en áreas relacionadas con el desarrollo de aplicaciones en contenedores, DevOps y despliegue de servicios en entornos de producción.
