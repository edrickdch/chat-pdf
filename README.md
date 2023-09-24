<p align="center">  
  <img href="daceflow.ai" src="https://github.com/edrickdch/chat-pdf/assets/36369935/1a88ae12-12a2-4407-831d-da9d5f60289a" alt="Daceflow AI logo" width="200"/>
</p>

<h3 align="center"> Elevate Your Project with Top-Tier AI/LLM Expertise! 🚀 </h3>

<p align="center">
  <b>Daceflow AI</b> <br>
  <a href="http://daceflow.ai">Unlock Possibilities →</a> <br>
  📧 Connect with us: <a href="mailto:edrick@daceflow.ai">edrick@daceflow.ai</a>
</p>

# 💬 Chat with your PDF 

## 👷️ Architecture

Link: https://youtu.be/FuqdVNB_8c0

This tutorial goes over the architecture and concepts used for easily chatting with your PDF using LangChain, ChromaDB and OpenAI's API.

## 💻 Getting Started

### Prerequisites

You will need Python and Pipenv.

Note: For **Windows** users, you might need to delete the `Pipfile.lock` before proceeding with the installation.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/edrickdch/chat-pdf
```

2. Navigate to the project directory:

```bash
cd chat-pdf
```

3. Install the required dependencies using Pipenv:

```bash
pipenv install
```

4. Activate the Pipenv shell:

```bash
pipenv shell
```

5. Create a .env file with your OpenAI API key (Replace with your key):

```bash
cat 'OPENAI_API_KEY="sk-XXXXXXXXXXXXXXXXXXXXXXXXXXXX"' >  .env
```

6. Run the ingestion:

```bash
python src/ingest.py
```

7. Run the conversation:

```bash
python src/single-pdf.py
```

## 🔗 Useful Links

- PDF: https://www.imf.org/en/Publications/WEO/Issues/2023/04/11/world-economic-outlook-april-2023 
- OpenAI: https://platform.openai.com/ 
- LangChain: https://python.langchain.com/en/latest/index.html  
- Chroma DB: https://docs.trychroma.com/ 

## 💌 Newsletter

👇 Subscribe to the newsletter if you're interested in building more AI applications 

https://practical-ai-builder.beehiiv.com/
