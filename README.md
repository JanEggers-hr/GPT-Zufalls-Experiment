# GPT-Zufalls-Experiment
Wie stark beeinflusst der Zufall die Antwort des Sprachmodells GPT auf ein Logikrätsel? Das Notebook stellt dieselbe Rätselfrage immer wieder und versucht, die Antworten auszuwerten.

![./Bildschirmfoto_2024-01-09_um_07.48.39.png](Screenshot: Einstell-Widgets in Colab)

[Hier klicken, um zum Notebook zu kommen](./GPT_Antwort_auf_Rätselfrage_testen.ipynb)

Was man braucht: 
- Ein [API-Token von OpenAI](https://platform.openai.com/api-keys)
- Ein Google-Konto - oder eine lokale Jupyter-Installation - um das Notebook ausführen zu können

Was es macht: 
- Fragt über die OpenAI-API immer wieder die Antwort auf ein Rätsel ab - mit einstellbarem Sprachmodell
- Extrahiert dann aus den Antworten die Zahl der Brüder und Schwestern, auf die das Sprachmodell tippt
