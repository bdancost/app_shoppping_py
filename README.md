

# Gerenciador de Lista de Compras

Um script Python simples para gerenciar listas de compras, permitindo adicionar, remover e visualizar itens, além de salvar e carregar listas de compras de um arquivo JSON.

## Índice

- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Funcionalidades](#funcionalidades)
- [Contribuindo](#contribuindo)

## Pré-requisitos

- Python 3.x
- Biblioteca `json` (inclusa na instalação padrão do Python)
- Acesso ao terminal (Windows, Mac ou Linux)

## Instalação

Clone o repositório para sua máquina local:

```bash
git clone https://github.com/bdancost/app_shoppping_py.git
cd app_shopping_py
```

## Como Usar

1. Execute o script `main.py` no terminal:

```bash
python main.py
```

2. Escolha uma das opções do menu:

   - `1` Criar uma nova lista de compras.
   - `2` Carregar uma lista existente.
   - `3` Sair.

3. Após criar ou carregar uma lista, use as seguintes opções:

   - `1` Adicionar um item à lista.
   - `2` Remover um item da lista.
   - `3` Visualizar a lista de compras.
   - `4` Salvar a lista e sair.
   - `5` Sair sem salvar.

## Funcionalidades

- **Adicionar item**: Adicione um item à lista de compras, especificando o nome e a quantidade.
- **Remover item**: Remova um item da lista.
- **Visualizar lista**: Exibe todos os itens e suas quantidades.
- **Salvar lista**: Salva a lista de compras em um arquivo JSON para carregá-la posteriormente.
- **Carregar lista**: Carrega uma lista de compras existente de um arquivo JSON.

## Exemplo de Uso

```python
# Adiciona um item à lista
adicionar_item(compras, "Maçã", 3)

# Remove um item da lista
remover_item(compras, "Maçã")

# Salva a lista em um arquivo JSON
salvar_compras(compras, "lista.json")

# Carrega uma lista de um arquivo JSON
compras = carregar_compras("lista.json")
```

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_ com melhorias e correções.

