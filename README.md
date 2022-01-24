# Installation
```
conda create -n rapids-21.12 -c rapidsai -c nvidia -c conda-forge rapids=21.12 python=3.8 cudatoolkit=11.5 \
pyarrow jupyterlab shap=0.39 conda-pack pyspark category_encoders dask-ml seaborn holoviews sdv 
```

# Running Workloads
Run each numbered notebook sequentially, starting with the lowest number. For numbers with letters such as a/b, select one notebook to run and proceed to the next step. These splits correspond to different implementations of performing similar operations.
