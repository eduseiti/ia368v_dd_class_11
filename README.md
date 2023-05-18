# ia368v_dd_class_11
Multi-document QA

## Notebooks for this activity

* [multidocQA_using_LLM_and_IIRC.ipynb](multidocQA_using_LLM_and_IIRC.ipynb): Multi-document QA implementation using LLM (`gpt3.5-turbo`) to execute the documents aggregation over [IIRC (Incomplete Information Reading Comprehension Questions) dataset](https://allenai.org/data/iirc).

<br/>
This implementation was based on the [neuralmind-ai/visconde](https://github.com/neuralmind-ai/visconde/tree/main) reference.

## Final results

| dataset | # questions | k aggregation | exact match score | f1 score | duration (s) |
|:---:|:---: |:---: |:---: |:---: |:---:|
| dev | 10 | 3 | 0.5 | 0.5971 | 20.49 |
| test | 10 | 3 | 0.1 | 0.1667 | 19.45 |
| test | 10 | 5 | 0.4 | 0.5467 | 21.92 |

<br/>

Check [here a presentation](https://docs.google.com/presentation/d/1ZxC38VyndG-eRamZNw0tCwX5BOYA2Hc_3FrXmm2tDj8/edit?usp=share_link) commenting this exercise resolution.
