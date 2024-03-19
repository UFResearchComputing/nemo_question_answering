**NeMo_Question_Answering**
===============
This tutorial was adopted from the Nemo User Guide.

Key Features
------------
* Natural Language Processing: [Question answering](https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/en/main/nlp/question_answering.html)
* [Question Answering Tutorial](https://colab.research.google.com/github/NVIDIA/NeMo/blob/stable/tutorials/nlp/Question_Answering.ipynb)

**NVIDIA NeMo**
===============
Introduction
------------
* NVIDIA NeMo is a conversational AI toolkit built for researchers working on automatic speech recognition (ASR), text-to-speech synthesis (TTS), large language models (LLMs), and natural language processing (NLP).

* The primary objective of NeMo is to help researchers from industry and academia to reuse prior work (code and pretrained models) and make it easier to create new [conversational AI models](https://developer.nvidia.com/conversational-ai#started).

Getting started with NeMo
------------
* State of the Art pretrained NeMo models are freely available on [HuggingFace Hub](https://huggingface.co/models?library=nemo&sort=downloads&search=nvidia) and [NVIDIA NGC](https://catalog.ngc.nvidia.com/models?query=nemo&orderBy=weightPopularDESC).

* These models can be used to transcribe audio, synthesize speech, or translate text in just a few lines of code.

* They have extensive [tutorials](https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/en/stable/starthere/tutorials.html) that can be run on [Google Colab](https://colab.research.google.com).

NeMo Github Repositories
------------
https://github.com/NVIDIA/NeMo/tree/main

**Steps to Follow for This Tutoria**
===============
1. Feel free to run the first two model training sessions using the BERT and BART models.
2. If you require an A100 GPU, you can complete the remaining exercises.
3. If you require an RTX 2080 Ti GPU (11GB memory), you may encounter an out-of-memory issue. Running the GPT-2 model will need approximately 13 GB, and the S2S BART model for MS-4. MARCO will need approximately 12 GB. One way to address this is by reducing the batch size to fit the training on a single RTX GPU.
5. If you are interested in running with multiple GPUs, more technical information can be found in the PyTorch Lightning documentation: [MODEL PARALLEL GPU TRAINING](https://lightning.ai/docs/pytorch/1.6.5/advanced/model_parallel.html#choosing-an-advanced-distributed-gpu-strategy).


License
------------
* All rights reserved. This work is the property of the NVIDIA NeMo Team.

* NeMo is released under an [Apache 2.0 license](https://github.com/NVIDIA/NeMo/blob/stable/LICENSE).