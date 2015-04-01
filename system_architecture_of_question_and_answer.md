# System Architecture of Question and Answer

#### Many questions can be answered by traditional search engines.

> What is the Largest City in Northern Afghanistan?

- Send the question in some form
- Query documents

#### Strategy
1. source identification
    - What documents we should use?
2. query modulation
    - paraphrase the question of a NL question to a syntax that search engine understands.
    ex. Who wrote Hamlet -> author | wrote Hamlet
3. document retrieval
4. sentence ranking
    - n-gram matching
5. answer extraction
    - question type classification
    - phrase chunking
6. answer ranking
    - frequency of the word

> What is the Largest City in Northern Afghanistan?

1. modulation: (largest OR biggest) city AND "northern afganistan"

#### Question Type Classification

> Who wrote Anna Karenina

Look for **entity**, a person.

#### UIUC Question Types

More comprehensive taxonomy of different questions types.
