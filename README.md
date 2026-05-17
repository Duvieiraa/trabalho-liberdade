# Jogo de Adivinhacao de Palavras

Projeto feito em Python com Streamlit. O jogo sorteia uma palavra relacionada a programacao e o jogador deve descobrir a palavra tentando letras ou arriscando a palavra completa.

## Funcionalidades

- Sorteio de palavras relacionadas a programacao.
- Palavra oculta com revelacao das letras acertadas.
- Controle de vidas, tentativas e letras ja utilizadas.
- Tentativa de adivinhar a palavra completa.
- Exibicao do significado e de um exemplo de uso da palavra.
- Botao para iniciar uma nova rodada.

## Tecnologias

- Python
- Streamlit

## Como Executar

1. Clone este repositorio:

```bash
git clone <url-do-repositorio>
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

5. Instale as dependencias:

```bash
pip install -r requirements.txt
```

6. Execute o aplicativo:

```bash
streamlit run app.py
```

7. Abra o endereco exibido no terminal. Normalmente sera:

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
3. Se a letra existir na palavra, ela sera revelada.
4. Se errar, uma vida sera removida.
5. Depois da primeira tentativa, tambem e possivel tentar adivinhar a palavra completa.
6. Ao acertar, o jogo mostra o significado e um exemplo da palavra.

## Observacao

O projeto foi desenvolvido para fins de estudo, praticando conceitos de Python, controle de estado com `st.session_state` e construcao de interfaces simples com Streamlit.
