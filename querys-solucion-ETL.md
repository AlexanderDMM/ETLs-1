SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Cities ."Total Population" DESC 
LIMIT 10;

SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Cities ."Total Population" ASC 
LIMIT 10;

SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Concentrations ."overall_aqi" DESC 
LIMIT 10;

querys empleadas para la base de datos ya creada en la cual se pretende encontrar relacion entre cantidad e poblacion y calidad del aire

en el analisis no se logra encontrar relacin alguna entre la cantidad de poblacoin y la calidad del aire ya que la mayoria de ciudades no tienen una alta poblacion y el analisis y la investigacion deverian estar mas enfocado en el tipo de industria en las ciudades que en la cantidad de poblacion 

