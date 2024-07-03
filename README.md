## Summariztion+Deep-translator (Jupyter-Notebook)
This project showcases how to use a model hosted on Hugging Face to summarize a PDF document. The process involves loading the PDF using fitz, chunking the text with LangChain, summarizing each chunk, concatenating the summaries, and then translating the final summary using deep-translator.

Steps
1. Loading the PDF
Use fitz (PyMuPDF) to load and read the PDF document.
Extract the text from the PDF for further processing.
2. Chunking the Text
Utilize LangChain to divide the extracted text into manageable chunks.
3. Summarizing Each Chunk
For each chunk of text, use a summarization model from Hugging Face to generate a summary.
Store the summaries of each chunk in a list.
4. Concatenating Summaries
Concatenate the individual chunk summaries to form a single document.
5. Translating the Final Summary
Use deep-translator to translate the final concatenated summary

## Text-Summarization-GROQ (Jupyter-Notebook)
This project use Groq API for invoking the Llama3 8b model to summarize the content of a PDF. The process involves loading a PDF, chunking it using LangChain, summarizing each chunk, concatenating the summaries, and finally generating a comprehensive summary.

Steps
1. Setting Up Groq API
Register and obtain your API key from Groq.
Access to the Llama3 8b model through Groq.
2. Loading the PDF file. Extract the text from the PDF for further processing.
3. Chunking the Text
Utilize LangChain to divide the extracted text into manageable chunks.
4. Summarizing Each Chunk
For each chunk of text, use the Groq API to call the Llama3 8b model and generate a summary.
Store the summaries of each chunk in a list.
5. Concatenating Summaries
Concatenate the individual chunk summaries to form a single document.
6. Final Summary
Use the Groq API once more to generate a final comprehensive summary from the concatenated chunk summaries.

## Future plan
- Discourse Analysis and find Discourse Structure
- Cohesion and Coherence
- Graph theory
