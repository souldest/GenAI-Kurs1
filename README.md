# LLMs, RAG & AI-Agenten in Python — Kurs: README (DE)

**Willkommen zum Kurs „LLMs, RAG & AI-Agenten in Python“ von AI & Data Solutions.**  
Dieser Kurs enthält Videolektionen, interaktive Jupyter-Notebooks und praktische Code-Beispiele.

---

## Inhalt des Kurs-Ordners
Struktur (Beispiel):

LLMs-RAG-AI-Agents-Kurs/
├── 01_Einfuehrung/
│ ├── video_01_willkommen.mp4
│ └── notebooks/01_intro_llms.ipynb
├── 02_LLMs_Grundlagen/
│ ├── video_02_openai_api.mp4
│ ├── notebooks/02_openai_basics.ipynb
│ └── code/llm_prompts.py
├── 03_RAG/
│ ├── video_03_rag_overview.mp4
│ ├── notebooks/03_faiss_demo.ipynb
│ └── code/rag_example.py
├── 04_AI_Agenten/
│ ├── video_04_agents.mp4
│ ├── notebooks/04_agent_demo.ipynb
│ └── code/agent_demo.py
├── 05_Abschlussprojekt/
│ └── notebooks/05_final_project.ipynb
├── requirements.txt
└── README.de.md

yaml
Code kopieren

---

## Voraussetzungen
- Grundkenntnisse in Python (Variablen, Funktionen, Pakete, einfache Datenmanipulation mit Pandas empfohlen)
- Optional: Grundverständnis von Machine Learning / Modellen
- Empfohlen: Python 3.8+ und ein moderner Editor (VS Code / JupyterLab)

---

## Installation (lokal)
1. Repository/Ordner herunterladen.
2. Virtuelle Umgebung erstellen:
   ```bash
   python -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
Abhängigkeiten installieren:

bash
Code kopieren
pip install -r requirements.txt
Jupyter starten:

bash
Code kopieren
jupyter lab
oder

bash
Code kopieren
jupyter notebook
Verwendung in Google Colab (ohne lokale Installation)
Öffne das gewünschte Notebook (.ipynb) in GitHub → Open in Colab (oder lade das Notebook in Colab hoch).

Installiere im Colab-Notebook ggfs. zusätzliche Pakete per !pip install -r requirements.txt (oder einzeln).

Wichtige Dateien
requirements.txt — benötigte Python-Pakete (z. B. openai, langchain, chromadb, faiss-cpu, tiktoken, python-dotenv)

notebooks/ — interaktive Übungen (Schritt für Schritt)

code/ — eigenständige Python-Scripte (z. B. rag_example.py, agent_demo.py)

videos/ oder *.mp4 — Lektionen (falls lokal bereitgestellt). Videos können alternativ per Link bereitgestellt werden.

API-Keys & Sicherheit
Einige Notebooks nutzen APIs (z. B. OpenAI). Lege sensiblen Schlüssel in einer .env oder in Colab-Variablen ab:

ini
Code kopieren
OPENAI_API_KEY=sk-...
Niemals API-Keys in öffentlichen Repositories committen.

Empfohlener Workflow
Schau das Video zur Lektion.

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
