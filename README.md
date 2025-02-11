# Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence

> Dataset of the paper: J. Martinez-Gil, Bernhard Freudenthaler, A Min Tjoa: Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence. DEXA (1) 2019: 138-148

[![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--3--030--27615--7_10-blue)](https://doi.org/10.1007/978-3-030-27615-7_10) [![Citations](https://img.shields.io/badge/citations-9-blue)](https://scholar.google.com/citations?view_op=view_citation&hl=en&citation_for_view=X1pRUYcAAAAJ:ndLnGcHYRF0C)

## 📖 Introduction
This dataset is a comprehensive collection of multiple-choice questions (MCQs) focused on the legal domain. It covers a broad range of topics such as European Commission procedures, legal document types, court system processes, legal definitions, and laws of the European Union and United Kingdom. 

### Citation
If you find this dataset useful, please cite the original work:

```bibtex
@inproceedings{GilFT19,
  title     = {Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence},
  author    = {Jorge Martinez-Gil and Bernhard Freudenthaler and A Min Tjoa},
  booktitle = {Database and Expert Systems Applications - 30th International Conference, {DEXA} 2019, Linz, Austria, August 26-29, 2019, Proceedings, Part {I}},
  year      = {2019},
  publisher = {Springer},
  pages     = {138--148},
  series    = {Lecture Notes in Computer Science},
  volume    = {11706},
  doi       = {10.1007/978-3-030-27615-7_10},
  url       = {https://doi.org/10.1007/978-3-030-27615-7_10}
}
```

## 📊 Dataset Structure
The dataset is formatted as a JSON array, with each element representing a distinct multiple-choice question (MCQ). The structure of each question object is outlined below:

#### Key - Description - Type
- `id` - Unique identifier for the question - Integer
- `question` - The question text - String
- `options` - An array of answer options - Array of objects

#### Example JSON Object
```json
{
  "id": 1,
  "question": "What type of form must a claimant complete to initiate legal action in a civil court?",
  "options": [
    {"option": "Civil action", "is_correct": false},
    {"option": "Track form", "is_correct": false},
    {"option": "Claim form", "is_correct": true},
    {"option": "Business form", "is_correct": false}
  ]
}
```

## 🚀 Usage

This dataset can be employed for various purposes, including:

-   **MCQA Accuracy Assessment**: Evaluate the precision of multiple-choice question answering systems in the legal domain.
-   **Machine Learning Training**: Use this dataset to train AI models focused on assessing legal knowledge.

## 📜 License

This dataset is available for educational use. For commercial applications, please adhere to applicable copyright and licensing regulations.

## 🙏 Acknowledgments

This dataset is intended for educational and informational purposes and should not be considered a substitute for professional legal advice. Users should consult with legal experts for specific legal issues.

## ⚠️ Note

Ensure the verification of the legal information's accuracy and relevance before using it, as legal standards and regulations may evolve over time.


## 📖 Research that has cited this work

### Legal Question Answering Systems

1. **[Exploring the State of the Art in Legal QA Systems](https://link.springer.com/content/pdf/10.1186/s40537-023-00802-8.pdf)**
   - **Authors:** A. Abdallah, B. Piryani, A. Jatowt
   - **Journal:** *Journal of Big Data*, 2023 (Springer)
   - **Abstract:** Answering questions in the legal domain is complex due to the intricate nature and diversity of legal documents. This paper explores advancements in legal QA systems.

2. **[A Survey on Legal Question–Answering Systems](https://www.sciencedirect.com/science/article/pii/S1574013723000199)**
   - **Author:** J. Martinez-Gil
   - **Journal:** *Computer Science Review*, 2023 (Elsevier)
   - **Abstract:** The rapid expansion of legal information makes legal practice more costly and time-consuming. This survey explores methods to improve efficiency in legal QA.

3. **[BERT-CNN Based Evidence Retrieval and Aggregation for Chinese Legal Multi-Choice Question Answering](https://link.springer.com/content/pdf/10.1007/s00521-023-09380-5.pdf)**
   - **Authors:** Y. Li, J. Wu, X. Luo
   - **Journal:** *Neural Computing and Applications*, 2024 (Springer)
   - **Abstract:** This study applies BERT-CNN for evidence retrieval in Chinese legal QA, using the Judicial Examination dataset.

4. **[cLegal-QA: A Chinese Legal Question Answering with Natural Language Generation Methods](https://link.springer.com/content/pdf/10.1007/s40747-024-01675-x.pdf)**
   - **Authors:** Y. Wang, X. Shen, Z. Huang, L. Niu, S. Ou
   - **Journal:** *Complex & Intelligent Systems*, 2025 (Springer)
   - **Abstract:** This paper introduces a legal QA system using natural language generation to improve answer accuracy.

### Multiple-Choice Question Answering

5. **[Natural Language-Based Analysis of SQuAD: An Analytical Approach for BERT](https://www.sciencedirect.com/science/article/pii/S0957417422000884)**
   - **Authors:** Z.A. Guven, M.O. Unalir
   - **Journal:** *Expert Systems with Applications*, 2022 (Elsevier)
   - **Abstract:** A study on the performance of BERT-based QA models using SQuAD datasets.

6. **[NLP-Based Management of Large Multiple-Choice Test Item Repositories](https://files.eric.ed.gov/fulltext/EJ1411474.pdf)**
   - **Authors:** V. Albano, D. Firmani, L. Laura, J.G. Mathew
   - **Journal:** *Journal of Learning*, 2023 (ERIC)
   - **Abstract:** Proposes an NLP-based system for managing large MCQ repositories in educational assessments.

7. **[Paragraph Similarity Matches for Generating Multiple-Choice Test Items](https://aclanthology.org/2021.ranlp-srw.15.pdf)**
   - **Authors:** H. Maslak, R. Mitkov
   - **Conference:** *Proceedings of the Student Research Workshop*, 2021 (ACL Anthology)
   - **Abstract:** Discusses an NLP-based method to automatically generate MCQs from text sources.

8. **[Managing Large Multiple-Choice Test Item Repositories](https://ieeexplore.ieee.org/abstract/document/10017844/)**
   - **Authors:** V. Albano, D. Firmani, L. Laura
   - **Conference:** *26th IEEE International Conference on Education Technologies*, 2022
   - **Abstract:** Describes a system for large-scale MCQ management in online assessment platforms.

9. **[A General Framework for Multiple-Choice Question Answering Based on Mutual Information and Reinforced Co-Occurrence](https://link.springer.com/chapter/10.1007/978-3-662-60531-8_4)**
   - **Authors:** J. Martinez-Gil, B. Freudenthaler, A.M. Tjoa
   - **Journal:** *Transactions on Large-Scale Data- and Knowledge-Centered Systems*, 2019 (Springer)
   - **Abstract:** Proposes a framework using mutual information and reinforcement learning for MCQ answering.
