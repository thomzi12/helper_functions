# Helper Scripts
Python, etc. files and notes related to data analyst work

Some Pandas notes: 

- To create multiple columns when doing a group by, use `df.groupby([cols]).apply(lambda x: pd.Series({"column": function(x)})).reset_index()` 

Some matplotlib notes: 

- to set the size on a plot in a Jupyter Notebook, use `plt.figure(figsize = (x,y))`
