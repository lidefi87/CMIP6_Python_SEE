# CMIP6_Python_SEE
Este taller fue creado como parte del **Python Weekend** organizado por la [Sociedad Ecuatoriana de Estadistica](https://www.facebook.com/socecuest/).

Este taller cubre un flujo de trabajo para acceder a modelos acoplados de hielo-oceanos que forman parte de CMIP6 a traves de la coleccion Pangeo Cloud. En este taller tambien muestra como manipular datos, llevar a cabo calculos simples y crear graficos sencillos.

En este cuaderno de Jupyter se utilizan las siguientes bibliotecas:  
- xarray  
- numpy  
- intake  
- cmip6_preprocessing  
- matplotlib
- cmocean
- cartopy
- os

Debido a una gran cantidad de dependencias entre varios paquetes, esta carpeta incluye un archivo yml (llamado `ambiente.yml`) donde se encuentra el ambiente necesario para que este cuaderno funcione de manera adecuada. Pueden instalar este ambiente utilizando la siguiente linea de codigo: `conda env create -f ambiente.yml`. Una vez instalado el ambiente, es necesario activarlo con la siguiente linea de codigo: `conda activate CMIP6_Python`.

Pueden encontrar indicaciones adicionales sobre como crear un ambiente desde un archivo yml en este [vinculo](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).
