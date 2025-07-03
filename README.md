# Proyecto ML Clusterización

Este proyecto contiene implementaciones y análisis de diferentes algoritmos de clusterización para Machine Learning.

## Configuración del Entorno Virtual

### Entorno ya creado

El entorno virtual ya está configurado en la carpeta `.venv` con Python 3.12.10.

### Activar el entorno virtual

**En Windows (PowerShell):**

```powershell
.venv\Scripts\Activate.ps1
```

**En Windows (Command Prompt):**

```cmd
.venv\Scripts\activate.bat
```

### Verificar que el entorno está activo

Cuando el entorno esté activo, verás `(.venv)` al inicio de tu línea de comandos.

### Instalar dependencias

Las dependencias ya están instaladas, pero si necesitas reinstalarlas:

```bash
pip install -r requirements.txt
```

### Desactivar el entorno virtual

```bash
deactivate
```

## Librerías Instaladas

- **pandas**: Manipulación y análisis de datos
- **numpy**: Computación numérica
- **matplotlib**: Visualización de datos
- **seaborn**: Visualización estadística
- **scikit-learn**: Algoritmos de Machine Learning
- **scipy**: Computación científica
- **jupyter**: Notebooks interactivos
- **ipykernel**: Kernel de Python para Jupyter

## Algoritmos de Clusterización Incluidos

1. **K-Means**: Algoritmo de particionamiento
2. **Clustering Jerárquico**: Agrupamiento aglomerativo
3. **DBSCAN**: Clustering basado en densidad
4. **Mean Shift**: Algoritmo de desplazamiento medio

## Uso

1. Activa el entorno virtual
2. Abre Jupyter Notebook o usa VS Code
3. Ejecuta el notebook `Clusterización teoría.ipynb`

## Datos

El proyecto utiliza el dataset `Mall_Customers.csv` para demostrar los diferentes algoritmos de clusterización.
