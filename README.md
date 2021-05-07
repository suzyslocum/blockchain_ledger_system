# Module 18 Challenge Assignment 
---

## Create a Blockchain Based Ledger System & Web Interface
---

## Overview 
---
  In order to allow our bank's partner banks to conduct financial transactions, we created a Blockshain-based ledger system and user-friendly web interface. The web interface also allows users to verify the validity of the data in the ledger.
  
  ![block_inspector](/Images/block_inspector.jpg)

  Input areas were created so that the user can enter information about the sender, receiver, and amount to transfer, and then submit their transaction. The transaction are logged, and made visible to the user on the web interface.
  
## Results
---

  ![streamlit](/Images/streamlit.jpg)

---

## Technologies

The application is written in Python using Pandas
The following packages are used:

Streamlit - to create the web application [Streamlit documentation](https://docs.streamlit.io/en/stable/)

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

Dataclass - provides a decorator and fucntions for automatically adding special methods to user-defined classes [Dataclass documentation](https://docs.python.org/3/library/dataclasses.html)

datetime - to standardize the format of dates - [datetime documentation](https://docs.python.org/3/library/datetime.html)

Typing - to provide runtime support for type hints - [typing documentation](https://docs.python.org/3/library/typing.html#)

Hashlib - to provide an interface to many secure hash and message algorithms - [hashlib documentation](https://docs.python.org/3/library/hashlib.html)


---

## Installation Guide

Install the Streamlit library using the following command: 'import streamlit as st'

Install the Pandas package using the following command: 'import pandas as pd'

Install the Dataclass library using the following command: 'from dataclasses import dataclass'

Install the datetime library using the following command: 'from datetime import datetime'

Install the typing libraries using the following command: 'from typing import Any, List'

Install the typing package using the following command: 'import hashlib'


--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and launch it using the command 'streamlit run pychain.py' then interact with the web interface that opens.

---

## Contributors
Susannah Slocum 
suzyslocum@gmail.com

---

## License

None
