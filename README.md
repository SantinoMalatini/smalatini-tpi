# Trabajo Práctico Integrador - Procesamiento de Ventas de Supermercado

**Alumno:** Santino Malatini

Sistema desarrollado en Python para procesar, ordenar y analizar estadísticas de compras de un supermercado a partir de archivos CSV. 

## Características principales
* **Ordenamiento:** Implementación del algoritmo de Burbuja (Bubble Sort) para organizar los registros.
* **Corte de Control:** Generación de reportes detallados con el total de unidades e importes por sucursal, identificando las compras mayores y menores, junto con un total general unificado.
* **Testing automatizado:** Pruebas unitarias implementada con `pytest` para validar la lógica central y el manejo de archivos.
* **Integración Continua (CI):** Pipeline configurado mediante GitHub Actions para verificar la integridad del código en cada modificación.

## Estructura del Proyecto

```text
├── .github/workflows/ # Configuración del pipeline de CI
├── main.py            # Código principal con la lógica de procesamiento y el menú
├── test_main.py       # Pruebas unitarias
├── requirements.txt   # Dependencias del proyecto
└── README.md          # Documentación del proyecto
```

## Instalación y Configuración
Sigue estos pasos para ejecutar el proyecto en tu entorno local:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/SantinoMalatini/smalatini-tpi.git](https://github.com/SantinoMalatini/smalatini-tpi.git)
cd smalatini-tpi
```

### 2. Crear y activar un entorno virtual
```bash
# Crear el entorno virtual
python -m venv venv

# Activar en Windows:
venv\Scripts\activate

# Activar en macOS/Linux:
source venv/bin/activate
```

### 3. Instalar las dependencias
```bash
pip install -r requirements.txt
```

## Instrucciones de uso

### Ejecutar el programa principal
Para iniciar el menú interactivo y procesar un archivo CSV:
```bash
python main.py
```

### Ejecutar las pruebas unitarias
Para correr los tests automatizados:
```bash
python3 -m pytest test_main.py -v
```

