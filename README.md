# ChartTableViVQA 
Repository for ChartTableViVQA: A Vietnamese Benchmark Dataset for Visual Question Answering with Reasoning Instruction over Charts and Tables Images
Data size: 
+ 868 images including 395 for charts and 473 for tables.
+ 13,003 question-answering pairs with instruction.

Please note that this dataset is used for research purposes only. 

# Publication 
Link: https://aclanthology.org/2026.aacl-long.5/  
Please cite this publication if you use ChartTableViVQA
```
@inproceedings{truong-etal-2026-charttablevivqa,
    title = "{C}hart{T}able{V}i{VQA}: A {V}ietnamese Benchmark Dataset for Visual Question Answering with Reasoning Instruction over Charts and Tables Images",
    author = "Truong, Quang Nhat  and
      Thang, Pham Quoc  and
      Luu, Son T.",
    editor = "Zhang, Yue  and
      Xu, Ruifeng  and
      Purwarianti, Ayu  and
      Rong, Tong  and
      Suzuki, Jun",
    booktitle = "Proceedings of the 15th International Joint Conference on Natural Language Processing and the 5th Conference of the {A}sia-Pacific Chapter of the {A}ssociation for {C}omputational {L}inguistics (Volume 1: Long Papers)",
    month = nov,
    year = "2026",
    address = "Hengqin, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.aacl-long.5/",
    pages = "99--123",
    ISBN = "979-8-89176-439-2",
    abstract = "Visual Question Answering (VQA) over charts and tables requires joint reasoning over language, visual structure, and numerical information, yet no standard benchmark currently exists for Vietnamese. We introduce \textbf{ChartTableViVQA}, a Vietnamese VQA dataset with 13,003 question{--}answer{--}instruction triplets over 868 chart and table images. Questions cover multiple reasoning types, ranging from simple value lookup to multi-step aggregation, comparison, and trend analysis, and are accompanied by concise instructions that explicitly guide the reasoning process. The dataset is built via a semi-automatic human-in-the-loop pipeline, combining large language model generation with manual verification by Vietnamese annotators. We evaluate several vision-language models in zero-shot and instruction-based settings. Results show strong performance on simple questions but clear weaknesses in complex reasoning, particularly on charts, while instruction-based prompting consistently improves accuracy."
}
```
