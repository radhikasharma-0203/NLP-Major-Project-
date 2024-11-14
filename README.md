# NLP-Major-Project-
Automated Question Generator Using NLP 

Manually generating questions from text is time-consuming and requires significant effort. This tool aims to automate the process, making it easier for anyone to get a clear overview of the main concepts in a text through question prompts. Whether for study or review, this question-generation tool helps users break down dense material into assessable chunks, providing a quicker and more interactive way to engage with content.


The ability to quickly generate relevant questions helps a wide range of users—from students seeking to reinforce learning to professionals needing an overview of complex material. For educators, it offers a way to create quizzes and assessment questions without manually sifting through content. For students, it promotes active learning and provides a method to self-assess their understanding. For businesses and organizations, this tool can help streamline training materials and documentation reviews. 

# NLP Tecniques Used

To create meaningful questions, this project uses a few key NLP techniques that help identify important information in the text and then turn that information into questions. 

# 1. TF-IDF (Term Frequency-Inverse Document Frequency)
Purpose: TF-IDF helps find the most important words in the text.

How It Works: TF-IDF looks at how often each word appears in the text compared to how commonly that word is used in general. Words that appear frequently in the document but are not common in other texts (like topic-specific terms) get a higher score, making them stand out as keywords.

Why It’s Useful: By identifying keywords, we can focus on important topics within the text. 

# 2. Transformer Model for Question Generation
Purpose: The transformer model (specifically, a T5 model) is used to generate questions from selected parts of the text.

How It Works: Transformers are deep learning models that can understand and generate human-like text. Here, the T5 model is fine-tuned for question generation, which means it’s trained to take a sentence or passage and create a question about it. In this project, the model is given selected sentences with a highlighted portion that it uses as the focus for the question.

Why It’s Useful: The transformer model makes it possible to create questions that are natural and relevant to the text, rather than just simple factual questions. This adds depth to the questions, making them more useful for understanding the material.

# 3. Sentence Segmentation and Highlighting
Purpose: Breaking down the text into sentences and highlighting certain parts helps guide the question-generation process.

How It Works: Using the SpaCy library, the text is split into individual sentences, which makes it easier to select specific parts of the content to focus on. Key sentences are highlighted to signal to the model which parts are most important. For example, if we want to ask a question about a specific fact or concept, we can highlight it to ensure the question centers on that part.

Why It’s Useful: Highlighting specific sections helps the model focus on important information, resulting in questions that are more relevant to the user’s needs.




