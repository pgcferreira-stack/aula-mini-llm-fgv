# Mini-LLM: do zero ao ajuste fino

Material hands-on de 90 minutos do MBA FGV em IA Generativa para Negócios.

**O caso:** treinar um LLM pequeno do zero para entender como ele aprende e, depois, ensinar as regras do Banco Aurora, uma empresa fictícia, a um modelo pré-treinado.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pgcferreira-stack/aula-mini-llm-fgv/blob/main/mini_llm.ipynb)

## Como rodar

1. Clique no botão **Open in Colab** acima e entre com sua conta Google.
2. **Arquivo → Salvar uma cópia no Drive**.
3. **Ambiente de execução → Alterar o tipo de ambiente de execução → GPU T4 → Salvar**.
4. Rode as células de cima para baixo com **Shift + Enter**. A primeira instala as bibliotecas e baixa este repositório.

## O que tem no notebook

| Parte | Conteúdo |
|---|---|
| 1. Um LLM do zero | Tokens, treino, troca de base, tamanho do modelo, poucos dados, temperatura e mapa de atenção |
| 2. Ajuste fino | Modelo pronto com e sem LoRA, comparado a um mini-GPT treinado só com o FAQ |

## Estrutura

- `mini_llm.ipynb`: o notebook
- `dados/machado.txt`: *Memórias Póstumas de Brás Cubas*, de Machado de Assis
- `dados/atendimento.txt`: 9.000 conversas de atendimento sintéticas
- `dados/faq_banco_aurora.jsonl`: 150 pares de pergunta e resposta do Banco Aurora

## Fontes e licenças

- Machado de Assis: domínio público, via [Project Gutenberg, ebook 54829](https://www.gutenberg.org/ebooks/54829).
- Modelo: [Qwen2.5-0.5B-Instruct](https://huggingface.co/Qwen/Qwen2.5-0.5B-Instruct) (Apache 2.0).
- O Banco Aurora, suas regras e as conversas são fictícios.

Nenhuma conta no Hugging Face nem chave de API é necessária.
