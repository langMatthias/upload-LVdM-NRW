# KI-Glossar

Ein kompakter Überblick über zentrale KI-Architekturen und Lernformen, mit Stärken und typischen Einsatzmöglichkeiten.

---

## Generelle Stärken von KI-Systemen
- Verarbeiten große Mengen an Daten effizient  
- Lernen aus Beispielen statt Regeln  
- Erkennen verborgene Muster oder Strukturen  
- Arbeiten rund um die Uhr (z. B. als Assistenten)  
- Unterstützen kreative Prozesse mit Vorschlägen oder Varianten  
- Machen Vorschläge, ohne zu bewerten oder zu kritisieren  

## Architekturen

| Architektur | Kurzbeschreibung | Individuelle Stärken & Besonderheiten |
|------------|------------------|---------------------------|
| <img src="img/perceptron.png" alt="Perceptron" width="40"/> | **Perceptron** | Einfachste Form eines künstlichen Neurons. Grundlage für komplexere Netzwerke.  <br>- Löst linear trennbare Probleme <br>- Sehr verständlich, ideal für Einstiege |
| <img src="img/neural_net.png" alt="MLP" width="40"/> | **MLP (Multilayer Perceptron)** | Mehrschichtige Netze aus Perceptrons. Können komplexe nichtlineare Zusammenhänge lernen. <br>- Vielseitig & robust <br>- Für strukturierte Daten geeignet <br>- Lernen durch Beispiele statt Regeln |
| <img src="img/cnn.png" alt="CNN" width="40"/> | **CNN (Convolutional Neural Network)** | Arbeitet mit Faltungen – stark bei visuellen oder räumlich strukturierten Daten. <br>- Erkennen Muster, Positionen & Kanten <br>- Sehr gut für Notenbilder & Spektrogramme <br>- Filtern wichtige Informationen automatisch |
| <img src="img/autoencoder.png" alt="Autoencoder" width="40"/> | **Autoencoder** | Lernen, Daten kompakt zu repräsentieren (Kompression + Rekonstruktion). <br>- Feature-Extraktion & Anomalie-Erkennung <br>- Datenvereinfachung & Vorverarbeitung <br>- Können Varianten aus bekannten Daten erzeugen |
| <img src="img/rnn.png" alt="RNN" width="40"/> | **RNN (Recurrent Neural Network)** | Speichert frühere Eingaben im Speicherzustand – ideal für Sequenzen. <br>- Modelliert zeitliche Abfolgen (z. B. Melodien, Sprache) <br>- Hat ein „Gedächtnis“ <br>- Gute Wahl für kontextabhängige Vorhersagen |
| <img src="img/transformer.png" alt="Transformer" width="40"/> | **Transformer** | Nutzt Selbstaufmerksamkeit („Attention“) statt Zustandsweitergabe über Zeit. <br>- Erkennt globale Zusammenhänge <br>- Verarbeitet Eingaben parallel <br>- Besonders stark bei längeren Texten oder Musikstücken |
| <img src="img/reinforcement_learning.png" alt="RL" width="40"/> | **Reinforcement Learning (RL)** | Agent lernt durch Belohnung/Bestrafung – wie in einem Spiel. <br>- Entwickelt eigene Strategien durch Feedback <br>- Eignet sich für interaktive & explorative Szenarien <br>- Kann selbstständig lernen (z. B. durch „Self-Play“) |
| <img src="img/gan.png" alt="GAN" width="40"/> | **GANs (Generative Adversarial Networks)** | Zwei Netzwerke „kämpfen“ miteinander: Generator vs. Critic. <br>- Erzeugen neue & realistische Inhalte <br>- Lernen den Stil von Beispielen <br>- Fördern kreative & experimentelle Anwendungen |
| <img src="img/diffusion.png" alt="Diffusion" width="40"/> | **Diffusion Models** | Lernen, Daten schrittweise zu „ent-rauschen“, um neue Beispiele zu erzeugen. <br>- Sehr hochwertige Musik-/Bildgenerierung <br>- Arbeiten gut mit Unsicherheit <br>- Ideal für stilvolle, kontrollierte Kreativität |

---

## Lernformen

| Begriff                        | Erklärung                                                                 | Typische Einsatzbereiche                                         |
|-------------------------------|---------------------------------------------------------------------------|------------------------------------------------------------------|
| **Supervised Learning**       | Lernen mit gelabelten Daten (Eingabe + gewünschte Ausgabe, vgl. Karteikarten).              | Klassifikation, Vorhersagen, Bewertung.                         |
| **Unsupervised Learning**     | Lernen ohne Vorgaben – Muster und Strukturen in Daten finden.            | Clustering, Feature-Reduktion, z. B. Stil-Analyse.              |
| **Self-Supervised Learning**  | Labels werden aus den Daten selbst gewonnen (z. B. Satzhälften ergänzen).| Sprach- & Musikmodelle wie GPT, MusicLM.                        |
| **Reinforcement Learning**    | (siehe oben) Lernen durch Handeln & Feedback (Belohnung).                 | Spielen, Improvisation, adaptive Systeme.                       |
---

## Ergänzende Begriffe

| Begriff                | Erklärung                                                                 |
|------------------------|---------------------------------------------------------------------------|
| **Pattern Recognition**| Fähigkeit, wiederkehrende Muster zu erkennen – z. B. in Melodien.         |
| **Latent Space**       | Abstrakter Raum, in dem Daten „verdichtet“ und strukturiert vorliegen.   |
| **Underfitting**         | Modell lernt Trainingsdaten zu grob – schlechte Leistung auf neuen Daten. |
| **Overfitting**        | Modell lernt Trainingsdaten zu genau – schlechte Generalisierung.         |
| **Bias in Daten**      | Vorurteile oder Verzerrungen in den Trainingsdaten – ethisches Risiko.   |
| **Large Language Models (LLMs)** | Große KI-Modelle, die auf Textdaten trainiert sind (z. B. GPT-3). | Sprachverarbeitung, Textgenerierung, Konversation.             |
| **Attention Mechanismus**| Kern des Transformers – entscheidet, worauf sich das Modell konzentriert.|
| **Turing Test**         | Test, ob eine Maschine menschliches Verhalten imitieren kann.            |
| **Turing Trap**        | Gefahr, dass KI menschliche Tätigkeiten ersetzt, anstatt sie zu erweitern. |

---
