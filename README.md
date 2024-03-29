# CMIP6_Python_SEE

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lidefi87/CMIP6_Python_SEE.git/HEAD)

Este taller fue creado como parte del **Python Weekend** organizado por la [Sociedad Ecuatoriana de Estadistica](https://www.facebook.com/socecuest/).

Este taller cubre un flujo de trabajo para acceder a modelos acoplados de hielo-oceanos que forman parte de CMIP6 a traves de la coleccion Pangeo Cloud. En este taller tambien muestra como manipular datos, llevar a cabo calculos simples y crear graficos sencillos.

En este cuaderno de Jupyter se utilizan las siguientes bibliotecas:  
- xarray  
- numpy  
- intake  
- xmip  
- matplotlib
- cmocean
- cartopy
- os

Debido a una gran cantidad de dependencias entre varios paquetes, esta carpeta incluye un archivo yml (llamado `environment.yml`) donde se encuentra el ambiente necesario para que este cuaderno funcione de manera adecuada. Pueden instalar este ambiente utilizando la siguiente linea de codigo: `conda env create -f environment.yml`. Una vez instalado el ambiente, es necesario activarlo con la siguiente linea de codigo: `conda activate CMIP6_Python`.

Pueden encontrar indicaciones adicionales sobre como crear un ambiente desde un archivo `yml` en este [vinculo](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

Si prefieres, puedes acceder este repositorio desde NBViewer [aqui](https://nbviewer.org/github/lidefi87/CMIP6_Python_SEE/tree/main/).
  
*Notas:*  
La biblioteca `cmip6_preprocessing` fue renombrada a `xmip`. Este cuaderno y todos los archivos de soporte han sido actualizados para reflejar este cambio. 