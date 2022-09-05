# Pasantía de Investigación 2022 (Universidad Mayor)

En esta pasantía a cargo del académico Nicolás Amigo Ahumada , se desarrollo de un modelo de Machine Learning para predecir las propiedades mecánicas de materiales.

En el Análisis exploratorio de la base de datos, se decidió trabajar con la Tensión y Compresión por separados, para tener una mejor idea respecto a como se comporta cada variable de manera independiente.
Posteriormente se utilizaron técnicas de Machine Learning (Linear Regression y Ridge) para este caso.

Con Respecto al analisis de las variables si tiene lo siguiente:


- Relaciones inversamente proporcionales entre los percentiles (Cu y Zr)
- Crate no se observan relaciones entre las variables
- A modo general las dimensiones en los experimentos de tensión tienden a tener mayor relación entre ellas. 
	- Lx relación directa con Ly
	- Lx y Ly semejantes respecto a Lz
  
  Por otra parte los experimentos de compresión
	- Se observa una pequeña relación entre Lx y Lz. Ly se nota una tendencia con ruido en los primeros valores
	- Se observa una tendencia con Lx. Con Lz los valores tienden a la baja aproximadamente a los 40 nm.
	- Lz y Lx se observa una tendencia lineal.
- Srate con E se observa una aparente relación raíz cuadrática, sin embargo, los valores anómalos no logran definir bien esta.
- En los gráficos de T en tensión se observa una tendencia a la baja con Smax hasta 3, posteriormente se mantiene bajo, además se observa una tendencia aproximadamente a los 150° (línea media). En el caso de la compresión esta línea se manifiesta a los 300° app.
- Tanto E como Smax se observa una relación lineal.

Se observa que todos los datos añadidos posteriormente de la base de datos Datos_MGs, en su mayoría representan datos anómalos (outliers)
