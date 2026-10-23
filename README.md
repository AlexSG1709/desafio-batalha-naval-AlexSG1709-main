# ⚓ Desafio Batalha Naval em C

![Linguagem C](https://shields.io)
![Ambiente](https://shields.io)
![Status](https://shields.io)

## 📝 Descrição do Projeto
Este projeto consiste no desenvolvimento de um simulador do clássico jogo **Batalha Naval**, construído inteiramente na **Linguagem C** para execução em terminal de comando. O desafio foi estruturado em três níveis de complexidade incremental (Novato, Aventureiro e Mestre), com o objetivo de consolidar conceitos avançados de estruturas de dados estáticas e algoritmos de mapeamento espacial.

---

## 🎮 Níveis de Desenvolvimento e Funcionalidades

### 🥉 1. Nível Novato (Fundamentos)
* **Mapeamento Bidimensional:** Implementação da lógica inicial de posicionamento de navios utilizando vetores bidimensionais.
* **Coordenadas Básicas:** Alocação manual de dois navios (um posicionado verticalmente e outro horizontalmente) com exibição das coordenadas de cada parte através da função `printf`.

### 🥈 2. Nível Aventureiro (Expansão Espacial)
* **Matriz Ampliada:** Expansão do tabuleiro para uma área de jogo com dimensões estáveis de **10x10**.
* **Posicionamento Diagonal:** Adição de regras para inserção e validação de quatro navios simultâneos, incluindo posicionamentos diagonais.
* **Renderização de Estados:** Exibição completa da matriz no console, utilizando `0` para indicar posições de água livre e `3` para identificar células ocupadas por embarcações.

### 🥇 3. Nível Mestre (Mecânicas Avançadas)
* **Matrizes de Habilidades:** Criação de três matrizes específicas independentes para sobrepor efeitos especiais de ataque ao tabuleiro.
* **Padrões Geométricos Complexos:** Algoritmos para desenhar e calcular áreas de efeito nos formatos de **Cone**, **Cruz** e **Octaedro**.
* **Estruturas de Repetição Aninhadas:** Uso de loops (`for` / `while`) aninhados para percorrer, preencher e validar dinamicamente o impacto das habilidades na área afetada (exibindo `0` para áreas salvas e `1` para posições atingidas).

---

## 🛠️ Requisitos Técnicos Consolidados

### Requisitos Funcionais
* **Estruturação por Matrizes:** Gerenciamento eficiente e manipulação direta de índices da matriz.
* **Entrada de Dados:** Configuração dos valores inseridos manualmente via variáveis controladas no escopo do código.
* **Exibição Formatada:** Saída de resultados organizada, garantindo legibilidade espacial do tabuleiro no console.

### Requisitos Não-Funcionais
* **Desempenho:** Execução imediata das varreduras e operações sem atrasos perceptíveis de processamento.
* **Manutenibilidade:** Código limpo, modularizado e devidamente comentado para facilitar futuras expansões de regras.

---

## 🚀 Como Executar o Projeto

Certifique-se de ter um compilador C instalado (como o `gcc`) em seu ambiente local.

1. Clone o repositório em sua máquina:
```bash
git clone https://github.com
```

2. Acesse o diretório do projeto:
```bash
cd desafio-batalha-naval-AlexSG1709-main
```

3. Compile o arquivo fonte:
```bash
gcc batalhaNaval.c -o batalhaNaval
```

4. Execute o simulador:
```bash
./batalhaNaval
```

---
*Projeto desenvolvido como atividade acadêmica para a plataforma MateCheck.*
