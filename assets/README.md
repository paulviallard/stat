## Installer Conda

Nous allons construire le même environnement Python pour tout le monde. Pour cela, nous allons installer un gestionnaire de paquets (et de versions de Python qui changent souvent...) nommé `conda`. Voici le lien pour installer le gestionnaire de paquets : [https://docs.conda.io/projects/conda/en/latest/index.html](https://docs.conda.io/projects/conda/en/latest/index.html).

**A noter** : Assurez-vous d'avoir la commande `conda` dans votre `PATH` à la fin de l'installation.

## Installer l'environnement

Ensuite, le fichier `env.yml` contient l'environnement que nous allons utiliser. Pour l'installer, lancez la commande :

```bash
conda env create -f env.yml
```

Conda va créer un environnement appelé STAT. Il faut l'activer avant chaque TP avec la commande :

```bash
conda activate STAT
```
