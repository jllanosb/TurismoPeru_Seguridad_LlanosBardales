# Turismo Perú – Seguridad

Repositorio de implementación y documentación de mecanismos de **seguridad, administración, respaldo, recuperación, exportación/importación y generación de reportes** para una base de datos orientada a la gestión turística del Perú.

## 1. Nombre del proyecto

**TurismoPeru_Seguridad_LlanosBardales**

Repositorio:

[https://github.com/jllanosb/TurismoPeru_Seguridad_LlanosBardales](https://github.com/jllanosb/TurismoPeru_Seguridad_LlanosBardales?utm_source=chatgpt.com)

---

## 2. Descripción

El proyecto **Turismo Perú – Seguridad** presenta un conjunto de procedimientos y evidencias relacionados con la administración y protección de una base de datos para un sistema de gestión turística.

El repositorio aborda principalmente:

* Administración de usuarios y roles.
* Asignación y control de permisos.
* Exportación e importación de información.
* Copias de seguridad.
* Procedimientos de restauración.
* Generación de reportes.
* Evidencias de ejecución y configuración.

La organización del repositorio permite separar las actividades administrativas, los mecanismos de respaldo y recuperación y los componentes relacionados con la generación de información para análisis y reportes.

El proyecto está estructurado para facilitar la reproducción de las actividades de administración y seguridad de la base de datos, así como la verificación mediante evidencias.

---

## 3. Tecnologías utilizadas

Las tecnologías utilizadas deben corresponder con los componentes incluidos en los scripts y archivos del repositorio.

### Componentes principales

| Tecnología / componente          | Utilización                                          |
| -------------------------------- | ---------------------------------------------------- |
| Sistema gestor de bases de datos | Administración de la base de datos turística         |
| SQL                              | Creación y ejecución de consultas y procedimientos   |
| Usuarios y roles                 | Control de acceso a los recursos de la base de datos |
| Backup                           | Respaldo de la información                           |
| Restore                          | Recuperación de la base de datos                     |
| Exportación / Importación        | Transferencia y recuperación de información          |
| Herramienta de reportes          | Presentación y análisis de información               |
| Git / GitHub                     | Control de versiones y distribución del proyecto     |

> **Nota:** se recomienda verificar en los scripts del repositorio la versión exacta del motor de base de datos y de la herramienta de reportes antes de ejecutar el proyecto en otro entorno.

---

## 4. Requisitos

Para reproducir el proyecto se requiere disponer de:

### Software

* Sistema gestor de bases de datos compatible con los scripts incluidos.
* Herramienta de administración del SGBD.
* Herramienta utilizada para la generación/visualización de reportes.
* Git, si se desea clonar el repositorio.

### Recursos

* Base de datos del proyecto Turismo Perú.
* Permisos administrativos suficientes para crear usuarios, roles y realizar operaciones de respaldo/restauración.
* Espacio suficiente para almacenar archivos de backup y exportaciones.
* Acceso a los archivos incluidos en el repositorio.

### Clonación del repositorio

```bash
git clone https://github.com/jllanosb/TurismoPeru_Seguridad_LlanosBardales.git
```

Ingresar al directorio:

```bash
cd TurismoPeru_Seguridad_LlanosBardales
```

---

## 5. Configuración

La configuración del proyecto debe realizarse antes de ejecutar los scripts de administración, respaldo, restauración o generación de reportes.

### 5.1 Configuración de la base de datos

1. Instalar y configurar el sistema gestor de bases de datos.
2. Crear o disponer de la base de datos correspondiente al proyecto Turismo Perú.
3. Verificar la existencia de las tablas requeridas.
4. Ejecutar los scripts de usuarios y roles.
5. Asignar los permisos correspondientes.
6. Verificar el acceso mediante usuarios con diferentes niveles de privilegio.

### 5.2 Configuración de usuarios y roles

Los procedimientos relacionados con seguridad se encuentran organizados en:

```text
01_Usuarios_Roles/
```

Esta sección contiene los elementos relacionados con la administración de:

* Usuarios.
* Roles.
* Privilegios.
* Permisos de acceso.
* Control de operaciones sobre la base de datos.

Se recomienda ejecutar estos scripts utilizando una cuenta con privilegios administrativos.

### 5.3 Configuración de exportación e importación

Los procedimientos correspondientes se encuentran en:

```text
02_Exportacion_Importacion/
```

Antes de ejecutar los scripts se debe verificar:

* Ruta de origen.
