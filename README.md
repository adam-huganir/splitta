# splitta for python 3

This adaption was only designed to fix a single use case, so has only been tested on the following methods:

```python
import os
import splitta
from splitta import sbd
model = sbd.load_sbd_model(os.path.join(os.path.dirname(splitta.__file__), "model_nb/"), use_svm=False)
sbd.sbd_text(model, "This is some text to tokenize. This is the second sentence of the tokenized text, at least any M.D. would think so.", False)
```
```
['This is some text to tokenize.',
 'This is the second sentence of the tokenized text, at least any M.D. would think so.']
```

Let me know if there is any other issues and I will take a look.
