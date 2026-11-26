Bano Qabil RAG AI Assistant

An AI-powered assistant that answers questions about Bano Qabil using information from its official website.

About the Project

This project uses Retrieval-Augmented Generation (RAG) to retrieve relevant information and generate helpful answers about Bano Qabil, including its courses, registration, and training programs.

Technologies Used

- Python
- Google Colab
- Gemini Embedding API
- Pinecone Vector Database
- Groq API
- BeautifulSoup
- Requests

How It Works

1. Collect information from the Bano Qabil website.
2. Extract and clean website content.
3. Split content into smaller chunks.
4. Generate embeddings using Gemini.
5. Store vectors in Pinecone.
6. Retrieve relevant information based on user questions.
7. Generate answers using Groq.

Knowledge Base

- https://banoqabil.pk
- https://banoqabil.pk/about
- https://banoqabil.pk/courses
- https://banoqabil.pk/news
- https://banoqabil.pk/faq
- https://banoqabil.pk/students

Hallucination Testing

The assistant was tested with questions about courses, registration, job guarantees, salaries, and the founder.

It provided answers based on retrieved website information and avoided making unsupported claims.

Future Improvements

- Add a user-friendly chat interface.
- Improve retrieval accuracy.
- Add Urdu language support.
- Improve response speed.

Project Goal

Built as a practical project to learn Retrieval-Augmented Generation, embeddings, vector databases, and AI-powered question answering.