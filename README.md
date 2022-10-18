# Introducción a WCF

### Objetivo: Identificar los pasos iniciales para trabajar con servicios WCF en el desarrollo de programas con comunicación en red

### Descripción del repositorio
        * La carpeta de "EjemploDelProfesor" consta de dos proyectos, en el de "MessageService.sln" actua como
        el servidor, tiene dos soluciones la de "Host" que nos ayuda para levantar el servicio y escichar en la red y la de
        MessafeService donde la IUserManager.cs es una interfaz que nos permite utilizarla como "contratos" que el cliente accedera
        de esta manera, mientras que MessageService nos permite mostrar la información de los usuarios de acuerdo a la Base de datos,
        el otro proyecto es "SimpleClient" este guarda la referencia al servidor utilizando RPC, al igual aqui se implementa la GUI
        donde un boton nos estará mando la informacion que tiene "MessageService.cs"

        * La carpeta de TcpBiding es del video de **C# SELF HOST WCF TCP/IP SERVICE IN 20 MINUTES**

### Modo de ejecución
        En el caso de la carpeta "EjemploDelProfesor" es necesario ejecutar el proyecto de "MessageService.sln" como Administrador
    
#### Preguntas de apoyo
        - ¿Cuál es el objetivo de utilizar WCF en la construcción de aplicaciones?
        - ¿Qué es un Contract en WCF y para qué sirve?
        - ¿Qué es un endpoint en WCF?
        - ¿Qué es un behaviour en el contexto de Service Runtime y por qué es necesario definirlos?
        - ¿Cómo podemos hacer la activación de un servicio y el proceso de hosting para poder consumir la funcionalidad en la red?

### Bibliografías:   
    - WCF Quick Guide (https://www.tutorialspoint.com/wcf/wcf_quick_guide.htm)
    - C# SELF HOST WCF TCP/IP SERVICE IN 20 MINUTES (https://www.youtube.com/watch?v=StvQQCY_LNE)