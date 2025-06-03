# streamlit-web-llm

Streamlit component for interacting with LLMs in-browser via WebLLM

## Installation instructions

```sh
pip install streamlit-web-llm
```

## Usage instructions

```python
import streamlit as st

from streamlit_web_llm import streamlit_web_llm

value = streamlit_web_llm()

st.write(value)
```