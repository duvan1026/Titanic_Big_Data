
** Base de datos sobre pasajeros del Titanic. (Extraidos de Kaggle)
 *** dataset.csv : dispone de toda la información. (entrenamiento)
 *** newData : se desconoce si sobrevio o no al hundimiento. (produccion real)

*** Caractaeristicas 
 *** (edad, género, situación socio-económica,...),
 ***  De tipo cualitativa y cuantitativa.
 *** suficiente registros para entenar modelo predictivo.
 *** datos incompletos.
 *** Mayor informacion de los datos, consultar: Report on the Loss of the ’Titanic’ (S.S.) (1990), British Board of Trade Inquiry Report_(reprint), Gloucester, UK: Allan Sutton Publishing
 
 *** Variable independiente: sobrevivio o no al hundimiento del Titanic.
 
**** Objetivos ****
** Encontrar alguna relación entre los atributos (Variables independientes)
** probabilidad de que un pasajero sobreviva o no al naufragio, por ejemplo, supervivencia por edad, sexo, clase, etc.


**** Actividades ****
* 1. Exploración de los datos (representación grafica de las variables y estudio estadístico de las mismas)
  ** Implementar codigo para análisis descriptivo de los datos (medidas de frecuencia, tendencia, dispersión, posición, distribución).
  ** Comprobar que no haya variables que tengan valores constantes, ya que estas variables perjudican al modelo.
  ** Con este analisis se pueden excluir aquellas variables que no aporten nada al estudio (criterio del experto).
  
* 2. Preprocesamiento (mejoramiento calidad de los datos)
 ** 2.1 Depuración de datos
  *** Deteccion de outliers mediante técnicas estadísticas:
      * implementar codigo para aplciar ténicas estadisticas en la detección de valores sospechosos de ser outliers(ruido) :
    	*  metodo basado en la desviación típica, 
		*  rango intercuartílico y
		*  diagrama de caja