# P02-20

1. Para clonar un repositorio ajeno y realizar cambios en este, primero tenemos que realizar un fork de dicho repositorio y crearnos una copia de este con nuestra cuenta de github:
![ForkRepositorio](/P2/assets/ForkRepo.PNG)

2. Luego clonamos el repositorio remoto que en el que previamente realizamos un fork usando el comando:
`git clone https://github.com/Alba1999/AlbaPractice.git`

3. Realizamos cambios en el repositorio clonado y confirmamos estos cambios usando la secuencia de comandos:
`git add ./*` para agregar todos los cambios a seguimiento
`git commit -m"[Aquí va un comentario]"` para confirmar los cambios en nuestra version local

4. Ahora se han realizado cambios en el repositorio original y los necesitamos unir a nuestros cambios en local, para ello usaremos el comando:
`git pull [Aquí va la url del repositorio original] [rama del repositorio original]` esto hará merge en nuestro repositorio local con nuestros cambios

5. Luego subimos los cambios a nuestro repositorio que habíamos obtenido al realizar el fork usando el comando:
`git push origin master` donde origin es nuestro repositorio remoto y master es nuestra rama

6. Ahora tenemos cambios en nuestro repositorio remoto, pero necesitamos que estos cambios estén el repositorio original, para ello le hacemos un pull request desde github
al propietario original:
![Pull Request](/P2/assets/pullRequest.png)

7. Esperamos a que el propietario original acepte nuestros cambios si los considera necesarios en su repositorio.
