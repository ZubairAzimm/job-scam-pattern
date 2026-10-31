# Requirements

## Functional requirements (what the system must DO)
FR-01:The system shall accept raw text input containing job titles, job descriptions, and requirements.
FR-02:The system shall clean and preprocess input text by removing HTML tags, punctuation, unwanted tex, and performing tokenization.
FR-03:The system shall convert text tokens into numerical vectors using TF-IDF feature extraction.
FR-04:The classification engine shall output a prediction label indicating whether the post is `Legitimate` or `Fraudulent`.
FR-05:The system shall display a confidence percentage score alongside the classification result to the user.

## Non-functional requirements (how the system must PERFORM)
NFR-01:The system shall complete text tokenization, and model inference within 2.0 seconds per job description.
NFR-02: The system shall encrypt all user-submitted job descriptions.
NFR-03: The text classification model shall maintain a minimum classification accuracy of 90% when evaluated against benchmark test splits.


