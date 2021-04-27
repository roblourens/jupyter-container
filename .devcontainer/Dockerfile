FROM jupyter/scipy-notebook

RUN conda install --quiet --yes -c nglview k3d drawdata vega-datasets altair plotly ipyleaflet bokeh
RUN conda install --quiet --yes -c conda-forge vega_datasets
RUN python -m pip install drawdata

# [Option] Install Node.js
ARG INSTALL_NODE="true"
ARG NODE_VERSION="lts/*"
# RUN if [ "${INSTALL_NODE}" = "true" ]; then . /usr/local/share/nvm/nvm.sh && nvm install ${NODE_VERSION} 2>&1; fi
