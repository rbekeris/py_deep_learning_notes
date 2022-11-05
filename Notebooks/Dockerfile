FROM tensorflow/tensorflow:latest-gpu
COPY ./Notebooks /Notebooks
WORKDIR /Notebooks
RUN pip install --upgrade -r requirements.txt
EXPOSE 8888
ENTRYPOINT ["jupyter", "notebook","--ip=0.0.0.0","--allow-root","--no-browser"]