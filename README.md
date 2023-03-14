# Guia-de-Instalação-SisIntel-2023.1
---
Insper: Laboratório Ágil
date: Março 2023
---

Neste documento estamos descrevendo o passo a passo para a instalação do Anaconda Navigator, junto com as bibliotecas necessárias para a Aula Eletiva de Sistemas Inteligentes de Extração de Conhecimentos.

Seguindo este tutorial, você estará instalando a mesma infraestrutura que utilizamos nas NUCs do Laboratório de Desenvolvimento Ágil

## :warning: MESMO COM A INFRAESTRUTURA CORRETAMENTE INSTALADA, UTILIZE AS NUCs DURANTE AS AULAS. ESTE GUIA EXISTE APENAS PARA AUXILIAR NA INSTALAÇÃO CASO FOREM RODAR AS AULAS E PROJETOS EM OUTRAS MÁQUINAS FORA DO PERÍODO DA AULA E FORA DO LABORATÓRIO :warning:

---

## Passo 1: Instalando o Anaconda Navigator (Windows):

### 1.a: Removendo Versões antigas do Anaconda:
É recomendado desinstalar qualquer versão do Anaconda do seu computador antes de começar este tutorial, para evitar conflitos indesejados durante o processo. Para tal, 
utilize os passos que estão disponíveis no site do Anaconda, abaixo:

https://docs.anaconda.com/anaconda/install/uninstall/

#### Caso esteja seguro de que seu Anaconda não possui nenhuma alteração indesejada, ou já realizou a instalação do mesmo sem problemas, pular para o Passo 2.

### 1.b: Instando o Anaconda Navigator:
Para instalar o Anaconda, iremos baixar o arquivo .exe do site do Anaconda, linkado abaixo, e seguir com sua instalação.

**Windows:** https://www.anaconda.com/products/distribution#windows

**MacOS:** https://www.anaconda.com/products/distribution#macos

**Ubuntu:** Siga o passo a passo nesta página: https://docs.anaconda.com/anaconda/install/linux/

### Windows

Após baixar o arquivo.exe no site do Anaconda, execute o mesmo e siga o passo a passo da Instalação. 

Quando o instalador perguntar se deseja instalar apenas para você ou para todos os usuários, escolha APENAS PARA VOCÊ, e depois, em opções avançadas, marque a opção de adicionar o Anaconda ao PATH e,caso não possua outro Python instalado em sua máquina, ou queira utilizar o python do anaconda como seu python padrão, marque a segunda opção. Em caso de dúvida, não marque a opção do Python, apenas o PATH.

Quando terminar a instalação, seu Anaconda já estará pronto, e você pode seguir para o próximo passo.

### MacOS
#### 👷‍♂️Em Breve

## Passo 2: Instalando as bibliotecas necessárias para SisIntel

Ok, estamos com nosso anaconda instalado. Para verificar, basta procurar pelo Anaconda Prompt, na sua barra de pesquisa, ou dentro da pasta do Anaconda ou na área de trabalho. Porém, mesmo com o pacote de bibliotecas padrão que o Anaconda nos dá, precisamos instalar mais algumas bibliotecas para rodar as aulas dentro do Jupyter-Notebook.

Abra seu **Anaconda Prompt**(não é necessário executar o Anaconda Navigator), e coloque os comando abaixo para instalar as bilbiotecas

### ⚠️ Não executar estes comandos no PowerShell ou no Prompt de Comando do Windows ⚠️
### ⚠️ Algumas bibliotecas podem levar um tempo maior para instalar, tenha paciência, e tenha certeza que está conectado na internet antes de começar⚠️

* **Biblioteca Pandas:** 
```
pip install pandas==1.2.2 
```
* **Bibliotecas Seahorn, Yahoo-fin e Python-bcb:** 
```
pip install seaborn==0.11.2 yahoo-fin python-bcb==0.1.7
```
* **Biblioteca Scikit-learn:** 
```
pip install scikit-learn==0.24.2
```
* **Biblioteca Plotly:** 
```
pip install plotly
```
* **Biblioteca Dash** 
```
pip install dash
```
* **Biblioteca Dash** 
```
pip install dash_bootstrap_components
```

## ⚠️ No momento ainda estamos adicionando mais bibliotecas conforme o professor nos passa com o passar das aulas, fique de olho aqui para ver se existem novas bibliotecas que precisam ser adicionadas no seu Anaconda ⚠️

Com as bibliotecas instaladas, seu anaconda deve estar pronto para uso. Basta executar o Jupyter-Notebook e importar as bibliotecas nos seus códigos 👍
