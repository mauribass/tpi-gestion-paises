# tpi-gestion-paises
Sistema de gestión de datos de países en Python — TPI Programación 1 UTN

---

## Descripción

Sistema de consola desarrollado en Python que permite gestionar información sobre países del mundo. Permite cargar datos desde un archivo CSV y realizar operaciones de búsqueda, filtrado, ordenamiento y estadísticas sobre el dataset.

---

## Integrantes

| Nombre | Legajo |
|--------|--------|
| Basaure Mauricio Ariel | [Legajo] |
| [Nombre Integrante 2] | [Legajo] |

---

## Estructura del Proyecto

```
tpi-gestion-paises/
├── tpi_gestion_paises.py   # Código fuente principal
├── paises.csv              # Dataset base de países
├── README.md               # Este archivo
└── Informe_TPI.pdf         # Documentación académica
```

---

## Instrucciones de Uso

### Requisitos

- Python 3.x instalado
- No requiere librerías externas (solo el módulo `csv` de la biblioteca estándar)

### Ejecución

```bash
python tpi_gestion_paises.py
```

Al iniciar, el programa crea automáticamente el archivo `paises.csv` con el dataset base si no existe, carga los datos y muestra el menú principal.

---

## Menú Principal

```
==================================================
  SISTEMA DE GESTIÓN DE PAÍSES
==================================================
1. Ver todos los países
2. Agregar país
3. Actualizar país
4. Buscar país
5. Filtrar países
6. Ordenar países
7. Estadísticas
0. Salir
==================================================
```

---

## Ejemplos de Uso

### Agregar un país
```
---- Nuevo país ----
Nombre del nuevo país: Portugal
Numero de población: 10300000
Superficie km²: 92212
Continente al que pertenece Portugal: Europa
'Portugal' agregado correctamente.
```

### Buscar un país (coincidencia parcial)
```
---- Busqueda en el sistema ----
Que pais desea buscar?: ar
2 resultado(s) encontrado(s):
País: Argentina | Población: 45376763 personas | Superficie: 2780400km² | Continente: América
País: Brasil | Población: 213993437 personas | Superficie: 8515767km² | Continente: América
```

### Filtrar por continente
```
---- Filtrar Países ----
Ingresá el continente a filtrar: Asia
3 país/es encontrado/s en Asia:
País: China | Población: 1412600000 personas | Superficie: 9596960km² | Continente: Asia
País: India | Población: 1380004385 personas | Superficie: 3287263km² | Continente: Asia
País: Japón | Población: 125800000 personas | Superficie: 377975km² | Continente: Asia
```

### Ordenar por población descendente
```
---- Ordenar Países ----
1. Por nombre  2. Por población  3. Por superficie
Seleccione un criterio: 2
1. Ascendente  2. Descendente
Seleccione el orden: 2

Países ordenados por poblacion (descendente):
País: China | Población: 1412600000 personas | ...
País: India | Población: 1380004385 personas | ...
...
```

### Estadísticas
```
---- Estadísticas ----
País con mayor población: China (1412600000 personas)
País con menor población: Chile (19458310 personas)

Promedio de población: 283715034 personas
Promedio de superficie: 2866614 km²

Cantidad de países por continente:
  América: 4 país/es
  Europa: 3 país/es
  Asia: 3 país/es
  África: 2 país/es
  Oceanía: 1 país/es
```

---

## Dataset Base

El archivo `paises.csv` incluye 13 países con el siguiente formato:

```
nombre,poblacion,superficie,continente
Argentina,45376763,2780400,América
Brasil,213993437,8515767,América
...
```

---

## Enlaces

- **Repositorio:** https://github.com/mauribass/tpi-gestion-paises
- **Video demostrativo:** [Insertar URL del video]
- **Documentación PDF:** [Insertar URL o ver archivo en la raíz del repositorio]

---

## Tecnologías utilizadas

- Python 3.x
- Módulo `csv` (biblioteca estándar)
