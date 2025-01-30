Dataset **Urban Street: Leaf Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI3MjRfVXJiYW4gU3RyZWV0OiBMZWFmIENsYXNzaWZpY2F0aW9uL3VyYmFuLXN0cmVldDotbGVhZi1jbGFzc2lmaWNhdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJJUXMvYkJ4NjYxV2gzSHNRN3V0blF6RDZJU2N0VTdRN2pIZmFhaHlWUnRBPSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Urban Street: Leaf Classification', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/erickendric/tree-dataset-of-urban-street-classification-leaf).