# 1000devs - AI/ML Aula 03

**Iniciativa 1000devs Aula 03 - Agentes**

> Este repositório é parte da iniciativa 1000devs, uma colaboração anual da Johnson & Johnson e do Hospital Israelita Albert Einstein para formar 1000 desenvolvedores no Brasil. Tive a oportunidade de apresentar os fundamentos, conceitos, campo e as ferramentas da Inteligência Artificial para os alunos.

Este repositório contém exemplos práticos de uso simples de **Agentes** usando o **Agent Framework SDK** da **Microsoft**.

Referência: [Agent Framework SDK - Microsoft](https://learn.microsoft.com/pt-br/agent-framework/overview/?pivots=programming-language-python)

Repositório oficial do SDK: [Agent Framework SDK - GitHub](https://github.com/microsoft/agent-framework)

## 🛠️ Instalação das ferramentas base

### 💻 Instalando o Visual Studio Code

Baixe o instalador do Visual Studio Code aqui [Visual Studio Code](https://code.visualstudio.com/) para seu sistema operacional (Windows, Linux, MacOS) e siga as instruções de instalação.

### 🔌 Instalando extensões base para o Visual Studio Code

[Python Data Science](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.python-ds-extension-pack)

[Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

### ⭐ Extensões adicionais recomendadas para o Visual Studio Code

[Portuguese (Brazil) Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-pt-BR)

[VS Code Speech](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-speech)

[.gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)

[Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)

[GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

[Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)

[Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)

[XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

[YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

### 📦 Instalando o Git

Baixe o instalador do git aqui [Git Downloads](https://git-scm.com/downloads) para seu sistema operacional (Windows, Linux, MacOS) e siga as instruções de instalação.

### 🐍 Instalando o Anaconda ou CondaForge (Gerenciador de ambientes Python)

**Para usar [Anaconda](https://www.anaconda.com/)** como gerenciador de ambientes:

Baixe o instalador aqui [Anaconda Downloads](https://www.anaconda.com/products/distribution) escolha Miniconda como distribuição, selecione o seu sistema operacional (Windows, Linux, MacOS) e siga as instruções de instalação.

**Para usar [CondaForge](https://conda-forge.org/)** como gerenciador de ambientes:

Baixe o instalador aqui [CondaForge Downloads](https://conda-forge.org/download/) selecione o seu sistema operacional (Windows, Linux, MacOS) e siga as instruções de instalação.

Após a instalação, inicialize o ambiente com o comando:

```bash
conda init
```

Verifique se o conda foi instalado corretamente com o comando:

```bash
conda --version
```

Verifique a versão do Python instalada no ambiente base com o comando:

```bash
python --version
```

### 🤖 Criando seu ambiente virtual para Agentes

Vamos criar um ambiente virtual chamado `py12ag` com Python 3.12

```bash
conda create -n py12ag python=3.12
```

Ative o ambiente virtual com o comando:

```bash
conda activate py12ag
```

Verifique se o ambiente virtual está ativo com o comando:

```bash
conda info --envs
```

#### 📚 Instalando pacotes essenciais para AI/ML

Com o ambiente virtual `py12ag` ativo, instale os pacotes essenciais para desenvolvimento em Machine Learning com o comando:

Bibliotecas base para ML

```bash
pip install numpy pandas matplotlib scikit-learn jupyter seaborn requests faker jupyterlab notebook ipywidgets pyarrow
```

Agent Framework SDK

```bash
pip install agent-framework --pre
```

#### 📓 Usando notebooks Jupyter através do utilitário Jupyter Notebook

Inicie o Jupyter Notebook com o comando:

```bash
jupyter notebook
```

Navegue até o diretório `./samples` para acessar os notebooks de exemplo.

#### 📝 Usando notebooks Jupyter através do Visual Studio Code

Localize na aba `Explorador de arquivos` o diretório `./samples` para acessar os notebooks de exemplo.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com melhorias, correções ou novos exemplos.
