FROM miniconda3

LABEL maintainer=@lukasvlcek

RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean -tipsy

CMD ["ipython"]

