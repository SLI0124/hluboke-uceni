# Zadání

Jednotilivé úkoly jsou popsány v jednotlivých souborech. Všechny úkoly na konci každého notebooku. Jedntlivé notebooky
obsahují detailní popis problematiky a na konci je vždy zadán úkol. Úkoly jsou zaměřeny na danou tématiku.

Osnova a zadání je převzato
z [GitHubu](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/8bd38c65ee2f88734e83486bf2b2c523da150ee5/README.md)
předmětu.

## Cvičení 1

## Exercise 1

V tomto cvičení prozkoumáme základní koncepty TensorFlow 2 a Keras pomocí praktických příkladů s datasetem MNIST

- tzv. "Hello World" hlubokého učení. Zaměříme se na:

**Klíčové koncepty**

- 🚀 Vytvoření a trénování základní neuronové sítě pro klasifikaci číslic
- 📒 Porozumění validačním strategiím pro hodnocení modelů
- 📊 Zkoumání komplexity modelů a jejího vlivu na výkon
- ✅ Návrh optimálních architektur s využitím plně propojených vrstev

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_01.ipynb)

## Cvičení 2

Cílem cvičení je naučit se řešit regresní problémy pomocí hlubokého učení. Naše modely použijeme
na datasetu [Auto MPG](https://archive.ics.uci.edu/ml/datasets/auto+mpg).

**Klíčové koncepty**

* ⛽ Regresní úloha predikce spotřeby paliva
* 💾 Dataset Auto MPG z repozitáře UCI Machine Learning
* 🚗 Predikce efektivity spotřeby paliva vozidel
* 🧪 Použití poskytnutých dat k trénování regresních modelů ANN

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_02.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_02.ipynb)

## Cvičení 3

Cílem cvičení je naučit se využívat základní architekturu založenou na konvolučních vrstvách a jak klasifikovat obrazová
data.

**Klíčové koncepty**

* 🎯 Základy konvolučních neuronových sítí
* 📊 Práce s datasetem CIFAR-10
* ✅ Techniky validace modelů
* 🔄 Batch normalization v Kerasu

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_03.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_03.ipynb)

## Cvičení 4

Cílem cvičení je naučit se používat transferové učení pro obrazová data. Ve druhé části se podíváme na klasifikaci
časových řad pomocí CNN.

**Základní koncepty**

* 🧠 Techniky transferového učení v CNN
* 📈 1D konvoluce pro zpracování časových řad
* 📊 Využití datasetu CIFAR-10
* ⏱️ Dataset FordA pro úlohy klasifikace časových řad

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_04.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_04.ipynb)

## Cvičení 5

Cílem cvičení je naučit se používat architektury Autoencoder a Variational Autoencoder na obrazových datech k
generování nových instancí obrazových dat a detekci anomálií.

**Základní koncepty**

* 🖼️ Autoencodery pro rekonstrukci obrazu
* 🔀 Variational Autoencodery pro generování obrazů
* 🔢 Dataset MNIST pro úlohy zpracování obrazu
* ⚙️ Implementace autoencoderů založených na CNN

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_05.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_05.ipynb)

## Cvičení 6

Cílem cvičení je naučit se používat rekurentní neuronové sítě (RNN) pro analýzu textových dat, konkrétně se zaměřením
na úlohy sentimentální analýzy pomocí dat z Twitteru.

**Základní koncepty**

* 🧠 Rekurentní neuronové sítě pro zpracování sekvencí
* 📝 Sentimentální analýza textových dat
* 🐦 Využití datasetu Twitter
* 🔤 GloVe vektory pro reprezentaci slov
* 📊 Klasifikace textu podle sentimentu

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_06.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_06.ipynb)

## Cvičení 7

Cílem tohoto cvičení je naučit se vytvářet neřízené vektorové reprezentace slov pomocí metody Word2Vec Skip-Gram a
implementovat rekurentní neuronové sítě (RNN) pro generování textu s využitím knih o Harrym Potterovi jako datasetu.

