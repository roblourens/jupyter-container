FROM jupyter/scipy-notebook

RUN python -m pip install nglview k3d drawdata vega-datasets altair plotly ipyleaflet bokeh vega_datasets drawdata 

# [Option] Install Node.js
ARG INSTALL_NODE="true"
ARG NODE_VERSION="lts/*"
# RUN if [ "${INSTALL_NODE}" = "true" ]; then . /usr/local/share/nvm/nvm.sh && nvm install ${NODE_VERSION} 2>&1; fi
