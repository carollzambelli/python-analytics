# python-analytics


## Sobre o projeto

> **Manaus é mesmo mais quente que o Rio? Choveu mais em Recife ou em Porto Alegre em
> janeiro? Qual cidade tem o clima mais "imprevisível"?**

Todo mundo tem um palpite sobre o clima da própria cidade. Neste projeto, você vai
**trocar o palpite por dados** e, de quebra, percorrer o mesmo caminho que um cientista de
dados percorre no dia a dia: buscar dados reais, limpá-los, transformá-los e, por fim,
contar uma história com eles.

Vamos trabalhar com dados climáticos **reais**, hora a hora, de janeiro de 2025, para
**5 capitais brasileiras** com climas bem diferentes:

| Cidade | Região | O que esperar |
|---|---|---|
| ☀️ Manaus | Norte | Equatorial: quente e úmido o tempo todo |
| 🌊 Recife | Nordeste | Tropical litorâneo |
| 🏖️ Rio de Janeiro | Sudeste | Tropical litorâneo |
| 🌆 São Paulo | Sudeste | Subtropical, mais ameno |
| 🧉 Porto Alegre | Sul | Subtropical, o "friozinho" do grupo |

Os dados vêm da API pública do [Open-Meteo](https://open-meteo.com/), gratuita e sem
necessidade de cadastro ou chave de acesso. Ou seja: **tudo o que você fizer aqui, você
consegue repetir para a sua cidade** (ou para o destino das suas próximas férias 😉).

### O que você vai aprender

1. Fundamentos de Python - notebooks 01
2. Manipulação de Dados com pandas - notebooks 02 e 03
3. Análise Exploratória - notebooks 04 e 05
4. Modelagem de Dados - notebooks 06

## Tutoriais: instalando e configurando Python + VSCode

Se este é seu primeiro contato com o ambiente, siga esta ordem antes do Setup abaixo:

1. **Instalar o Python**
   - Windows/macOS/Linux: [python.org/downloads](https://www.python.org/downloads/) (marque
     "Add Python to PATH" no instalador do Windows).
   - macOS (alternativa via [Homebrew](https://brew.sh/)): `brew install python`.
   - Linux (Debian/Ubuntu): `sudo apt install python3 python3-venv python3-pip`.
   - Confirme a instalação: `python3 --version` (ou `python --version` no Windows).
2. **Criar um ambiente virtual** (isola as dependências deste projeto do resto do sistema):
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate       # Windows: .venv\Scripts\activate
   ```
   Guia oficial: [docs.python.org/3/library/venv](https://docs.python.org/3/library/venv.html).
3. **Instalar o VSCode**: [code.visualstudio.com](https://code.visualstudio.com/download).
4. **Instalar a extensão Python** (Microsoft) pelo Marketplace do VSCode — habilita
   IntelliSense, execução/debug de notebooks e scripts, e detecção automática do
   ambiente virtual criado no passo 2.
   - Extensão: [marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
   - Extensão Jupyter (para abrir os `.ipynb` de `notebooks/` direto no VSCode):
     [marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
5. **Selecionar o interpretador correto no VSCode**: `Ctrl+Shift+P` /
   `Cmd+Shift+P` → "Python: Select Interpreter" → escolha o `.venv` criado no passo 2.
6. **Tutoriais oficiais para se aprofundar**:
   - [Python for Beginners (Microsoft/VSCode)](https://code.visualstudio.com/docs/python/python-tutorial)
   - [Documentação oficial do Python (tutorial)](https://docs.python.org/3/tutorial/)
   - [Working with Jupyter Notebooks in VSCode](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
   - [Debugging Python in VSCode](https://code.visualstudio.com/docs/python/debugging)