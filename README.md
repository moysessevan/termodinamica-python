# Códigos: Termodinâmica Aplicada com Python e CoolProp

Bem-vindo ao repositório de códigos do livro *"Termodinâmica Aplicada com Python e CoolProp: Resolução de problemas e simulação de processos para Engenharia de Alimentos"*. 

Este repositório contém os Jupyter Notebooks (`.ipynb`) apresentados ao longo da obra, focados na transição das tabelas termodinâmicas tradicionais para o ambiente computacional, facilitando o cálculo de propriedades e a construção de diagramas.

---

## 📂 Estrutura do Repositório

### Capítulo 1 — O Ambiente de Trabalho e Conceitos Fundamentais
Este capítulo introduz o uso do Python e da biblioteca CoolProp para cálculos termodinâmicos iniciais e operações básicas.

- **`cod_1_1_variaveis_operacoes_si.ipynb`** 
  - *Descrição:* Declaração de variáveis, operações aritméticas básicas e formatação de saída no Sistema Internacional (SI).
- **`cod_1_2_funcao_loop_temperaturas.ipynb`** 
  - *Descrição:* Função personalizada e laço de repetição (`for`) para conversão de escalas de temperatura.
- **`cod_1_3_gas_ideal_isotermas.ipynb`**
  - *Descrição:* Cálculo vetorizado (NumPy), tabulação e plotagem do diagrama $P\text{-}\hat{V}$ de isotermas de gás ideal.
- **`cod_1_4_propriedades_agua_coolprop.ipynb`**
  - *Descrição:* Consulta de propriedades da água líquida e determinação da temperatura de ebulição a vácuo utilizando a função `PropsSI` do CoolProp.

### Capítulo 2 — Mudança de Fase e Diagramas Termodinâmicos
Este capítulo aborda o comportamento de fluidos puros sob mudança de fase, cálculo de título e a construção de diagramas termodinâmicos essenciais.

- **`cod_2_1_diagnostico_fase_saturacao.ipynb`**
  - *Descrição:* Diagnóstico automático de fase (`PhaseSI`) e determinação do calor latente de vaporização do fluido R134a.
- **`cod_2_2_calculo_titulo_mistura.ipynb`**
  - *Descrição:* Verificação da região bifásica e cálculo inverso do título de vapor ($x$).
- **`cod_2_3_diagrama_Tv_agua.ipynb`**
  - *Descrição:* Construção computacional do diagrama de fases $T\text{-}\hat{V}$ (domo de saturação) para a água.
- **`cod_2_4_diagrama_Ph_r134a.ipynb`**
  - *Descrição:* Construção computacional do diagrama frigorífico $P\text{-}\hat{H}$ para o fluido refrigerante R134a.

### Capítulo 3 — Energia e a Primeira Lei em Sistemas Fechados
Este capítulo explora os balanços de energia para sistemas sem fluxo de massa, incluindo cálculo de trabalho de fronteira, calorimetria e ciclos termodinâmicos fechados.

- **`cod_3_1_trabalho_politropico_pv.ipynb`**
  - *Descrição:* Cálculo de trabalho de fronteira em trajetórias politrópicas e diagrama $P\text{-}V$.
- **`cod_3_2_aquecimento_isobarico_agua.ipynb`**
  - *Descrição:* Balanço da Primeira Lei em aquecimento isobárico da água com mudança de fase.
- **`cod_3_3_resfriamento_isocorico_autoclave.ipynb`**
  - *Descrição:* Resfriamento isocórico de vapor de água em autoclave rígida.
- **`cod_3_4_calorimetria_equilibrio_fsolve.ipynb`**
  - *Descrição:* Calorimetria e cálculo de temperatura de equilíbrio térmico com a função `fsolve` do SciPy.
- **`cod_3_5_ciclo_fechado_pandas.ipynb`**
  - *Descrição:* Análise energética de ciclo fechado de gás ideal em três etapas utilizando tabulação com Pandas.
- **`cod_3_6_pasteurizador_batelada_agitacao.ipynb`**
  - *Descrição:* Balanço de energia em pasteurizador de leite em batelada considerando os efeitos de agitação mecânica.
- **`cod_3_7_expansao_livre_nitrogenio.ipynb`**
  - *Descrição:* Expansão livre de nitrogênio real no vácuo versus expansão contra a pressão atmosférica.

### Capítulo 4 — Análise de Energia em Volumes de Controle
Este capítulo aplica os balanços de massa e energia da Primeira Lei em regime permanente e transiente para equipamentos de fluxo contínuo e processos industriais.

- **`cod_4_1_bocal_convergente_vapor.ipynb`**
  - *Descrição:* Balanço de energia em regime permanente para determinação da velocidade de saída de vapor em um bocal convergente.
- **`cod_4_2_turbina_vapor_nao_adiabatica.ipynb`**[cite: 2]
  - *Descrição:* Análise energética e cálculo de potência gerada em uma turbina a vapor não adiabática com perdas térmicas.
- **`cod_4_3_bombeamento_lavagem_industrial.ipynb`**[cite: 2]
  - *Descrição:* Dimensionamento energético e cálculo de potência de bombeamento em sistema de lavagem industrial.
- **`cod_4_4_valvula_estrangulamento_r134a.ipynb`**[cite: 2]
  - *Descrição:* Expansão isoentálpica e determinação do título após passagem do fluido refrigerante R134a por uma válvula de estrangulamento.
- **`cod_4_5_dessuperaquecedor_mistura.ipynb`**[cite: 2]
  - *Descrição:* Balanço de massa e energia em câmara de mistura (dessuperaquecedor) por injeção direta de água líquida.
- **`cod_4_6_pasteurizador_placas_parametrico.ipynb`**[cite: 2]
  - *Descrição:* Modelagem e análise paramétrica da troca térmica em um pasteurizador a placas para processamento de alimentos.
- **`cod_4_7_transiente_enchimento_tanque_brentq.ipynb`**[cite: 2]
  - *Descrição:* Balanço de energia em regime transiente durante o enchimento de um tanque rígido utilizando o método numérico `brentq` do SciPy.

---

## 🚀 Como Utilizar

Todos os ficheiros deste repositório estão no formato Jupyter Notebook (`.ipynb`). 

A forma mais simples e recomendada de os executar é utilizando o **Google Colab**:
1. Abra o ficheiro desejado aqui no GitHub.
2. Se tiver a extensão do Colab ou se o botão estiver disponível, clique em **"Open in Colab"**.
3. Em alternativa, pode descarregar os ficheiros e abri-los localmente utilizando o Jupyter Notebook ou o VS Code, garantindo que instala as dependências necessárias executando: `pip install CoolProp numpy pandas matplotlib scipy`.
