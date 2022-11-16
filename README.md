# iitj-sde-project-neurallog
iitj-sde-project-neurallog

## Summary 

The work done in the report is around using semantic based attention models to understand the context of the sentences, and use the same for fetching anomalies from the logs data, which are primarily unstructured by nature. 
Data is loaded using pytorch data loaders, which can easily handle more than memory data size. They send the data as a stream for batch processing in neural networks. From application processing point of view, cleaning of the texts using python string modules. 
The data formatted is passed through Bert 512 transformer model, which understands the contextual information, with window size being of 20. 

## Get started

- `pip install pipenv`
- `git clone <url>`
- `cd <project>`
- `pipenv shell`
- `pipenv install`
- `python main.py`
