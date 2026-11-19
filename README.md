# Termodinâmica Aplicada com Python e CoolProp

Bem-vindo ao repositório do livro *"Termodinâmica Aplicada com Python e CoolProp: Resolução de problemas e simulação de processos para Engenharia de Alimentos"*.
Este diretório contém os notebooks Jupyter (`.ipynb`) e os scripts em Python que acompanham a parte teórica introdutória do livro, demonstrando como sair das tabelas termodinâmicas impressas para o ambiente computacional.

## Capítulo 1: Fundamentos de Termodinâmica e Introdução Computacional

## 📚 Conteúdo do Capítulo

Os códigos aqui presentes estão organizados de acordo com as seções do livro. *(Nota: A seção 1.4 não possui material computacional associado neste repositório).*

- **1.1. Conceitos Básicos e Sistemas Termodinâmicos:** Scripts introdutórios definindo variáveis de sistema fechado e volume de controle.
- **1.2. Propriedades e Postulado de Estado:** Exemplos de conversão de unidades (temperatura, pressão) e cálculo de propriedades intensivas e extensivas.
- **1.3. Configuração do Ambiente Python (Google Colab):** Notebook base com as importações fundamentais (`numpy`, `matplotlib`) e testes de ambiente.
- **1.4. Primeiros Passos com CoolProp:** Introdução à biblioteca `CoolProp`. Como obter entalpia, entropia e volume específico de fluidos refrigerantes e água sem usar tabelas manuais.

## ⚙️ Pré-requisitos e Instalação

Recomendamos fortemente o uso do **Google Colab** para rodar os exemplos sem a necessidade de instalação local. No entanto, se preferir rodar em sua própria máquina (via Jupyter Notebook ou VS Code), você precisará instalar a biblioteca científica principal.

No terminal ou na primeira célula do seu notebook, execute:

```bash
pip install CoolProp numpy matplotlib
