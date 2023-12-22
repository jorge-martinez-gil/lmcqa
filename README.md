# Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence

> Dataset of the paper: J. Martinez-Gil, Bernhard Freudenthaler, A Min Tjoa: Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence. DEXA (1) 2019: 138-148

[![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--3--030--27615--7_10-blue)](https://doi.org/10.1007/978-3-030-27615-7_10)

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