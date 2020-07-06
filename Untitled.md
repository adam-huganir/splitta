```python
import gc
import os
import re
import json

import urllib3
from tqdm.autonotebook import tqdm

import spacy
import pandas as pd
from nltk import sent_tokenize
from redshred import SimpleAPI

from dataclasses import dataclass

urllib3.disable_warnings()
```

```python
@dataclass
class GenericData:
    pass


@dataclass
class GraphData:
#     g: Graph
    n: GenericData = GenericData()
    r: GenericData = GenericData()


```

```python

```
