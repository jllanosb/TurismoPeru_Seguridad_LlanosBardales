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
* Ruta de destino.
* Permisos de lectura/escritura.
* Existencia de la base de datos.
* Compatibilidad de las estructuras de datos.

### 5.4 Configuración de backups

Los archivos correspondientes a las copias de seguridad se encuentran en:

```text
03_Backup/
```

Se debe verificar previamente:

* Directorio de almacenamiento.
* Permisos de escritura.
* Espacio disponible.
* Nombre de la base de datos.
* Fecha y tipo de backup.

### 5.5 Configuración de reportes

Los componentes relacionados con los reportes se encuentran en:

```text
05_Reportes/
```

La configuración debe contemplar la conexión con la fuente de datos y la actualización de los datos utilizados por los reportes.

---

## 6. Estructura del proyecto

La estructura principal del repositorio es la siguiente:

```text
TurismoPeru_Seguridad_LlanosBardales/
│
├── 01_Usuarios_Roles/
│   └── Scripts relacionados con usuarios y roles
│
├── 02_Exportacion_Importacion/
│   └── Scripts de exportación e importación
│
├── 03_Backup/
│   └── Procedimientos y archivos relacionados con backups
│
├── 05_Reportes/
│   └── Reportes y componentes de visualización
│
├── 06_Evidencias/
│   └── Capturas y evidencias de ejecución
│
└── README.md
```

La organización observada directamente en GitHub incluye estas cinco carpetas principales y el archivo `README.md`.

---

## 7. Scripts disponibles

Los scripts están organizados de acuerdo con la función que desempeñan dentro del proyecto.

### 7.1 Usuarios y roles

Ubicación:

```text
01_Usuarios_Roles/
```

Incluye los scripts destinados a:

* Crear usuarios.
* Crear roles.
* Asignar permisos.
* Revocar permisos.
* Administrar el acceso a los objetos de la base de datos.
* Comprobar los privilegios asignados.

### 7.2 Exportación e importación

Ubicación:

```text
02_Exportacion_Importacion/
```

Incluye procedimientos para:

* Exportar información.
* Importar información.
* Transferir datos.
* Verificar la recuperación de los datos.

### 7.3 Backup

Ubicación:

```text
03_Backup/
```

Incluye procedimientos relacionados con:

* Creación de copias de seguridad.
* Gestión de archivos de backup.
* Recuperación de información.

### 7.4 Reportes

Ubicación:

```text
05_Reportes/
```

Incluye los recursos necesarios para la generación y visualización de reportes.

---

## 8. Procedimiento de restauración

La restauración debe realizarse utilizando una cuenta con privilegios suficientes.

### Procedimiento general

1. Detener las operaciones que puedan modificar la base de datos.
2. Verificar la disponibilidad del archivo de backup.
3. Comprobar la integridad y ubicación del archivo.
4. Identificar la base de datos de destino.
5. Ejecutar el procedimiento de restauración correspondiente.
6. Verificar que la restauración haya finalizado correctamente.
7. Comprobar la existencia de las tablas.
8. Validar la información restaurada.
9. Comprobar los usuarios, roles y permisos.
10. Ejecutar consultas de validación.
11. Verificar finalmente los reportes.

### Validación posterior

Después de restaurar la base de datos se recomienda comprobar:

```text
Base de datos
    ↓
Tablas
    ↓
Datos
    ↓
Relaciones
    ↓
Usuarios
    ↓
Roles
    ↓
Permisos
    ↓
Reportes
```

> El procedimiento concreto de restauración debe ejecutarse según el motor de base de datos y el tipo de backup utilizado por los scripts del directorio `03_Backup/`.

---

## 9. Configuración del reporte

Los recursos asociados a los reportes se encuentran en:

```text
05_Reportes/
```

El procedimiento general consiste en:

### Paso 1. Abrir el reporte

Abrir el archivo de reporte utilizando la herramienta correspondiente.

### Paso 2. Configurar la conexión

Configurar la conexión hacia la base de datos restaurada.

Verificar:

* Servidor.
* Instancia.
* Base de datos.
* Usuario.
* Método de autenticación.

### Paso 3. Actualizar los datos

Ejecutar la actualización del modelo de datos.

```text
Actualizar / Refresh
        ↓
Conectar con la base de datos
        ↓
Obtener información
        ↓
Procesar modelo
        ↓
Actualizar visualizaciones
```

### Paso 4. Validar información

Comprobar que los indicadores, tablas y gráficos presenten información consistente con la base de datos.

---

## 10. Capturas de pantalla

Las evidencias del desarrollo se encuentran en:

```text
06_Evidencias/
```

Esta sección documenta visualmente la ejecución de los procedimientos desarrollados en el proyecto.

Se recomienda organizar las evidencias de acuerdo con las siguientes categorías:

### Administración de usuarios y roles

Capturas correspondientes a:

* Creación de usuarios.
* Creación de roles.
* Asignación de permisos.
* Verificación de permisos.

### Exportación e importación

Capturas correspondientes a:

* Exportación de datos.
* Importación de datos.
* Validación de los datos importados.

### Backup y restauración

Capturas correspondientes a:

* Creación del backup.
* Archivo generado.
* Proceso de restauración.
* Validación posterior a la restauración.

### Reportes

Capturas correspondientes a:

* Conexión con la base de datos.
* Modelo de datos.
* Indicadores.
* Gráficos.
* Reporte final.

---

## 11. Autor

**Dr. Ing. Jaime Llanos Bardales**

Docente Investigador
Ingeniería de Sistemas

GitHub:

[jllanosb](https://github.com/jllanosb?utm_source=chatgpt.com)

---

## Licencia

Este repositorio se encuentra destinado a fines académicos, educativos y de investigación.

---

## Referencia del repositorio

[TurismoPeru_Seguridad_LlanosBardales](https://github.com/jllanosb/TurismoPeru_Seguridad_LlanosBardales?utm_source=chatgpt.com)
