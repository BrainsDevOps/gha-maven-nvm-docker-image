# Imagen Docker con maven y node (nvm)

Este repositorio contiene un ejemplo de cómo construir un imagen docker y subirla a dockerhub, aprovechando acciones de docker para añadir labels y tags en base a metainformación de git.

## Contexto
Este repositorio forma parte del contenido de mis cursos de udemy:
* [Domina Github Actions](https://www.udemy.com/course/domina-github-actions/?referralCode=CBFBAF72C38BE758CFE1)
* [Domina SonarQube](https://www.udemy.com/course/domina-sonarqube/?referralCode=EF59257E7D8DC3026D6D)

Si te interesa aprender más sobre SonarQube o Github Actions, Puedes ver si hay promociones vigentes para los cursos en la sección de cursos de [devopsbrains.com](https://devopsbrains.com/cursos/)


## Prerrequisitos
* Cuenta de Github con Github Actions habilitado
* Cuenta de dockerhub

# Uso del ejemplo
* Crea un fork de este repositorio en tu cuenta de Github
* Clona el código en local y ajusta la configuración con tu cuenta de dockerhub / Dockerfile
* Crea un PAT en Dockerhub para identificarte con los permisos necesarios
* Añade los secretos necesarios en Github
* La acción se lanza haciendo push de un tag con el formato "v*.*.*"