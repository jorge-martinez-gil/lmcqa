# Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence

Dataset of the paper *J. Martinez-Gil, Bernhard Freudenthaler, A Min Tjoa: Multiple Choice Question Answering in the Legal Domain Using Reinforced Co-occurrence. DEXA (1) 2019: 138-148*

[https://doi.org/10.1007/978-3-030-27615-7_10](https://doi.org/10.1007/978-3-030-27615-7_10 "https://doi.org/10.1007/978-3-030-27615-7_10")

## Introduction

This dataset contains a set of multiple-choice questions related to various legal topics. The dataset contains 20 questions covering various aspects of legal knowledge, such as the workings of the European Commission, types of legal documents, procedures in the court system, legal definitions, and European Union+United Kingdom law, among others.

If you find it useful for research, please consider citing the original publication:


```
@inproceedings{GilFT19,
  author       = {Jorge Martinez-Gil and
                  Bernhard Freudenthaler and
                  A Min Tjoa},
  editor       = {Sven Hartmann and
                  Josef K{\"{u}}ng and
                  Sharma Chakravarthy and
                  Gabriele Anderst{-}Kotsis and
                  A Min Tjoa and
                  Ismail Khalil},
  title        = {Multiple Choice Question Answering in the Legal Domain Using Reinforced
                  Co-occurrence},
  booktitle    = {Database and Expert Systems Applications - 30th International Conference,
                  {DEXA} 2019, Linz, Austria, August 26-29, 2019, Proceedings, Part
                  {I}},
  series       = {Lecture Notes in Computer Science},
  volume       = {11706},
  pages        = {138--148},
  publisher    = {Springer},
  year         = {2019},
  url          = {https://doi.org/10.1007/978-3-030-27615-7\_10},
  doi          = {10.1007/978-3-030-27615-7\_10}
}
```

Please note that each question is associated with four options, one of which is marked as the correct answer. The dataset is designed for use in creating legal knowledge quizzes, educational materials, or for any other purpose where legal knowledge assessment is required.

## Dataset Structure
The dataset is provided as a JSON array, where each element represents a single multiple-choice question. Each question object has the following structure:

```json
{
  "id": 1,
  "question": "Question text",
  "options": [
    {
      "option": "Option text", 
      "is_correct": "true or false"
    },
    "... (three more options)"
  ]
}
```

## Example Question
In this example, the question asks about the type of form required to initiate legal action in a civil court, and the correct answer is "Claim form."

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

## Usage
You can use this dataset for various purposes, including:

- Assessing the accuracy of MCQA in the legal domain
- Training machine learning models for legal knowledge assessment

## License
This dataset is provided without any specific license. You are free to use it for educational purposes. If you plan to use it commercially, please comply with copyright and licensing requirements.

## Acknowledgments
This dataset is created for educational and informational purposes. It does not replace professional legal advice, and users should consult legal professionals for specific legal matters.

## Note
Please make sure to verify the accuracy and relevance of the legal information contained in this dataset before using it for any legal or educational purposes. Legal standards and regulations may change over time, and this dataset may not be current with the latest legal developments.
