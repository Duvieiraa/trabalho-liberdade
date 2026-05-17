# Jogo de Adivinhação de Palavras

Projeto feito em Python com Streamlit. O jogo sorteia uma palavra relacionada a programação e o jogador deve descobrir a palavra tentando letras ou arriscando a palavra completa.

## Funcionalidades

* Sorteio de palavras relacionadas a programação.
* Palavra oculta com revelação das letras acertadas.
* Controle de vidas, tentativas e letras já utilizadas.
* Tentativa de adivinhar a palavra completa.
* Exibição do significado e de um exemplo de uso da palavra.
* Botão para iniciar uma nova rodada.

## Tecnologias

* Python
* Streamlit

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/Duvieiraa/trabalho-liberdade.git

```

2. Acesse a pasta do projeto:

```bash
cd trabalho-liberdade

```

3. Crie um ambiente virtual:

```bash
python -m venv .venv

```

4. Ative o ambiente virtual.

No Windows:

```bash
.venv\Scripts\activate

```

No Linux ou macOS:

```bash
source .venv/bin/activate

```

5. Instale as dependências:

```bash
pip install -r requirements.txt

```

6. Execute o aplicativo:

```bash
streamlit run app.py

```

7. Abra o endereço exibido no terminal. Normalmente será:

```text
http://localhost:8501

```

## Estrutura do Projeto

```text
.
├── app.py
├── requirements.txt
└── README.md

```

## Como Jogar

1. Observe a quantidade de letras da palavra oculta.
2. Digite uma letra e clique em `Verificar Letra`.
3. Se a letra existir na palavra, ela será revelada.
4. Se errar, uma vida será removida.
5. Depois da primeira tentativa, também é possível tentar adivinhar a palavra completa.
6. Ao acertar, o jogo mostra o significado e um exemplo da palavra.

## Observação

O projeto foi desenvolvido para fins de estudo, praticando conceitos de Python, controle de estado com `st.session_state` e construção de interfaces simples com Streamlit.
