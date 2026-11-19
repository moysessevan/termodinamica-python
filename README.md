# Códigos: Termodinâmica Aplicada com Python e CoolProp

Bem-vindo ao repositório de códigos do livro *"Termodinâmica Aplicada com Python e CoolProp: Resolução de problemas e simulação de processos para Engenharia de Alimentos"*. 

Este repositório contém os Jupyter Notebooks (`.ipynb`) apresentados ao longo da obra, focados na transição das tabelas termodinâmicas tradicionais para o ambiente computacional, facilitando o cálculo de propriedades e a construção de diagramas.

---

## 📂 Estrutura do Repositório

### Capítulo 1 — O Ambiente de Trabalho e Conceitos Fundamentais
Este capítulo introduz o uso do Python e da biblioteca CoolProp para cálculos termodinâmicos iniciais e operações básicas.

* **`cod_1_1_variaveis_operacoes_si.ipynb`** 
  * *Descrição:* Declaração de variáveis, operações aritméticas básicas e formatação de saída no Sistema Internacional (SI).
* **`cod_1_2_funcao_loop_temperaturas.ipynb`** 
  * *Descrição:* Função personalizada e laço de repetição (`for`) para conversão de escalas de temperatura.
* **`cod_1_3_gas_ideal_isotermas.ipynb`**
  * *Descrição:* Cálculo vetorizado (NumPy), tabulação e plotagem do diagrama $P\text{-}\hat{V}$ de isotermas de gás ideal.
* **`cod_1_4_propriedades_agua_coolprop.ipynb`**
  * *Descrição:* Consulta de propriedades da água líquida e determinação da temperatura de ebulição a vácuo utilizando a função `PropsSI` do CoolProp.

### Capítulo 2 — Mudança de Fase e Diagramas Termodinâmicos
Este capítulo aborda o comportamento de fluidos puros sob mudança de fase, cálculo de título e a construção de diagramas termodinâmicos essenciais.

* **`cod_2_1_diagnostico_fase_saturacao.ipynb`**
  * *Descrição:* Diagnóstico automático de fase (`PhaseSI`) e determinação do calor latente de vaporização do fluido R134a.
* **`cod_2_2_calculo_titulo_mistura.ipynb`**
  * *Descrição:* Verificação da região bifásica e cálculo inverso do título de vapor ($x$).
* **`cod_2_3_diagrama_Tv_agua.ipynb`**
  * *Descrição:* Construção computacional do diagrama de fases $T\text{-}\hat{V}$ (domo de saturação) para a água.
* **`cod_2_4_diagrama_Ph_r134a.ipynb`**
  * *Descrição:* Construção computacional do diagrama frigorífico $P\text{-}\hat{H}$ para o fluido refrigerante R134a.

---

## 🚀 Como Utilizar

Todos os ficheiros deste repositório estão no formato Jupyter Notebook (`.ipynb`). 

A forma mais simples e recomendada de os executar é utilizando o **Google Colab**:
1. Abra o ficheiro desejado aqui no GitHub.
2. Se tiver a extensão do Colab ou se o botão estiver disponível, clique em **"Open in Colab"**.
3. Em alternativa, pode descarregar os ficheiros e abri-los localmente utilizando o Jupyter Notebook ou o VS Code, garantindo que instala as dependências necessárias executando: `pip install CoolProp numpy pandas matplotlib`.
