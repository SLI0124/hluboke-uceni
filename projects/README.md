# Projekty

## První projekt - CNN

### Cíl projektu
Využití modelů hlubokého učení pro zpracování dat a porovnání přístupů.

### Požadavky (10-20 bodů)

#### Analýza dat
- Popis datové sady (počet obrázků, tříd, vyváženost)
- Analýza vzorků

#### Metriky
- Volba metrik (přesnost, precize, recall, F1)
- Zdůvodnění klíčové metriky

#### Modely
1. **Vlastní model**
    - Vlastní architektura
    - Dokumentace experimentů
    - Analýza vlivu komponent

2. **Transfer learning**
    - Využití předtrénovaného modelu
    - Doladění pro danou úlohu
    - Srovnání s vlastním modelem

#### Shrnutí poznatků

### Odevzdání
- Jupyter Notebook s popisem nebo PDF + kód
- Časová náročnost: 5-10 hodin
- **Termín: 20. 4. 2025**

## Druhý projekt - RNN

### Cíl projektu
Využití rekurentních neuronových sítí pro zpracování textových dat a porovnání přístupů.

### Požadavky (10-20 bodů)

#### Analýza dat
- Popis datové sady (počet instancí, tříd, vyváženost)
- Analýza textových vzorků

#### Metriky
- Volba metrik (přesnost, precize, recall, F1)
- Zdůvodnění klíčové metriky vzhledem k vyváženosti tříd a úloze

#### Modely
1. **Vlastní model**
    - Vlastní architektura RNN
    - Dokumentace experimentů a ladění hyperparametrů
    - Analýza vlivu komponent (BatchNormalization, velikosti vrstev, optimalizátory)

2. **Transfer learning**
    - Využití předtrénovaných embedingů (GloVe, Word2Vec, FastText) nebo transformerů
    - Doladění modelu pro danou úlohu
    - Srovnání s vlastním modelem

#### Shrnutí poznatků

### Odevzdání
- Jupyter Notebook s popisem nebo PDF + kód
- Časová náročnost: 5-10 hodin
- **Termín: 25. 5. 2025**

## Třetí projekt - vlastní volba

### Cíl projektu 
Vytvoření důkladnější analýzy zvolené datové sady a aplikace hlubokého učení.

### Požadavky (20-40 bodů)

#### Analýza dat
- Popis datové sady (počet instancí, tříd, vyváženost)
- Ukázky dat a jejich rozbor
- Volba dat z domény obrázků, textu nebo časových řad

#### Metriky
- Volba relevantních metrik (přesnost, precize, recall, F1)
- Zdůvodnění klíčové metriky vzhledem k vyváženosti tříd a řešené úloze

#### Modely
1. **Vlastní modely**
    - Vytvoření vlastních architektur jako výchozí bod
    - Systematické ladění hyperparametrů (batch size, optimalizátory)
    - Doporučeno využití frameworků jako Optuna pro optimalizaci
    - Dokumentace experimentů pomocí tabulek a grafů

2. **Transfer learning**
    - Využití a doladění různých předtrénovaných modelů:
        - Pro obrazová data: modely z Keras applications (ResNet, EfficientNet) nebo YOLO
        - Pro textová data: HuggingFace Transformers, embedingy (GloVe, FastText, Word2Vec)
    - Možnost využití předzpracování dat, převzorkování či augmentace dat

3. **Sledování experimentů**
    - Implementace systematického sledování experimentů (Comet ML, Neptune.ai, W&B, MLflow nebo TensorBoard)
    - Dokumentace verzí modelů, hyperparametrů a metrik výkonu
    - Vytvoření dashboardů pro efektivní porovnání výsledků

4. **Inference pipeline**
    - Výběr nejlepšího modelu a jeho export (např. ONNX)
    - Implementace jednoduché inference třídy s metodou predict
    - Dokumentace použití pipeline s příklady

#### Shrnutí poznatků
- Porovnání modelů a shrnutí výsledků
- Nejzajímavější získané poznatky

### Odevzdání
- Jupyter Notebook s popisem nebo PDF + kód
- Časová náročnost: 10-15 hodin
- **Termín: 8. 6. 2025**
