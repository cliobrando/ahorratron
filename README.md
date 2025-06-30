# Ahorratrón
> 🐷💾 El chanchito que automatiza tus finanzas

**Ahorratrón** es una herramienta en Python para ayudarte a organizar, convertir y analizar tus datos financieros, especialmente diseñada para procesar cartolas bancarias y de tarjetas de crédito de forma eficiente.

Inspirada en los tradicionales chanchitos de ahorro, esta herramienta busca facilitar el control de gastos, fomentar el ahorro y ayudarte a tomar el control de tus finanzas personales (o familiares).

---

## ✨ Características

- Analiza y convierte cartolas bancarias o de tarjetas (TXT, CSV, XLS).
- Interfaz de línea de comandos (CLI) para exportar datos al formato de [Actual Budget](https://actualbudget.com/).
- Definiciones de campos extensibles para soportar distintos bancos.
- Pensado para facilitar el ahorro, saldar deudas y alcanzar metas financieras.

---

## ⚙️ Instalación

Requiere Python 3.12 o superior.

Clona el repositorio e instala las dependencias:

```bash
pip install .
````

Para desarrollo (con herramientas de prueba):

```bash
pip install .[dev]
```

---

## 🚀 Uso

La herramienta principal es `convert-to-actual`, que convierte tus cartolas al formato compatible con Actual Budget:

```bash
convert-to-actual <archivo_entrada> [opciones]
```

Ejemplo:

```bash
convert-to-actual cartola.txt
```

---

## 🗂️ Estructura del proyecto

* `ahorratron/` – Paquete principal
  * `cli/convert_to_actual.py` – Punto de entrada CLI
  * `parsers/` – Parsers para distintos formatos de archivo
  * `field_definitions/` – Definiciones de campos por banco
* `tests/` – Pruebas unitarias

---

## 🧪 Desarrollo

Para ejecutar los tests:

```bash
pytest
```

---

## 📝 Licencia

Licencia MIT. (Agrega aquí tus datos de autoría o archivo LICENSE si corresponde)

---

> *Hecho con cariño, Python y ganas de ahorrar 🇨🇱*

