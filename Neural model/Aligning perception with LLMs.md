### Language Is Not All You Need: Aligning Perception with Language Models

Paper: [ https://doi.org/10.48550/arXiv.2302.14045](https://doi.org/10.48550/arXiv.2302.14045)

Github: https://github.com/microsoft/unilm

Microsoft: [Shaohan Huang](https://arxiv.org/search/cs?searchtype=author&query=Huang%2C+S), [Li Dong](https://arxiv.org/search/cs?searchtype=author&query=Dong%2C+L), [Wenhui Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+W), [Yaru Hao](https://arxiv.org/search/cs?searchtype=author&query=Hao%2C+Y), [Saksham Singhal](https://arxiv.org/search/cs?searchtype=author&query=Singhal%2C+S), [Shuming Ma](https://arxiv.org/search/cs?searchtype=author&query=Ma%2C+S), [Tengchao Lv](https://arxiv.org/search/cs?searchtype=author&query=Lv%2C+T), [Lei Cui](https://arxiv.org/search/cs?searchtype=author&query=Cui%2C+L), [Owais Khan Mohammed](https://arxiv.org/search/cs?searchtype=author&query=Mohammed%2C+O+K), [Barun Patra](https://arxiv.org/search/cs?searchtype=author&query=Patra%2C+B), [Qiang Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+Q), [Kriti Aggarwal](https://arxiv.org/search/cs?searchtype=author&query=Aggarwal%2C+K), [Zewen Chi](https://arxiv.org/search/cs?searchtype=author&query=Chi%2C+Z), [Johan Bjorck](https://arxiv.org/search/cs?searchtype=author&query=Bjorck%2C+J), [Vishrav Chaudhary](https://arxiv.org/search/cs?searchtype=author&query=Chaudhary%2C+V), [Subhojit Som](https://arxiv.org/search/cs?searchtype=author&query=Som%2C+S), [Xia Song](https://arxiv.org/search/cs?searchtype=author&query=Song%2C+X), [Furu Wei](https://arxiv.org/search/cs?searchtype=author&query=Wei%2C+F)

>A big convergence of language, multimodal perception, action, and world modeling is a key step toward artificial general intelligence. 
>
>In this work, we introduce Kosmos-1, a Multimodal Large Language Model (MLLM) that can perceive general modalities, learn in context (i.e., few-shot), and follow instructions (i.e., zero-shot). Specifically, we train Kosmos-1 from scratch on web-scale multimodal corpora, including arbitrarily interleaved text and images, image-caption pairs, and text data. We evaluate various settings, including zero-shot, few-shot, and multimodal chain-of-thought prompting, on a wide range of tasks without any gradient updates or finetuning. 
>
>Experimental results show that Kosmos-1 achieves impressive performance on (i) language understanding, generation, and even OCR-free NLP (directly fed with document images), (ii) perception-language tasks, including multimodal dialogue, image captioning, visual question answering, and (iii) vision tasks, such as image recognition with descriptions (specifying classification via text instructions). 
>
>We also show that MLLMs can benefit from cross-modal transfer, i.e., transfer knowledge from language to multimodal, and from multimodal to language. In addition, we introduce a dataset of Raven IQ test, which diagnoses the nonverbal reasoning capability of MLLMs.



### The Increasing Role of Sensorimotor Experience in Artificial Intelligence 

Richard Sutton

All Rich Sutton's Talks :http://www.incompleteideas.net/Talks/Talks.html

> Sensorimotor experience is the sensations and actions of an agent's ordinary interaction with the world
>
> >- Reinforcement learning involves experience
> >- Predictive learning involves experience
> >- Supervised learning does not involve experience: it learns from special training data
> >- Experience is the agent's only access to the world
> >- Experience has meaning only by its relationship to other experience
> > - except for reward, a special scalar part of the sensation, which is good

Will intelligence ultimately be explained in

>Experiential terms
>
>>- sensations
>>- actions
>>- rewards
>>- time steps
>>- things inside the agent

>Objective terms
>
>>- states of the external world
>>- objects, people, places, relationship, atoms
>>- space, motion, distances
>>- things outside the agent

Main points / outline

> Over Al's seven decades, experience has played an increasing role; I see four major steps in this progression:
>
> > Step 1: Agenthood (having experience)
> > Step 2: Reward (goals in terms of experience)
> > Step 3: Experiential state (state in terms of experience)
> > Step 4: Predictive knowledge (to know is to predict experience)
>
> For each step, Al has reluctantly moved toward experience in order to be more grounded, learnable, and scalable



### Cross-Modal Fine-Tuning: Align then Refine

> Fine-tuning large-scale pretrained models has led to tremendous progress in well-studied modalities such as vision and NLP. However, similar gains have not been observed in many other modalities due to a lack of relevant pretrained models. In this work, we propose ORCA, a general cross-modal f ine-tuning framework that extends the applicability of a single large-scale pretrained model to diverse modalities. ORCA adapts to a target task via an align-then-refine workflow: given the target input, ORCA first learns an embedding network that aligns the embedded feature distribution with the pretraining modality. The pretrained model is then fine-tuned on the embedded data to exploit the knowledge shared across modalities. Through extensive experiments, we show that ORCA obtains state-of-the-art results on 3 benchmarks containing over 60 datasets from 12 modalities, outperforming a wide range of hand-designed, AutoML, general-purpose, and task-specific methods. We highlight the importance of data alignment via a series of ablation studies and demonstrate ORCA’s utility in data-limited regimes.
>
> 