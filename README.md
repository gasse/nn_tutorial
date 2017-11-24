# CONFIGURATION

## Machine CPE

Bootez sous Linux.

Activez l'environnement du TP:
```sh
export PATH="/softwares/INFO/Module_ML/miniconda3/bin:$PATH"
```

## Machines perso (Linux)

Installez **miniconda**:
```sh
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash ./Miniconda3-latest-Linux-x86_64.sh
```

Installez les paquets suivants:
```sh
conda install jupyter=1.0.0 matplotlib=2.1.0 scikit-learn=0.19.1 
conda install pytorch=0.2.0 torchvision=0.1.9 -c soumith
```

## IDE

Lancez un serveur ***jupyter***:
```sh
jupyter notebook
```

# Notebooks

Suivez les notebooks suivants, dans l'ordre:
1. `pytorch.ipynb`
2. `mnist_from_scratch.ipynb`
3. `mnist.ipynb`

Rendu: vos notebooks avec votre code, réponse aux questions et résultats.

```
File -> Download as -> Notebook (ipynb)
```

Compressez votre fichier dans une archive ZIP, avec pour nom `TP_NN_VOSNOMSDEFAMILLE.zip`.

