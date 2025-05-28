# Proyecto - Etapa III - Implementación de Metaheurísticas

Maria Alejandra Londoño <br>
Angélica Ortiz <br>
María José Amorocho

# Descripción
Este repositorio contiene la tercera entrega del proyecto del curso Modelado, Optimización y Simulación. En esta etapa se implementan y reportan soluciones al problema de ruteo de vehículos (CVRP) mediante algoritmos genéticos y herramientas de optimización.

# Estructura del repositorio
MOS-Entrega-3/
├── Entrega 2/                # Notebook y materiales de la entrega anterior
│   └── ...
├── content/                  # Datos de clientes, depósitos, vehículos para cada caso
│   └── base/
│       ├── clients.csv       # Información de clientes
│       ├── depots.csv        # Información de depósitos
│       └── vehicles.csv      # Información de vehículos
├── solutions/                # Scripts de solución
│   └── ...
├── Entrega 3.ipynb           # Notebook principal de la Entrega 3
├── detalles_solucion.txt     # Descripción de resultados
└── README.md                 # Este archivo


# Contenido
- `Entrega 3.ipynb`: notebook donde se implementa un algoritmo genético para CVRP y se realizan visualizaciones de rutas
- `solutions/`: scripts y módulos reutilizables extraídos del notebook.
- `Entrega 2/`: material de la entrega previa para referencia.
- `detalles_solucion.txt`: archivo txt con detalles de solución generado cuando se ejecuta el algorimo genético

# Requisitos
Paquetes principales:
- pandas
- numpy
- matplotlib
- openrouteservice
- folium
-pyomo (opcional, comparativo)

```bash
pip install pandas numpy matplotlib openrouteservice folium jupyter
```