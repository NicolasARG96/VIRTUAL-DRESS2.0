---
title: Vestidor Virtual Widget
emoji: 👕
colorFrom: purple
colorTo: gray
sdk: gradio
sdk_version: 4.38.1
app_file: app.py
pinned: false
license: apache-2.0
---

# Vestidor Virtual Widget

**Vestidor Virtual Widget** es una adaptación del [Kolors Virtual Try-On](https://github.com/teasai/Kolors-Virtual-Try-On) que ofrece un widget embebible para que las tiendas online permitan a sus clientes probarse virtualmente las prendas. Con este servicio, el usuario sube una fotografía (por ejemplo, de su torso o de la parte inferior) y también la imagen de la prenda (en formato PNG con fondo transparente). En menos de dos minutos podrá visualizar cómo le quedaría la prenda.

## Descripción

El objetivo es brindar una solución simple y eficaz para mejorar la experiencia de compra online y reducir la tasa de devoluciones. El widget se integra mediante un iFrame, de modo que las tiendas no necesiten realizar desarrollos complicados, solo incorporar un pequeño fragmento de código en sus páginas.

## Características

- **Interfaz Sencilla y Responsiva:** Basada en Gradio, facilita una interacción inmediata.
- **Procesamiento Rápido:** Superposición de imágenes y generación de resultados en menos de dos minutos.
- **Embebible:** Se integra en cualquier página web usando un iFrame.
- **Personalizable:** Permite ajustar parámetros (por ejemplo, identificar la prenda o configurar dimensiones).
- **Escalable:** Desplegado en Heroku, adaptable a mayor demanda en el futuro.
- **Licencia Apache 2.0:** Basado en el proyecto original que se distribuye bajo la Apache License 2.0.

## Instalación y Ejecución

### Requisitos
- Python 3.7 (o superior)
- Las dependencias listadas en el archivo `requirements.txt`

### Pasos para Ejecutar Localmente

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/vestidor-virtual-widget.git
   cd vestidor-virtual-widget
