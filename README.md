# Asistente PPC Amazon — Versión V4 🚀

¡Bienvenido al **Asistente PPC Amazon (V4)**! Esta es una herramienta interactiva, completamente **offline y estática (HTML/CSS/JS)**, diseñada para optimizar tus campañas de publicidad en Amazon mediante el análisis inteligente de reportes de términos de búsqueda (*Search Term Reports*).

Esta versión V4 implementa lógicas de negocio avanzadas para maximizar tus ventas, automatizar la graduación de términos ganadores y proteger de forma activa tu posicionamiento histórico.

---

## ✨ Características Principales (V4)

### 1. 🚀 Graduación de Palabras Clave Segmentada
* **Manual Amplia (Broad) — 1 Venta:** Si un término consigue exactamente **1 venta**, se gradúa a una campaña **Manual Amplia** para seguir descubriendo palabras clave de cola larga (*long-tail*). Se recomienda **mantener activo** el término en la campaña automática original para no cortar el flujo de tráfico inicial.
* **Manual Exacta — 2+ Ventas:** Si un término acumula **2 o más ventas**, se gradúa directamente a una campaña **Manual Exacta**. 
  * Si el ACOS es excelente (menor o igual a tu ACOS objetivo), se sugiere incrementar el bid un **+15%** para acelerar conversiones rentables.
  * Se aconseja añadir como negativa exacta en la campaña automática solo una vez que la campaña manual empiece a capturar tráfico.

### 2. 🛡️ Escudo Anti-Sobrenegativización (Conversion Shield)
* **Protección de Conversiones:** Protege de forma activa cualquier término que tenga **1 o más ventas** pero presente un ACOS elevado.
* **Reducción de Bid en lugar de Negación:** En lugar de recomendar la negación del término (lo cual destruiría tu indexación orgánica y tu relevancia histórica de conversión), el asistente activa el **Escudo de Conversión**, estableciendo el estado del término como **Bajar bid** y recomendando una reducción controlada del **-20%** en el bid.
* **Panel Educativo:** Incluye una sección visual interactiva en la interfaz que explica detalladamente por qué la sobrenegativización daña el rendimiento de tus campañas en Amazon a largo plazo.

### 3. 🎨 Interfaz Premium Dark-Glassmorphism
* **Diseño Moderno:** Fondo difuminado estilo cristal, sombras suaves y contrastes optimizados con acentos vibrantes que ofrecen una experiencia visualmente impactante.
* **Score de Salud Dinámico (Health Gauge):** Un medidor circular animado en SVG que evalúa la salud publicitaria de tu cuenta en tiempo real, penalizando clics desperdiciados y CTR bajos para alertarte sobre posibles fugas de presupuesto.
* **Bandeja de Prioridades Ejecutivas:** Agrupación visual de recomendaciones por orden de prioridad para agilizar tu toma de decisiones diaria (Negativas urgentes, Ajustes de bid protegidos, Graduaciones a Exacta, Graduaciones a Amplia y Optimizaciones de CTR).

---

## 🛠️ Cómo Utilizar el Asistente

### Opción A: Uso Local (Offline)
1. Descarga o clona este repositorio.
2. Haz doble clic sobre el archivo `index.html` (o `agente-ppc-amazon-v4.html`) para abrirlo en cualquier navegador web moderno (Chrome, Safari, Firefox, Edge).
3. **No requiere conexión a Internet ni instalación de dependencias.** Es 100% privado y seguro, tus datos no salen de tu ordenador.

### Opción B: Ejecución en la Nube (GitHub Pages)
Este repositorio está estructurado para ejecutarse directamente en la nube utilizando **GitHub Pages**:
1. Entra a tu repositorio en GitHub.
2. Ve a **Settings** (Configuración) > **Pages**.
3. En la sección **Build and deployment**, selecciona la rama `main` y la carpeta `/ (root)`.
4. Haz clic en **Save** (Guardar).
5. En un par de minutos, GitHub te proporcionará una URL pública (ej. `https://tu-usuario.github.io/PPC-AMAZON/`) para que puedas usar tu asistente desde cualquier dispositivo (incluido el móvil) sin necesidad de descargar archivos.

---

## 📋 Requisitos del Reporte de Amazon
Para realizar el análisis, exporta tu reporte de términos de búsqueda desde tu consola de Amazon Advertising en formato **CSV**. La herramienta es compatible con:
* **Sponsored Products (SP)**
* **Sponsored Brands (SB)**
* **Sponsored Display (SD)**

---

## ⚖️ Licencia y Privacidad
* **Privacidad 100% Garantizada:** El procesamiento de los datos CSV se realiza en su totalidad en el cliente (dentro de tu propio navegador web). Ningún dato se sube a servidores externos.
* Desarrollado con pasión para vendedores de Amazon de alto rendimiento.
