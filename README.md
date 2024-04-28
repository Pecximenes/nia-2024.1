# Introdução


Este repositório representa os trabalho e exercícios propostos na disciplina de Noções de Inteligência Artificial ofertado pela UnB. Para executar os cadernos é necessário utilizar o gerenciador de pacotes conda, além de algumas bibliotecas como: pandas, numpy, PyTorch, TensorFlow e d2l.


## Instalando o Miniconda

Neste projeto foi utilizado o Miniconda, que usa como base o gerenciado conda. Para instalá-lo em sistemas Linux baseados em ubuntu, basta executar os seguintes comandos no terminal:

```
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

Depois de instalar, é necessário inicializar o recém instalado Miniconda. Os comandos abaixo mostram como inicializar via bash e zsh shells:

```
~/miniconda3/bin/conda init bash
~/miniconda3/bin/conda init zsh
```


## Inicialização

• Abra um Terminal e execute `conda init`

• Feche o Terminal e abra novamente.

• Criação do ambiente D2L:

• Execute no terminal `conda create --name d2l python=3.9 -y`

• Substitua 3.9 pela versão instalada do Python

• Ative o ambiente com `conda activate d2l`

• Instale Pytorch e TensorFlow:

```
pip install torch==2.0.0 torchvision==0.15.1
pip install tensorflow==2.12.0 tensorflow-probability==0.20.0
```

• Instale o Pacote d2l
```
pip install d2l==1.0.3
```

• Em um terminal você deve conseguir iniciar o notebook com:
```
jupyter notebook
```