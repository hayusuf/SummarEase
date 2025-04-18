# SummarEase
### Making Long Reads Effortless
This project was created for EECS 486, Information Retrieval.

We create a hybrid summarization model based on both extractive and abstractive summarization methods. 

It is motivated by people experiencing information overload from having to read lengthy or dense content resulting in 
reader fatigue.

The intention is to empowers readers to save time, improve comprehension, and stay informed across a variety of content types.

A retroactively cleaned version of our code has been added here. 

## The datasets we used:

### 1. CNN/DailyMail
Domain: News articles

Size: ~287,000 samples

Content: Full news articles with human-written highlights

Purpose: Primary dataset for both extractive and abstractive training/fine-tuning

Annotation Type: Human-generated summaries

### 2. XSum
Domain: BBC News articles

Size: ~204,000 samples

Content: Each article paired with a single-sentence summary

Purpose: Testing performance on extreme summarization tasks

Annotation Type: Human-written short summaries

### 3. PubMed
Domain: Biomedical research

Size: ~1.1 million scientific paper abstracts

Content: Long-form biomedical articles paired with abstracts

Purpose: Testing the model's performance on complex, domain-specific text

Annotation Type: Author-written abstracts
### 4. arXiv
Domain: Scientific research 

Size: ~215,000 papers

Content: Full papers paired with abstracts

Purpose: Evaluating summarization on technical, structured academic text

Annotation Type: Author-written abstracts

### 5. The Guardian 
Domain: Journalistic articles

Size: ~10,000 articles

Content: Professionally written news with varied tones and structures

Purpose: Custom/qualitative evaluation for generalization and narrative handling

Annotation Type: Human-written content
