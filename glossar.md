# KI-Glossar

Ein kompakter Überblick über zentrale KI-Architekturen und Lernformen, mit Stärken und typischen Einsatzmöglichkeiten.

---

## Architekturen

| Architektur             | Kurzbeschreibung                                                                 | Stärken & Besonderheiten                                         |
|-------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------|
| ![Neural Net](img/perceptron.png) | **Perceptron**          | Einfachste Form eines künstlichen Neurons. Grundlage für komplexere Netzwerke.  | Linear trennbare Probleme lösen; Einstieg in neuronale Netze.   |
| ![Neural Net](img/neural_net.png) | **MLP (Multilayer Perceptron)** | Mehrschichtige Netze aus Perceptrons. Können komplexe nichtlineare Zusammenhänge lernen. | Vielseitig, robust, für strukturierte Daten geeignet.           |
| ![RNN](img/rnn.png) | **RNN (Recurrent Neural Network)** | Speichert frühere Eingaben im Speicherzustand – ideal für Sequenzen.         | Zeitliche Abhängigkeiten, z. B. in Musik oder Sprache.           |
| ![CNN](img/cnn.png) | **CNN (Convolutional Neural Network)** | Arbeitet mit Faltungen – stark bei visuellen oder räumlich strukturierten Daten. | Mustererkennung in Bildern, Noten, Spektrogrammen.              |
| ![Autoencoder](img/autoencoder.png) | **Autoencoder**         | Lernen, Daten kompakt zu repräsentieren (Kompression + Rekonstruktion).        | Feature-Extraktion, Anomalie-Erkennung, Vorverarbeitung.        |
| ![GAN](img/gan.png) | **GANs (Generative Adversarial Networks)** | Zwei Netzwerke „kämpfen“ miteinander: Generator vs. Diskriminator.          | Realistische Datengenerierung (z. B. Musik, Bilder).             |
| ![Reinforcement Learning](img/reinforcement_learning.png) | **Reinforcement Learning (RL)** | Agent lernt durch Belohnung/Bestrafung – wie in einem Spiel.                 | Selbstständiges Lernen, Strategieentwicklung, Self-Play.        |
| ![Transformer](img/transformer.png) | **Transformer**         | Nutzt Selbstaufmerksamkeit („Attention“) statt Zustandsweitergabe über Zeit. | Erkennt globale Abhängigkeiten **ohne sequenzielle Verkettung**; starke Leistung bei langen Eingaben; parallele Verarbeitung. |
| ![Diffusion](img/diffusion.png) | **Diffusion Models**    | Lernen, Daten schrittweise zu „ent-rauschen“, um neue Beispiele zu erzeugen.   | Sehr realistische Bild- und Audio-Generierung (z. B. Musik).    |

---

## Lernformen

| Begriff                        | Erklärung                                                                 | Typische Einsatzbereiche                                         |
|-------------------------------|---------------------------------------------------------------------------|------------------------------------------------------------------|
| **Supervised Learning**       | Lernen mit gelabelten Daten (Eingabe + gewünschte Ausgabe, vgl. Karteikarten).              | Klassifikation, Vorhersagen, Bewertung.                         |
| **Unsupervised Learning**     | Lernen ohne Vorgaben – Muster und Strukturen in Daten finden.            | Clustering, Feature-Reduktion, z. B. Stil-Analyse.              |
| **Self-Supervised Learning**  | Labels werden aus den Daten selbst gewonnen (z. B. Satzhälften ergänzen).| Sprach- & Musikmodelle wie GPT, MusicLM.                        |
| **Reinforcement Learning**    | (siehe oben) Lernen durch Handeln & Feedback (Belohnung).                 | Spielen, Improvisation, adaptive Systeme.                       |
| **Few-Shot / Zero-Shot Learning** | Lernen mit sehr wenigen oder gar keinen Beispielen.                     | Anpassung an neue Aufgaben ohne langes Nachtraining.            |
| **Transfer Learning**         | Vortrainiertes Wissen wird auf neue Aufgaben übertragen.                 | Schnelle Anwendung vorhandener Modelle auf Musikpädagogik.      |

---

## Ergänzende Begriffe

| Begriff                | Erklärung                                                                 |
|------------------------|---------------------------------------------------------------------------|
| **Pattern Recognition**| Fähigkeit, wiederkehrende Muster zu erkennen – z. B. in Melodien.         |
| **Latent Space**       | Abstrakter Raum, in dem Daten „verdichtet“ und strukturiert vorliegen.   |
| **Underfitting**         | Modell lernt Trainingsdaten zu grob – schlechte Leistung auf neuen Daten. |
| **Overfitting**        | Modell lernt Trainingsdaten zu genau – schlechte Generalisierung.         |
| **Bias in Daten**      | Vorurteile oder Verzerrungen in den Trainingsdaten – ethisches Risiko.   |
| **Attention Mechanismus**| Kern des Transformers – entscheidet, worauf sich das Modell konzentriert.|
| **Turing Test**         | Test, ob eine Maschine menschliches Verhalten imitieren kann.            |
| **Turing Trap**        | Gefahr, dass KI menschliche Tätigkeiten ersetzt, anstatt sie zu erweitern. |

---
