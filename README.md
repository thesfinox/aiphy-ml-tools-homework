# Code for AIPHY24 phd school
# Machine Learning Tools

> **Authors**: [Andrea Ciardiello](andrea.ciardiello@iss.it) (ISS) [Stefano Giagu](stefano.giagu@uniroma1.it) (Sapienza Rome university)
>
> **Event**: _Artificial Intelligence and Modern Physics. A Two-Way Connection._


You can find here the materials for the the doctoral school _AIPHY_ (_Artificial Intelligence and Modern Physics. A Two-Way Connexion_, Monopoli, Bari, Italy), from 30/09/2024 to 04/10/2024, for the course of **Machine Learning Tools**.
Hands-on sessions are presented as _Jupyter_ notebooks.

## Installation
_Jupyter_ notebooks are supposed to be used on the CINECA school account. Follow the guide to run the forward2 bash script.

Notebooks should also work fine in Colab.

On your login node home, create a folder
```bash
mkdir MLtools
cd MLtools
```

Then, clone this repository
```bash
 git clone https://github.com/pumazzo/AIPHY24.git
```

The notebook should automatically make a local copy of the data from my account on the CINECA machine

If the 30 minutes time constrain for the _slurm_ process is too binding, you can modify it going into the _leonardo/jupyter-conda_.

Look for this line and change it to a larger time

```bash
#SBATCH -t 02:30:00
```
