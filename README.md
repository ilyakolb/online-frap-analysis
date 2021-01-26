## Online FRAP analysis

Instructions
-----

1. Upload csv file to /data (Upload button top right of notebook)
2. In `online-frap-analysis.ipynb` change the `all_constructs` and `all_cell_num` fields accordingly, i.e. for a file named `myConstruct.001.csv` set:

```
all_constructs = ['myConstruct']
all_cell_num = ['001']

```

3. To change the number of peaks that get averaged, change `num_peaks_to_plot`. Set to 1 to just look at the first curve.
4. Run the notebook. Plots should appear on the bottom.