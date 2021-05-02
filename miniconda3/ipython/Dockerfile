FROM miniconda3
LABEL maintainer=@tnguyen2921
RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean -tipsy
CMD ["ipython"]