# CNN-basierte Klassifikation von Waldbränden

## Anwendungsbeispiel

Ziel ist die **automatisierte Klassifikation von Satellitenbildern** in die Klassen:

- **"Waldbrand"**
- **"Kein Waldbrand"**

Dies dient als Beitrag zum **Umweltschutz** und zur Verbesserung des **Katastrophenmanagements**.

---

## Datensatz

- **Quelle**: [Kaggle – Wildfire Prediction Dataset](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset/)
- **Herkunft**: Kanadische Regierungsdaten
- **Größe**:
  - 22.710 Bilder mit „Wildfire“
  - 20.140 Bilder mit „No Wildfire“
- **Format**: 350×350 Pixel, Farbbilder
- **Aufteilung**:
  - 70 % Training
  - 15 % Validierung
  - 15 % Test
- **Lizenz**: Creative Commons 4.0 Attribution (CC-BY)
- **Bedingung für Wildfire-Label**: Fläche > 0,01 Acres

---

## Forschungsfragen

1. **Modellvergleich**:  
   Welche CNN-Architektur erreicht die höchste Genauigkeit?  
   – Vergleich von **eigenem CNN-Modell** mit **Transfer Learning** (z. B. **ResNet50**)

2. **Einfluss von Data Augmentation**:  
   Wie wirkt sich **Rotation**, **Spiegelung** und **Helligkeitsveränderung** auf die Klassifizierungsgenauigkeit aus?

3. **Modelleinsicht mittels Grad-CAM**:  
   Welche Bildbereiche und Merkmale nutzt das Modell hauptsächlich zur Klassifikation?

---

## Einordnung

- **Lernverfahren**:  
  Überwachtes Lernen (Supervised Learning), da **gelabelte Daten** verwendet werden.

- **Problemstellung**:  
  **Binäre Bildklassifikation** mit Convolutional Neural Networks (CNNs).  
  Fokus liegt auf der **Mustererkennung in Satellitenbildern**.

