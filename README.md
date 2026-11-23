# Thai Address Tagging Notebook

English | [ภาษาไทย](README.th.md)

See how a dictionary-based Thai NLP pipeline turns address text into structured fields without training a model. The notebook shows the intermediate tokens, spelling corrections, and matched address components so you can inspect what changed at each step.

## Explore the notebook

Open [`address_taging.ipynb`](address_taging.ipynb) on GitHub to inspect the saved outputs, or [open it in Google Colab](https://colab.research.google.com/github/ffe111/thaiAddressTag/blob/main/address_taging.ipynb) to experiment. It contains exploratory cells for different PyThaiNLP versions, so use the relevant setup and pipeline cells as a group rather than assuming the entire notebook is one reproducible run. [`addresses.py`](addresses.py) and [`hashmap.py`](hashmap.py) contain reference data used by the project.

## What it can and cannot do

The workflow combines text cleanup, custom tokenization, dictionary-based spelling correction, and reference matching for province, district, subdistrict, and postal code. It does not predict a missing address or verify deliverability. Try it with synthetic inputs, not real contact details.

Want an HTTP endpoint? See the [dictionary-based FastAPI implementation](https://github.com/ffe111/address_detection_api).

<!-- Maintainers: Update the English README first, then mirror the change in README.th.md. -->
