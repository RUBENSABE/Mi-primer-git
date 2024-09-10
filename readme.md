#COMANDOS GIT

0. Configuracion de GIT en nuestro sistema operativo (git config --global user.name && user.mail)
1. git init: Inicializa git en nuestro proyecto (solo se ejecuta una vez)
2. git status: Te menciona la situacion de tu proceso de GIT
3. git add . : Pasa cambio de working directory a staging area
4. git commit -m "Mi primer commit" : Pasa cambios de staging area a repository
5. git log: Te muestra todos los commits

#BRANCH
1. Main (Production) : El ambiente del cliente
2. Desarrollo(Dev) : Nuestro ambiente para trabajar
3. QA(Calidad del codigo): Se prueba los desarrollos
4. UAT(Pre Produccion) : Antes de mandar a produccion

1(Desarrollo) => 2(QA) => 3(UAT) => 4(PRODUCTION)