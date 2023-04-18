# The Pychain Ledger
This is a Visual Studio file that creates a blackchain ledger as Pychain. This bloackchain ledger is created utilizing streamlit with a user friendly interface. This ledger allows a seller and receiver to conduct financial transactions through Pychain  and is able to validate the transactions integrity. 
---

## Technologies & Libraries

This project utilizes python 3.7 with the following:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [Streamlit](https://github.com/streamlit) - The fastest way to build data apps in Python. Information on github. 

* [Dataclasses](https://docs.python.org/3/library/dataclasses.html) - This module provides a decorator and functions for automatically adding generated special methods.

* [Haslib](https://docs.python.org/3/library/hashlib.html) - This module implements a common interface to many different secure hash and message digest algorithms.

* [Typing](https://docs.python.org/3/library/typing.html) - This module provides runtime support for type hints.

---

## Pre Installation Guide

Prior to running this application, please first install the following dependencies:

```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

---

## Images

# Interface Picture
<img width="880" alt="Interface" src="https://user-images.githubusercontent.com/117557983/232643878-58e948b8-b611-48aa-8940-81a75d5b1526.PNG">

# Ledger Picture
<img width="577" alt="Ledger" src="https://user-images.githubusercontent.com/117557983/232643928-8ee7bc95-757e-4341-9e5f-7019bb567603.PNG">

# Inspector Picture
<img width="239" alt="Inspector" src="https://user-images.githubusercontent.com/117557983/232643949-cdcc1f97-ef7d-4a9a-9f78-db5c72470315.PNG">


## Contributors

DU Starter Code

Ben Lindauer

---

## License

MIT
