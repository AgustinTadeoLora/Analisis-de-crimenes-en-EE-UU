# Analisis-de-crimenes-en-EE-UU
<img src="https://github.com/user-attachments/assets/7a8e5585-faa1-407b-bb3f-c917280128ef" alt="Criminalidad EE.UU." style="max-width:100%; height:auto; display:block; margin:auto;" />

El objetivo de este análisis es **entender patrones de criminalidad, identificar tendencias y generar insights útiles para estudios sociales y de seguridad**.  
Se realizó un **análisis exploratorio de datos (EDA)** sobre un dataset de crímenes en Estados Unidos, que contiene 1,000 registros con información sobre:  
- Fecha y hora del crimen  
- Tipo de crimen  
- Género, raza y edad de la víctima  
- Ciudad y estado  

Este proyecto permite descubrir patrones que afectan la criminalidad en distintas zonas del país.  

---

## Tipos de crímenes más frecuentes
1. Allanamiento a la morada (Burglary)  
2. Violencia doméstica (Domestic Violence)  
3. Homicidio (Homicide)  
4. Robo (Robbery)  

---

## Ciudades con mayor número de crímenes
- Houston  
- Dallas  
- New York  

Se añadió granularidad analizando la cantidad de crímenes por **ciudad y por año**.  

## Análisis por año
- Baja en 2020, posiblemente relacionada con la cuarentena.  
- Incremento en 2021 tras la cuarentena, tendencia hasta 2024.  
- En 2025 parece haber una disminución, aunque aún es temprano para establecer patrones definitivos.  

---

## Análisis por horario y día de la semana
- La mayor cantidad de crímenes ocurre los **miércoles y viernes**, especialmente en **horas nocturnas y madrugada**.  
- Al analizar la combinación de día y franja horaria, los promedios se mantienen similares, sin diferencias significativas.  

---

## Análisis por calle
Las calles más afectadas por la criminalidad son:  
- Main St  
- Broadway  

---

## Análisis por género
- Los hombres presentan mayor número de víctimas en delitos como **incendios provocados (Arson)** y **violencia doméstica**.  
- Las mujeres presentan cifras más altas en **allanamiento a la morada**, **posesión de drogas** y **homicidio**.  
- Otros géneros muestran variaciones según el tipo de crimen, especialmente en **allanamiento** y **violencia doméstica**.  

---

## Análisis por raza
- Blancos y negros: pico notable en **allanamiento a la morada**.  
- Asiáticos: sufren más **robos y vandalismo**.  
- Hispanos: mayor incidencia de **homicidios**.  

> Esto sugiere que ciertos tipos de crimen afectan más a determinados grupos raciales, posiblemente por factores socioeconómicos o geográficos, pero **no se establece causalidad**.  

---

## Conclusiones
- Los crímenes más comunes son **allanamiento, violencia doméstica y homicidio**.  
- Las ciudades con mayor criminalidad son **Houston, Dallas y New York**.  
- Los crímenes tienden a ocurrir en **horas nocturnas y madrugada**, especialmente los miércoles y viernes.  
- La distribución por **género y raza** muestra diferencias, indicando que ciertos grupos son más afectados por tipos específicos de crimen.  
- La información por **calle** permite identificar zonas críticas, como **Main St** y **Broadway**.  

Este análisis proporciona un panorama general de la criminalidad en EE. UU., útil para la planificación de **políticas de seguridad** y **estudios sociológicos**.  

---

## Herramientas utilizadas
- Python 🐍  
- Pandas 🐼  
- NumPy ✨  
- Matplotlib 📊  
- Seaborn 🎨  
