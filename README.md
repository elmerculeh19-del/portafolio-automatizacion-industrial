### Proyecto 1 – HMI de control de tanque con gráfico de nivel (TIA Portal)

- **Contexto:** Proyecto de práctica del curso de programación HMI en TIA Portal (Ingelearn).  
- **Objetivo:** Diseñar una pantalla HMI para supervisar y controlar el llenado y vaciado de un tanque, con visualización dinámica del nivel y alarmas de proceso.

**Herramientas utilizadas**

- TIA Portal (SIMATIC HMI Comfort Panel).  
- PLC Siemens S7‑1200 (configurado en el proyecto).  

**Descripción del proyecto**

- Diseño de una **pantalla principal** que incluye:
  - Representación gráfica del tanque con indicador de nivel dinámico.
  - Señalización de estados: *Rebase, Alarma, Lleno y Vacío*.
  - Gráfico de tendencias en tiempo real del nivel del tanque.
- Implementación de controles de operación:
  - Botones de **Arranque** y **Parada** del sistema de llenado.
  - Botón de **Conmutar vaciado** para activar el vaciado del tanque.
  - Ajuste del **setpoint de velocidad del motor** mediante un deslizador (slider).
- Configuración de **tags HMI** enlazados con variables del PLC para:
  - Nivel del tanque.
  - Estados de alarmas y límites.
  - Comandos de arranque/parada y vaciado.
- Uso de elementos gráficos de TIA Portal:
  - Animaciones para el nivel del tanque.
  - Indicadores luminosos para alarmas y estados.
  - Gráfico de tendencias para el historial de nivel.

**Lo que aprendí**

- Crear pantallas HMI con elementos gráficos dinámicos (tanque y nivel).  
- Configurar gráficos de tendencias para monitorizar variables de proceso.  
- Gestionar alarmas visuales a partir de límites de proceso.  
- Enlazar correctamente tags entre PLC y HMI en TIA Portal.

**Capturas de pantalla**

Las imágenes del proyecto están en la carpeta `img/` de este repositorio:

![Pantalla principal – HMI tanque](img/hmi_tanque_pantalla_principal.png)
