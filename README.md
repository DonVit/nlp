# NLP - Natural Language Processing Sample

This is based on articale from [here](https://stackabuse.com/implementing-word2vec-with-gensim-library-in-python/)

# Environment Setup

Follow steps [here](https://docs.docker.com/get-started/) and setup docker.
Make sure the following command runs `docker --version`

## Build Docker machine

From command line run `docker build -t nplmachine .`

## Run Docker machine

On windows run `winpty docker run -it nlpmachine`

## Run scriptp

`python3.6 ~/pagescraper.py`

# Issues

If you get the below warning when running the python script then install Visual C++ Build Tools as mentioned [here](https://bebound.github.io/posts/enable-c-extension-for-gensim-on-windows/)
