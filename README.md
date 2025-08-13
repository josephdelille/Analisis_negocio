# 📊 Análisis de Negocio: Conversiones y Pruebas A/B

Este proyecto realiza un análisis completo de datos de eventos de usuarios para evaluar conversiones y pruebas A/B.  
Incluye desde la carga y limpieza de datos hasta la aplicación de pruebas estadísticas para validar hipótesis.

## 📂 Estructura del proyecto

- **Parte 1:** Importación y limpieza de datos
  - Conversión de formatos de fecha
  - Creación de columnas derivadas
- **Parte 2:** Análisis exploratorio
  - Conteo de eventos y usuarios únicos
  - Promedio de eventos por usuario
  - Rango de fechas de los datos
- **Parte 3:** Visualización
  - Histogramas de frecuencia de eventos
- **Parte 4:** Pruebas A/B
  - Prueba de hipótesis con `proportions_ztest`

## 🛠️ Requisitos

Este proyecto está desarrollado en **Python 3.x** y utiliza las siguientes librerías:

  ```bash
  pandas
  matplotlib
  statsmodels
  ```

Puedes instalarlas con:
  ```bash
  pip install pandas matplotlib statsmodels
  ```

## 🚀 Uso
- Clona este repositorio o descarga el notebook.

- Asegúrate de tener los datos (logs_exp_us.csv) en la carpeta de trabajo.

- Ejecuta el notebook proyecto.ipynb paso a paso.

Ejemplo para ejecutar:
  ```bash
  jupyter notebook proyecto.ipynb
  ```
## 📈 Resultados esperados
Estadísticas descriptivas del comportamiento de los usuarios.

Gráficos de distribución de eventos en el tiempo.

Validación estadística de diferencias entre grupos A/B.

## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes usarlo, modificarlo y compartirlo libremente.

