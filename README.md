# Proyecto_Python_Galvis_Pamela

> **Nota:** Este es un proyecto académico realizado con la finalidad de consolidar los conocimientos adquiridos en el módulo de Python.

Una compañía de transportes y logística desea desarrollar un programa en Python que permita llevar el registro y control de todos los envíos, recepción y reparto de paquetes. Este sistema facilita la gestión integral de clientes, envíos y el seguimiento de paquetes, optimizando la operación y mejorando la experiencia tanto de empleados como de clientes.

---

## Tabla de Contenidos

- [Descripción General](#descripción-general)
- [Funcionalidades Principales](#funcionalidades-principales)
- [Historias de Usuario](#historias-de-usuario)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación](#instalación)
- [Ejemplo de Uso](#ejemplo-de-uso)
- [Enlace del Repositorio](#enlace-del-repositorio)

---

## Descripción General

Este proyecto permite registrar y controlar todos los envíos, recepción y reparto de paquetes de una empresa de transportes y logística. Incluye módulos para la gestión de clientes, registro de envíos, seguimiento de paquetes, notificaciones y generación de informes.

---

## Funcionalidades Principales

1. **Registro de Clientes:**  
   Permite registrar y actualizar la información de los clientes que realizan envíos.

2. **Registro de Envíos:**  
   Permite registrar la información de cada envío, generando automáticamente un número de guía único.

3. **Seguimiento de Paquetes:**  
   Permite a los destinatarios y clientes verificar el estado de sus envíos usando el número de guía.

4. **Actualización de Información de Clientes:**  
   Los clientes pueden actualizar su información personal para asegurar la correcta entrega de sus envíos.

5. **Notificaciones y Gestión de Problemas:**  
   El sistema notifica automáticamente a los empleados en caso de problemas con un envío.

6. **Generación de Informes:**  
   Los administradores pueden generar informes sobre el volumen de envíos, tiempos de entrega y rendimiento del servicio.

7. **Seguimiento de Múltiples Envíos:**  
   Los clientes pueden realizar el seguimiento de varios envíos simultáneamente.

8. **Registro Detallado de Envíos:**  
   El personal puede ingresar información detallada de cada envío para un seguimiento preciso.

---

## Historias de Usuario

- Como destinatario, quiero ingresar el número de guía para verificar el estado y ubicación de mi envío.
- Como empleado, quiero que el sistema genere automáticamente un número de guía único para cada envío.
- Como cliente, quiero poder actualizar mi información personal para asegurar la correcta entrega de mis envíos.
- Como empleado, quiero recibir notificaciones automáticas ante problemas con un envío.
- Como administrador, quiero generar informes sobre el volumen de envíos y tiempos de entrega.
- Como cliente, quiero realizar seguimiento de múltiples envíos a la vez.
- Como empleado, quiero registrar nuevos clientes en el sistema.
- Como empleado, quiero ingresar información detallada de los envíos.

---

## Estructura del Proyecto

- **main.py**: Archivo principal de ejecución.
- **clientes.py**: Módulo para la gestión de clientes.
- **envios.py**: Módulo para la gestión de envíos.
- **seguimiento.py**: Módulo para el seguimiento de paquetes.
- **utils.py**: Funciones utilitarias y de apoyo.
- **data/clientes.json**: Almacena la información de los clientes.
- **data/envios.json**: Almacena la información de los envíos.

---

## Instalación

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/pamelamichellga01/Proyecto_Python_Galvis_Pamela.git
   cd Proyecto_Python_Galvis_Pamela
   ```

2. **(Opcional) Crear y activar un entorno virtual:**

   ```bash
   python -m venv venv
   # En Windows
   venv\Scripts\activate
   # En Linux/Mac
   source venv/bin/activate
   ```

3. **Instalar dependencias (si aplica):**

   Este proyecto utiliza solo la biblioteca estándar de Python, por lo que no requiere instalación de paquetes adicionales. Si en el futuro se agregan dependencias, puedes instalarlas con:

   ```bash
   pip install -r requirements.txt
   ```

---

## Ejemplo de Uso

1. **Ejecutar el programa principal:**

   ```bash
   python main.py
   ```

2. **Flujo típico de uso:**

   - Registrar un nuevo cliente ingresando sus datos personales.
   - Registrar un nuevo envío, seleccionando el remitente (cliente ya registrado) y proporcionando los datos del destinatario.
   - El sistema generará automáticamente un número de guía para el envío.
   - Consultar el estado de un paquete ingresando el número de guía en el módulo de seguimiento.
   - Actualizar la información de un cliente si es necesario.
   - Los empleados pueden consultar informes y recibir notificaciones sobre el estado de los envíos.

---

## Enlace del Repositorio

Puedes clonar o consultar el repositorio en el siguiente enlace:  
[https://github.com/pamelamichellga01/Proyecto_Python_Galvis_Pamela.git](https://github.com/pamelamichellga01/Proyecto_Python_Galvis_Pamela.git)

---

