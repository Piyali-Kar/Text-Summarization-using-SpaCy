# Text-Summarization-using-SpaCy
Complete explanation of Text Summarization with code

**Text summarization:**
Text Summarization is basically a process of providing a summary, a brief restatement of something that captures all its important points.

**It is categorised based on: -**

![image](https://user-images.githubusercontent.com/111500103/232610935-11a2b351-d765-444a-8596-f663f91fd763.png)

*BASED ON INPUT TYPE*

**Single-Document:** where the input length is short.
**Multi-Document:** where the input can be arbitrarily long.

*BASED ON PURPOSE*

**Generic:** where the model makes no assumptions about the domain or content of the text to be summarized and treats all inputs as homogeneous.
**Domain Specific:** where the model uses domain-specific knowledge to form a more accurate summary. For example, summarizing research papers of a specific domain, biomedical documents, etc.
**Query Based:** here the summary only contains information that answers natural language questions about the input text.

*BASED ON OUTPUT TYPE*

**Abstractive:** where important sentences are selected from the input text to form a summary. Commonly used.
**Extractive:** where the model forms its own phrases and sentences to offer a more coherent summary, like what a human would generate. This approach is definitely more appealing, but much more difficult than extractive summarization.
