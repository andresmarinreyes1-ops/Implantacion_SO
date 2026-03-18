# Implantacion_SO
Documentacion Sistemas Operativos
1- APUNTES.	4
2- DOCUMENTACIÓN	6
3- CREAR CARPETAS Y ORDENARLAS	7
4- Asignar usuarios a grupos (usermod -aG)	10
5- Verificar los grupos (id)	10
1. ls -la	10
2. sudo chmod 640 [archivo] (El Modo Numérico)	10
3. sudo chmod u=rw,g=r,o= [archivo] (El Modo Letras)	11
6- Consultar usuarios	11
7- Cambiar el Propietario (chown)	12
8- Cambiar el Grupo (chgrp)	12
1. Cambios masivos con -R (Recursivo)	12
2. El comando "Buscador" (find)	13
3. El Nuevo Home (chmod 770)	13
9- El comando tee (La franja negra)	13
1. El análisis de /etc/passwd (La lista larga)	14
2. La diferencia entre passwd e id	14
3. El bit de "Grupo Colaborativo" (Permiso 2770)	15
4. Probar como otro usuario sin cerrar sesión (su -c)	15
10. EJERCICIO  REESTRUCTURACIÓN DE PERMISOS	16
Gestión de Usuarios y Grupos	16
Acceso a Directorios	16
11- BÚSQUEDA DE ARCHIVOS	20
1. ¿Qué buscamos exactamente?	20
2. Los componentes del comando	20
3. La diferencia entre las rutas	20
12-LISTADO DE DIRECTORIOS	21
13- GESTIÓN DE USUARIOS AVANZADOS	21
14- COMANDOS DE VERIFICACIÓN E INSPECCIÓN	22
15- GESTIÓN Y MODIFICACIÓN DE USUARIOS EXISTENTES	22
16- GESTIÓN DE DIRECTORIOS Y PROPIEDADES	23
17- Seguridad de Contraseñas y Bloqueo	24
18- MODIFICACION DE USUARIOS	25
19- Extracción y Auditoría de Usuarios	26
20- Gestión Avanzada de Grupos	27
21- Membresías y Grupos Colaborativos	28
21- STICKY BIT	29
22- GESTIÓN DEL CICLO DE VIDA DE UN USUARIO	31
2. Gestión de Usuarios: Creación Segura (Laura)	31
El objetivo de esta sección es crear un nuevo usuario y, al mismo tiempo, establecer una política de seguridad que fuerce el cambio de contraseña en el primer inicio de sesión. El administrador asigna una clave temporal, y el usuario debe sustituirla inmediatamente por una privada.Comandos de Creación y Configuración	31
Comando: sudo useradd -m -s /bin/bash -G dev laura	31
Esta sección valida el correcto funcionamiento de las políticas de seguridad y los permisos configurados previamente en el entorno real del servidor.Comprobaciones Prácticas	32
Acción de Verificación: su - laura	32
23- Configuración de Entornos y Auditoría de Sistemas	33
24- NANO COMO EDITOR DE TEXTO
