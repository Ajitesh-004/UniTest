# UniTest: AI-Based Question Paper Generator

UniTest is an intelligent question paper generator that leverages Natural Language Processing (NLP) and Machine Learning (ML) to generate syllabus-aligned, Bloom’s Taxonomy-based questions for academic assessments. Designed to assist educators, it ensures curriculum relevance, question diversity, and cognitive balance.

---

## Features

- Syllabus-Aligned Questions: Generates questions directly from provided syllabus topics.
- Bloom’s Taxonomy Integration: Classifies questions based on cognitive levels (Remember, Understand, Apply, Analyze, Evaluate, Create).
- AI-Powered Question Generation: Uses NLP models to generate meaningful and accurate questions.
- Question Paper Blueprint: Visual representation of question distribution by difficulty and topic.
- Topic-Based Filtering: Select specific units or chapters to tailor question papers.
- User-Friendly Interface: Clean, intuitive frontend for educators and admins.

---

## Tech Stack

| Layer        | Technologies Used |
|--------------|-------------------|
| Language      | Python |
| GUI Framework | Tkinter (for desktop interface), PIL (image handling) |
| NLP & AI      | NLTK (tokenization, stopwords), Google Generative AI (Gemini API) |
| ML Model      | Gemini 2.0 Flash (via Generative AI) |
| Database      | MySQL (for user accounts and progress tracking) |

---

## Why UniTest?

Traditional question paper setting is time-consuming, prone to repetition, and often lacks variety in cognitive levels. UniTest solves these problems by:

- Automating question generation
- Ensuring better syllabus coverage
- Enhancing learning outcomes through balanced cognitive level distribution

---

## How It Works

1. Input Syllabus: User provides the unit/topic syllabus or uploads a document.
2. Keyword Extraction: NLP extracts key concepts from the input.
3. Question Generation: Gemini AI generates questions using contextual understanding.
4. Classification: Each question is mapped to a Bloom’s Taxonomy level.
5. Display: Questions are shown in a clean UI with options to answer, retry, or move to the next level.


---

## Future Enhancements

- User Authentication and Role-based Access  
- Export Option: Download generated question papers in PDF format.
- Question Bank with Filtering and Tags  
- Multi-language support  
- Integration with Retrieval-Augmented Generation (RAG)
- ChatBot integration for better user experience 
---

Star this repository if you found it helpful!
