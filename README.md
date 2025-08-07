# 🧪 Gerador de Testes Unitários com LangChain + Azure OpenAI

Projeto prático para automatizar a criação de testes unitários utilizando LLMs (Modelos de Linguagem) com LangChain e Azure OpenAI.

## 📌 Descrição

Este projeto demonstra como utilizar a biblioteca [LangChain](https://www.langchain.com/) integrada com o modelo `gpt-35-turbo` da Azure OpenAI para gerar automaticamente testes unitários com base em funções Python fornecidas.

## 🎯 Objetivos

- Automatizar testes unitários em Python
- Integrar LLMs (Azure GPT) com LangChain
- Usar Colab como ambiente de desenvolvimento
- Compartilhar conhecimento no GitHub

## Resultados Obtidos

<img width="585" height="301" alt="image" src="https://github.com/user-attachments/assets/2cf69d43-d213-4b9f-99a9-591da7fd663b" />
<img width="604" height="273" alt="image" src="https://github.com/user-attachments/assets/3aaa2d58-6742-443e-857e-c9ff7c6fe8bc" />


## ⚙️ Tecnologias Utilizadas

- Python
- Google Colab
- Azure OpenAI (GPT-3.5 Turbo)
- LangChain
- `unittest` (módulo nativo do Python)

## 📈 Demonstração

### Função fornecida:
```python
def calcular_media(lista):
    if not lista:
        return 0
    return sum(lista) / len(lista)

