# Hi, I'm Dorna 🤗

I have an MSc in Computer Science from the University of British Columbia. I work on machine learning for messy, real-world data: language models for data integration, document understanding, and vision-language retrieval.

## Selected projects

**[LLM-assisted schema matching for spreadsheets](https://github.com/thedrna/spreadsheet-schema-matching)** (MSc thesis)
A pipeline that turns heterogeneous Excel spreadsheets into one standardized dataset. Local LLMs (Jellyfish 7B, Mistral 7B) decide which columns match, and deterministic rules do the transformations, so results stay auditable. Evaluated on 35 held-out projects. [Thesis](https://open.library.ubc.ca/soa/cIRcle/collections/ubctheses/24/items/1.0451952?o=0)

**[Page classification with OCR and LayoutLM](https://github.com/thedrna/environmental-doc-classification)**
Tesseract OCR plus a fine-tuned LayoutLM classifies document pages as chart/map, correspondence, or other. 0.88 accuracy on 253 held-out pages, using a document-wise split so no document appears in both training and test.

**[Zero-shot image retrieval with generated reference images](https://github.com/thedrna/zero-shot-image-retrieval)**
Stable Diffusion turns a text prompt into a reference image, and CLIP and DINOv2 embeddings find the closest images in an unlabeled collection. The top result was judged relevant for 75 to 90% of prompts, depending on the model combination.

## Tools

Python, PyTorch, Hugging Face Transformers, pandas, scikit-learn, Ollama, PandasAI, Tesseract, R (tidyverse)

## Contact

[LinkedIn](www.linkedin.com/in/dorna-dehghani-294b6b185)
