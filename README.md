# Jupyter Notebook Experiments

I needed to familiarize myself with Jupyter Notebooks - so this is how I did it.

`imdb_experiments.ipynb` is a Jupyter Notebook that will merge together some of the data files freely provided by IMDB. You can get the three necessary data files [from IMDB](https://www.imdb.com/interfaces/). Be sure to read their license agreement because the data is only available for personal, non-commercial use. You'll need:

* title.basics.tsv.gz
* title.principals.tsv.gz
* name.basics.tsv.gz

Unarchive them into the directory alongside `imdb_experiments.ipynb` and rename the `data.tsv` files to match what's in the notebook. For example, `title.principals.tsv`. That _should_ be all you need to run the notebook but.

The notebook creates a Pandas data frame that will let you see who the principal actors in the Avengers are or which movies Johnny Depp was the principal actor. Both of these examples are in the notebook.