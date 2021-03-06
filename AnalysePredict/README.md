# This package contains metric functions and DataFrame handling modules

## Installation

install the development version from GitHub:

```bash
pip install git+https://github.com/Analyse/AnalysePredict
```
## Import packages

import numpy as np
import pandas as pd

## Usage

```python
>>> import AnalysePredict as ap
>>> ap.dictionary_of_metrics([1, 2, 3, 4, 5])
{'mean': 3.0, 'median': 3.0, 'variance': 2.5, 'standard deviation': 1.58, 'min': 1.0, 'max': 5.0}

>>> ss.five_num_summ([1, 2, 3, 4, 5])
{'max': 5.0, 'median': 3.0, 'min': 1.0, 'q1': 1.5, 'q3': 4.5}
```

The code adheres to [PEP8] guidelines.

[PEP8]: https://www.python.org/dev/peps/pep-0008/ "PEP 8 -- Style Guide for Python Code"

## Functions and examples

### Descriptive statistics and measure of variability

| Function                           | Example                                                           |
|------------------------------------|-------------------------------------------------------------------|
| [dictionary of metrics]            | `dictionary_of_metrics([1, 2, 3, 4, 5])`                          |
| [five_num summ]                    | `five_num_summ([1, 2, 3, 4, 5)`                                   |
| [data parser]                      | `data_parser(["2019-11-29 12:50:54"])`                            |

## Spirit and rules

- Everything should be implemented in raw, organic, locally sourced Python.
- Use libraries only if you have to and only when unrelated to the math/statistics. For example, `from functools import reduce` to make `reduce` available for those using python3. That's okay, because it's about making Python work and not about making the stats easier.
- It's okay to use operators and functions if they correspond to regular calculator buttons. 
Anything beyond that, like `mean`, `median`, we have to write ourselves.

Pull requests are welcome!

## Contributors

- Marcus Moeng :https://github.com/marcusmoeng
- Akhona Stefane 
- Lawrence Hlapa 
- Mpho Marufu 
- Pennelope Makhosazane:https://github.com/makhosazane89
