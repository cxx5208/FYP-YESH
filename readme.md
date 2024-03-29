**CREATING A UNIFIED FRAMEWORK FOR VISION LANGUAGE PRE-TRAINING DOWNSTREAM TASKS**

**ABSTRACT:**
The use of Vision-Language Pre-training (VLP) has considerably enhanced the
efficiency of many vision-language tasks. However, existing pre-trained models have
limitations in their performance and are specialized in either understanding or generationbased tasks. Additionally, the current methodology for improving performance has relied
on a dataset that includes noisy image-text pairs gathered from the web, which is not an
optimal source of supervision. In this research, a new VLP framework is proposed, which
flexibly transfers to both vision-language understanding and generation tasks.
The framework makes use of the noisy web data by bootstrapping the captions,
where synthetic captions are generated by a captioner, and a filter is utilized to remove
the noisy ones. State-of-the-art results have been achieved using this framework for
various vision-language tasks, such as image-text retrieval, image captioning, and VQA.
For example, the average recall@1 has improved by 2.7% in image-text retrieval,
CIDEr has increased by 2.8% in image captioning, and there is a 1.6% enhancement in
VQA score. Furthermore, this new framework shows a robust generalization ability, and
it can be directly transferred to video-language tasks in a zero-shot approach.

**Model Architecture:**

<img width="668" alt="Screen Shot 2023-10-03 at 5 03 14 PM" src="https://github.com/cxx5208/FYP-YESH/assets/76988460/5e5b5482-7f8e-4613-92df-c24849a5adf9">

**Results:**

<img width="542" alt="Screen Shot 2023-10-03 at 5 04 23 PM" src="https://github.com/cxx5208/FYP-YESH/assets/76988460/09febd8b-7a1b-425e-9202-701852d7f225">
<img width="540" alt="Screen Shot 2023-10-03 at 5 05 02 PM" src="https://github.com/cxx5208/FYP-YESH/assets/76988460/5168bb8e-5d68-4237-812e-7e5185eadf09">

