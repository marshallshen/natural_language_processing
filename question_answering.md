# Question Answering

- Siri
- Ask Jeeves (ask.com)
- WolframAlpha (answer of math questions)
- IBM's Watson

### Watson on Jeopardy

- Sample questions:
    > In 2010 this first lady published book "XXX".

- People ask questions online (about 10%)
    - Half of questions are factual
    - Half of questions are procedural.

- Murax Question:
    - What U.S city is at the junction of ...

- AOL Corpus Questions

## Question Type Taxonomy

    - Factual vs. Procedural
    - Single vs. Multiple Answers
    - Objective vs. Subjective
    - Context-specific vs. Generic
    
## State of the Art

    - Question type: mostly factual, short-answer questions
    - Statistical approaches using lots of data
    
#### Eliza

    - Plays a therapy
    - Built in 1960s

#### Lunar

    - Lunar Sciences Natural Language Information System.
    - Lunar Grammar Fragment: classify questions.

### How to evaluate Q&A question
    - Run by NIST
    - Facts extraction to analyze accuracy
    
### MRR: Mean Reciprocal Rank (ex. Watson came up different passages, ordered by descending probability)

- Pass in 5 passages for each answer, and verify the correctness of the answer
> What is the capital of Canada?
    1. New York 2. Ottawa... (highest rank is 2)
- If one passage has wrong answer, it has lower score.
- The MRR is an average formula over all results of 5 pssages.

### Other types of questions

Definitional:
    - What is a boll weevil
List:
    - Which stats signed the Independence
Crosslingual:
    - What is "ni hao"?
Series Questions:
    - Who is the lead singer in Nirvana?
    - What are the members of the band? (band is Nirvana)

    





    



