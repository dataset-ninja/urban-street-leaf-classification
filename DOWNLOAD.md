Dataset **Urban Street: Leaf Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/q/T/Jm/lo5yVMOVf8D0m89r3JO4gRr1Cqogxdm28hhU1RJnOgYm4Sv9s9NwAGBhWcID35mk6FQ4CHSXXEe1d7WJBufZDzqkbbvPlBWfplzIVDuM5cs7VqxUHi4ktupX9nhF.tar)

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