**Základní koncepty**

* 🧠 Model Word2Vec Skip-Gram pro vytváření slovních embeddingů
* 📚 Korpus Harryho Pottera pro trénování embeddingů
* 🔤 Analýza vztahů mezi slovy v embeddingovém prostoru
* ⚡ Generování textu pomocí RNN založených na znacích
* 📝 Vytváření příběhů ve stylu Harryho Pottera pomocí generativních modelů

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_07.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_07.ipynb)

## Cvičení 8

Cílem tohoto cvičení je naučit se implementovat a využívat mechanismy pozornosti v modelech hlubokého učení, se
zaměřením
na to, jak tyto techniky umožňují modelům selektivně se soustředit na nejrelevantnější části vstupních dat.

**Základní koncepty**

* 🧠 Základy mechanismu pozornosti a jeho matematické principy
* 🔍 Typy mechanismů pozornosti (Self-attention, Dot-product)
* 📊 Aplikace v oblasti zpracování přirozeného jazyka
* ⚙️ Implementace modelů založených na mechanismech pozornosti

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_08.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_08.ipynb)

## Cvičení 9

Toto cvičení se zaměřuje na implementaci a využití transformačních modelů pomocí knihovny HuggingFace ve spojení s
TensorFlow 2. Prozkoumáme, jak využít předtrénované modely pro úlohy zpracování přirozeného jazyka.

**Základní koncepty**

* 🤗 Knihovna HuggingFace a její ekosystém
* 🔧 Integrace modelů HuggingFace s TensorFlow 2
* 📊 Doladění předtrénovaných modelů pro konkrétní NLP úlohy
* 🚀 Praktické aplikace transformačních modelů

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_09.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_09.ipynb)

## Cvičení 10

Toto cvičení se zaměřuje na implementaci konvolučních neuronových sítí (CNN) pro úlohy lokalizace objektů a na průzkum
výkonné architektury YOLOv8. Naučíme se detekovat a přesně lokalizovat objekty na obrázcích a videích a následně tyto
koncepty aplikujeme pomocí špičkového modelu v reálných scénářích.

**Základní koncepty**

* 🖼️ Základy lokalizace objektů a regrese ohraničovacích boxů
* 🧠 Architektury CNN pro efektivní extrakci rysů a detekci objektů
* 📦 Architektura a schopnosti modelu YOLOv8
* 🔍 Praktická implementace lokalizace objektů v reálných aplikacích
* 🛠️ Trénování a doladění YOLOv8 na vlastních datasetech

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_10.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_10.ipynb)

## Cvičení 11

Toto cvičení se zaměřuje na predikci časových řad pomocí technik hlubokého učení. Tyto metody aplikujeme na předpověď
spotřeby zemního plynu, přičemž budeme pracovat s předzpracovaným datasetem z předchozích cvičení.

**Základní koncepty**

* 📈 Predikce časových řad pomocí hlubokého učení
* ⛽ Předpověď spotřeby zemního plynu
* 📊 Využití předzpracovaných datasetů časových řad
* 🧠 Implementace modelů hlubokého učení pro časová data
* 🛠️ Praktická aplikace hlubokého učení na reálné predikční problémy

Surový dataset je dostupný na [vsb.ai](https://vsb.ai/natural-gas-forecasting), v tomto cvičení však použijeme jeho
předzpracovanou verzi.

> [Jupyter Notebook](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_11.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_11.ipynb)

## Cvičení 12

Cílem této přednášky je získat přehled o možnostech v oblasti generativní umělé inteligence (GenAI).

> [Jupyter Notebook - Stable Diffusion](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_12_01.ipynb)

> [Google Colab - Stable Diffusion](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_12_01.ipynb)

> [Jupyter Notebook - LLM](https://github.com/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_12_02.ipynb)

> [Google Colab - LLM](https://colab.research.google.com/github/rasvob/VSB-FEI-Deep-Learning-Exercises/blob/main/dl_12_02.ipynb)