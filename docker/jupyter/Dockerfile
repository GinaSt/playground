FROM jupyter/tensorflow-notebook
MAINTAINER gina <ginastavropoulou@gmail.com>
RUN conda install -c anaconda psycopg2 
RUN conda install -y -c conda-forge geopy
RUN conda install -y -c conda-forge geopandas
RUN conda install folium -y -c conda-forge
RUN pip install --upgrade pip
RUN pip install opencv-python
RUN pip install opencv-contrib-python
CMD jupyter notebook --no-browser --ip="*" --NotebookApp.iopub_data_rate_limit=1.0e10 --allow-root 
