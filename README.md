# DocGenome: An Open Large-scale Scientific Document Benchmark for Training Next-generation Large Models

Scientific documents record research findings and valuable human knowledge, comprising a vast corpus of high-quality data. Thus, leveraging multi-modality data extracted from these documents and assessing large models' abilities to handle scientific document-oriented tasks is meaningful. Despite promising advancements, large models still perform poorly on multi-page scientific document extraction and understanding tasks, and their capacity to process within-document data formats such as charts and equations remains under-explored. To address these issues, we present DocGenome, a structured document dataset constructed by annotating 500K scientific documents from 153 disciplines in the arXiv open-access community, using our custom auto-labeling pipeline. DocGenome features four key characteristics: 

- 1) Completeness: It is the first dataset to structure data from all modalities including 13 layout attributes along with their LaTeX source codes. 
- 2) Logicality: It provides 6 logical relationships between different entities within each scientific document. 
- 3) Diversity: It covers various document-oriented tasks, including document classification, visual grounding, document layout detection, document transformation, open-ended single-page QA and multi-page QA.  
- 4) Correctness: It undergoes rigorous quality control checks conducted by a specialized team. 

Besides, based on DocGenome, we conduct extensive experiments to demonstrate the advantages of DocGenome and objectively evaluate the performance of current large models on our benchmark.

<div align=center>
<img src="static/images/figure1.png" height="95%">
</div>

## This is [Official Page](https://unimodal4reasoning.github.io/DocGenome_page/) of DocGenome Benchmark. 