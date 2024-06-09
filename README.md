# mediumblogpost
this repo is to provide the notebooks and code reference for my blogs on medium
From: https://medium.com/@praveenveera92/a-comprehensive-guide-to-multi-modal-rag-on-pdfs-using-gpt4-vision-and-llamaindex-ca7d61218f7d



## Installation
Create a virutal environment using venv or conda (rag_gpt4). Activate this environment and run the following:

```pip install -r requirements.txt```

Note output of pip freeze is in `requirements_YYYY_MM_DD.txt` files

Create the kernel for jupyter notebook to use
```
# name argument should be the name of the environment you created.
python -m ipykernel install --user --name=rag_gpt4v 
```

## Running
In your activated virtual environment, start jupyter
```
jupyter lab
```
Go to http://localhost:8888/lab


### Notebooks
**rag_multimodel_gpt4v.ipynb** - this was the tutorial described in the Medium post.  The original code needed edits in order to get it fully running since llama-index had breaking changes between the blog post and when I ran it on 6/7/24 



