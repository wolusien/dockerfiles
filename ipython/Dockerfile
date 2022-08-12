FROM miniconda3
LABEL maintainer=@joshuacook
RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean --all -f
CMD ["ipython"]