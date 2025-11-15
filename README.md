# TP Integrador - Configuración de Servidor Debian

## Integrantes del Grupo
- Nombre Integrante 1
- Nombre Integrante 2
- Nombre Integrante 3
- Nombre Integrante 4
- Nombre Integrante 5

## Descripción
Trabajo práctico integrador de Computación Aplicada - Configuración de máquina virtual Debian con servicios SSH, Apache+PHP, MariaDB, particionamiento de disco y script de backup automatizado.

## Estructura del Repositorio
- `/root` - Configuraciones y datos del usuario root
- `/etc` - Configuraciones del sistema (SSH, Apache, MariaDB, fstab, crontab)
- `/opt` - Scripts de backup y automatización
- `/proc` - Información de particiones respaldada
- `/www_dir` - Contenido web
- `/backup_dir` - Backups generados
- `/var` - Logs del sistema (splitteado en partes)

## Componentes Implementados
1. **Configuración de Red**: IP estática en enp0s3
2. **SSH**: Acceso remoto con autenticación por clave pública/privada
3. **Apache + PHP**: Servidor web con soporte PHP 7.3+
4. **MariaDB**: Base de datos con script cargado
5. **Almacenamiento**: Particionamiento de disco adicional (3GB + 6GB)
6. **Backup**: Script automatizado con cron
