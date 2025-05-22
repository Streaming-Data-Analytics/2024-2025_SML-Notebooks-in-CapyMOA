# 2024-2025 SML Notebooks in CapyMOA

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2023-24/) course provided by [Politecnico di Milano](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=811164&polij_device_category=DESKTOP&__pj0=0&__pj1=d563c55e73c3035baf5b0bab2dda086b).

Student: Sebastian Ballesteros (10945208)

Final presentation link: https://www.canva.com/design/DAGkgk0WPu4/ZVpTionxGsxBxhRwHM-0_Q/edit?utm_content=DAGkgk0WPu4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## Background
Streaming Machine Learning is a paradigm for processing data in real time, continuously adapting the model to new information. This approach is particularly useful in scenarios where data arrive in continuous streams and it is not practical or possible to re-train the model on the entire accumulated dataset.

CapyMOA is a recent library for Streaming Machine Learning based on MOA (Massive Online Analysis), which proposes an optimized implementation of several online learning algorithms. Another popular library for Streaming Machine Learning is River, which offers a range of algorithms and tools for stream data analysis.

This project aims to reproduce the tutorial notebooks of CapyMOA and compare their temporal performance with similar implementations in River, to evaluate the actual optimization proposed by the authors of CapyMOA.

## Goals and objectives
- Reproduce CapyMOA tutorial notebooks to understand how the library works.
- Compare the time performance of some parts of the CapyMOA code with the same features implemented in River.
- Analyze not only the execution speed, but also predictive performance and computational costs (e.g., CPU/RAM usage).
- Check whether time optimization in CapyMOA resulted in sacrifices in accuracy or computational efficiency.
- Identify any features present in River but absent in CapyMOA, suggesting possible motivated improvements to the library.

## Datasets
To ensure a fair comparison between the two libraries, standard datasets for Streaming Machine Learning will be used. Some suggested datasets are:
- *Electricity:* a classification problem based on the Australian New South Wales Electricity Market
- *Covertype:* it contains the forest cover type for 30 x 30 meter cells obtained from US Forest Service (USFS) Region 2 Resource Information System (RIS) data.
- *Fried:* a regression problem based on the Friedman dataset.
- *Synthetic datasets:* artificially generated datasets to evaluate specific aspects of streaming learning algorithms.

## Evaluation metrics
The metrics used for comparison will be:
- *Run-time:* measurement of the time required to complete training and prediction.
- *Performance metrics:* to assess the quality of the model.
- *Memory Utilization:* amount of RAM required during execution.
- *CPU Utilization:* computational load generated.

## Deliverable
At the end of the project, the student should deliver:
- Notebooks containing:
  - A reproduction of the CapyMOA tutorials.
  - Comparison with implementations in River.
  - Analysis of performance and computational costs.
- A section with proposals for features that could be added to CapyMOA, taking inspiration from River.

The project will help to understand the advantages and limitations of CapyMOA compared to an established library such as River, providing concrete data on their differences in performance and scalability.

## Note for Students
- Clone the created repository offline;
- Add your name and surname into the Readme file;
- Make any changes to your repository, according to the specific assignment;
- Add a requirement.txt file for code reproducibility and instructions on how to replicate the results;
- Commit your changes to your local repository;
- Push your changes to your online repository.

