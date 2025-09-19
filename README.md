# LLMs, RAG & AI-Agenten in Python — Kurs: README (DE)

**Willkommen zum Kurs „LLMs, RAG & AI-Agenten in Python“ von AI & Data Solutions.**  
Dieser Kurs enthält interaktive Jupyter-Notebooks und praktische Code-Beispiele.

---

## Inhalt des Kurs-Ordners
Struktur (Beispiel):

LLMs-RAG-AI-Agents-Kurs/
├── 01_Einfuehrung/
│ └── notebooks/01_intro_llms.ipynb
├── 02_LLMs_Grundlagen/
│ ├── notebooks/02_openai_basics.ipynb
│ └── code/llm_prompts.py
├── 03_RAG/
│ ├── notebooks/03_faiss_demo.ipynb
│ └── code/rag_example.py
├── 04_AI_Agenten/
│ ├── notebooks/04_agent_demo.ipynb
│ └── code/agent_demo.py
├── 05_Abschlussprojekt/
│ └── notebooks/05_final_project.ipynb
├── requirements.txt
└── README.de.md

## Voraussetzungen
- Grundkenntnisse in Python (Variablen, Funktionen, Pakete, einfache Datenmanipulation mit Pandas empfohlen)
- Optional: Grundverständnis von Machine Learning / Modellen
- Empfohlen: Python 3.8+ und ein moderner Editor (VS Code / JupyterLab)

## Installation (lokal)
1. Repository/Ordner herunterladen.
2. Virtuelle Umgebung erstellen:
   python -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
Abhängigkeiten installieren:

pip install -r requirements.txt
Jupyter starten:

jupyter lab
oder

jupyter notebook
Verwendung in Google Colab (ohne lokale Installation)
Öffne das gewünschte Notebook (.ipynb) in GitHub → Open in Colab (oder lade das Notebook in Colab hoch).

Installiere im Colab-Notebook ggfs. zusätzliche Pakete per !pip install -r requirements.txt (oder einzeln).

Wichtige Dateien
requirements.txt — benötigte Python-Pakete (z. B. openai, langchain, chromadb, faiss-cpu, tiktoken, python-dotenv)

notebooks/ — interaktive Übungen (Schritt für Schritt)

code/ — eigenständige Python-Scripte (z. B. rag_example.py, agent_demo.py)

API-Keys & Sicherheit
Einige Notebooks nutzen APIs (z. B. OpenAI). Lege sensiblen Schlüssel in einer .env oder in Colab-Variablen ab:

ini
Code kopieren
OPENAI_API_KEY=sk-...
Niemals API-Keys in öffentlichen Repositories committen.

Empfohlener Workflow

Starte das zugehörige Notebook (lokal oder Colab).

Führe die Zellen aus, experimentiere mit Parametern.

Prüfe die Beispiel-Skripte im Ordner code/ und erweitere sie für eigene Aufgaben.

Support & Kontakt
Bei technischen Problemen oder Fragen zum Kurs:

E-Mail: estaghvirou.b@gmail.com

Telefon: +49 176 / 31591931

Alternativ über das Kontaktformular auf der Kursseite.

Lizenz & Nutzung
Die Kursmaterialien sind für persönliche Lernzwecke vorgesehen. Bitte nicht ohne Zustimmung kommerziell weiterverbreiten. Für Kooperationen oder Firmenlizenzen kontaktiere AI & Data Solutions.

Viel Erfolg und viel Spaß beim Lernen!
