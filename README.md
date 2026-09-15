## Hi there 👋

# Portfolio de Prácticas: Copias de Seguridad y Gestión de Correo en Local con Mozilla Thunderbird

**Alumno/a:** Vanesa  
**Fecha:** 15 de septiembre de 2026  
**Módulo / Materia:** Transmisión de Datos y Gestión Documental  

---

## 1. Objetivos de la Práctica

* Configurar una estructura de copia de seguridad local para cuentas de correo electrónico gestionadas mediante el cliente Mozilla Thunderbird.
* Diferenciar entre el almacenamiento en servidor (IMAP/Nube) y el almacenamiento en cliente local.
* Comprender la gestión de espacio de almacenamiento en buzones corporativos o con límite de cuota.

---

## 2. Procedimiento Realizado

1. **Creación de la estructura en Carpetas Locales:**  
   En el panel lateral de Mozilla Thunderbird, dentro de la sección **Carpetas locales**, se creó una carpeta principal con el nombre de la cuenta de correo (`usuario@dominio.com`) para organizar los respaldos.

2. **Generación de subcarpetas espejo:**  
   Dentro de la carpeta de la cuenta creada en local, se agregaron dos subcarpetas esenciales:
   * `Entrada`: para el respaldo de la bandeja de entrada.
   * `Enviados`: para el respaldo de los correos enviados.

3. **Transferencia y respaldo de mensajes:**  
   Se procedió a la selección de mensajes desde el servidor y a la ejecución del comando **Copiar a** hacia la carpeta local correspondiente (`Carpetas locales > usuario@dominio.com > Entrada`), verificando que los mensajes y adjuntos quedaran guardados correctamente en disco.

---

## 3. Análisis Técnico: Copiar vs. Mover

| Operación | Destino del mensaje original | Uso recomendado |
| :--- | :--- | :--- |
| **Copiar** | Permanece en el servidor | Generación de backups preventivos sin alterar el correo en la nube. |
| **Mover** | Se elimina del servidor y pasa a local | Libera espacio en el servidor cuando el buzón está lleno (cuota agotada). |

---

## 4. Conclusión

La utilización de las **Carpetas locales** en Mozilla Thunderbird es una estrategia eficaz tanto para la transmisión segura de datos como para garantizar la continuidad del acceso a la información en entornos laborales o personales, evitando la pérdida de correos por cierre de cuentas o falta de almacenamiento.
