# GIT. CONTROL DE VERSIONES

## TAREA 4.12. GIT. CREANDO RAMAS.  

En esta práctica vas a crear y configurar nuevas ramas, las mezclarás (Merge) y realizarás commits sobre ellas. Para ello usarás el flujo de trabajo GitFlow.

GitFlow fue publicado por primera vez y popularizado por Vincent Driessen en nvie. El flujo de trabajo de Gitflow define un modelo estricto de ramificación diseñado alrededor de la publicación del proyecto. Proporciona un marco sólido para gestionar proyectos más grandes.

1. Crea en este repositorio el esquema de ramas que se adjunta:
    - Las ramas utilizadas son: 
        - Ramas de desarrollo y maestras.
        - Ramas de función.
        - Ramas de publicación.
        - Ramas de corrección.  

2. El flujo general de Gitflow es el siguiente:
    - Se crea una rama de desarrollo a partir de la maestra.
    - Una rama de publicación se crea a partir de la de desarrollo.
    - Las ramas de función se crean a partir de la de desarrollo.
    - Cuando una función está completa, se fusiona en la rama de desarrollo.
    - Cuando la rama de publicación está lista, se fusiona en la de desarrollo y la maestra.
    - Si se detecta una incidencia en la maestra, se crea una rama de corrección a partir de la maestra.
    - Una vez que la corrección está completa, se fusiona tanto con la de desarrollo como con la maestra.  

3. Adjunta un pantallazo del comando git log --oneline --decorate --graph --all.  
    ![Comando Git log](img/Captura1.JPG)

4. Una vez subido el repositorio, adjunta un pantallazo del apartado de GitHub "Insights"/"Network graph".  
    ![Insights/Network graph](img/Captura2.JPG)