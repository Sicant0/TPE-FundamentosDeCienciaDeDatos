# TPE-FundamentosDeCienciaDeDatos

## Requisitos

- Python 3.13.15 o superior ([descargar](https://www.python.org/downloads/))
- Git

Para verificar la versión instalada:

```bash
python --version
```

> En Linux/macOS puede que el comando sea `python3` en lugar de `python`.

## Instrucciones de ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/Sicant0/TPE-FundamentosDeCienciaDeDatos.git
cd TPE-FundamentosDeCienciaDeDatos
```

### 2. Crear y activar el entorno virtual

Crear el entorno:

```bash
python -m venv venv
```

Activarlo según el sistema operativo:

**Windows (PowerShell)**
```powershell
venv\Scripts\Activate.ps1
```

**Windows (CMD)**
```cmd
venv\Scripts\activate.bat
```

**Linux / macOS**
```bash
source venv/bin/activate
```

Con el entorno activado, la terminal muestra `(venv)` al inicio de la línea.

### 3. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### Desactivar el entorno

Al terminar de trabajar:

```bash
deactivate
```