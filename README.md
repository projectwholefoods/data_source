# Project WHOLEFOODS

>Please read this:
>
>Any and all resources are "void of warranty" and provided "as-is". This includes this current repository and all publicly facing releases, regardless of whether labeled as `stable` or not. Personal use-case is open and doesn't abide by any licensing restrictions or contractual obligations. Medical use-case is currently prohibited until explicitly stated otherwise in future licensing.

## `data_source`

Nutrition-specific and cost-related datapoints provided to synthesize the final insights. Here are required implementation steps:

### 1. Structure 

Intermediate format is arbitrary, but should follow the structure of the pathway, so that it's easily tracable "back-to-back" from insight to original clues.

>We highly recommend you **do not** use third-party, online-sourced providers, as this can lead to imprecise data provision and/or outdated clues. If you rely on a reliable third-party provider and are fine with doing so, you can.
>
>Please refer to [wholefoods](https://github.com/projectwholefoods/wholefoods) for implementation details.

### 2. Processing / Analysis

Processes can include manual cross-analysis or an LM model of choice (or dedicated "mixture-of-experts", eg. cross-examining the input data from different specialization standpoints - nutritionalist, personal trainer, etc.) with the addition of `RAG` data retrieval for precise clinical alignment[[0]](#0).



## Additional resources

- For the technical request structure as well as the `POST` structure, please refer to following repo: [research-public](https://github.com/projectwholefoods/research-public)
- For original source, we also include direct backing of the data sources. Only for referencial[[1]](#1) use: [sources-public](https://github.com/projectwholefoods/sources-public)
- For a recommended contextual input example (version `1.0`: textual prompts and files structure) visit: [wholefoods](https://github.com/projectwholefoods/wholefoods)


## Footnotes
>
><a id="0">[0]</a> Please note, medical use-case is currently prohibited and unwarranted. For personal use-case, always consult your doctor before proceeding with medical-related queries.
>
><a id="1">[1]</a>  `sources-public` contain partial visual clues to prefill our database and **DOES NOT** contain detailed nutrional information.
For complete reference please contant our developers (`ermu at wholefoods dot lifestyle`) or please kindly wait for an upcoming `stable` release.
