# Hluboké učení

Cílem předmětu je seznámit studenty s metodami hlubokého učení, hlubokých neuronových sítí a dalších metod pokročilého
zpracování dat. Studenti budou seznámeni se základními a pokročilými metodami hlukového učení a jejich aplikací nad
vektorovými, obrazovými, textovými a dalšími daty.

Odkaz na stránku [předmětu](https://homel.vsb.cz/~pla06/) s přednáškami a na [cvičení](https://homel.vsb.cz/~svo0175/).

## Vytvoření a spuštění virtuálního prostředí

Pro tento projekt byl použit Python 3.12.3 a TensorFlow 2.18.0, společně s PyTorch 2.6.0. Pro spuštění je zapotřebí mít
nainstalovanou CUDA verzi 12.6.

### Vytvoření virtuálního prostředí

```bash
python3 -m venv .venv
```

### Aktivace virtuálního prostředí

```bash
source .venv/bin/activate
```

### Instalace závislostí

#### Závislosti pro Jupyter Notebook

```bash
pip install jupyter "jupyterlab>=3" "ipywidgets>=7.6"
``` 

#### Závislosti pro TensorFlow

Toto je zapotřebí pouze v případě, že máte nainstalovanou CUDA a chcete používat GPU akceleraci.

```bash
pip install tensorflow[and-cuda]
```

#### Závislosti pro PyTorch

Toto by mělo bát ošetřeno extra indexem v [requirements.txt](requirements.txt). Pokud ne, použijte následující příkaz
pro instalaci PyTorch s CUDA 12.6:

```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
```

### Ostatní závislosti

```bash
pip install -r requirements.txt
```

#### Ověření instalace

##### TensorFlow

```bash
python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
``` 

##### PyTorch

```bash
python -c "import torch; print(torch.__version__)"
python -c "import torch; print(torch.cuda.is_available())"
```