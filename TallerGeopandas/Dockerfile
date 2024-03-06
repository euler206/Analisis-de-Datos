FROM  jupyter/scipy-notebook

RUN pip install numpy matplotlib geopandas mapclassify seaborn

COPY datasets /datasets
COPY precios_gasolina_jupyter.ipynb shapely_taller.ipynb .
