MAPA – Pesquisa Operacional: Modelagem do Problema de Transporte

Autor: Michael Ewerton Oliveira Disciplina: Pesquisa Operacional Instituição: UniCesumar

Descrição do Projeto

Esta atividade propôs a modelagem de um problema clássico de programação linear, conhecido como problema de transporte, visando minimizar o custo logístico entre fábricas de monitores (X, Y, Z) e centros de distribuição (A, B, C, D, E). O desafio foi transformar dados reais de produção, demanda e custos em uma estrutura matemática formalizada.

Componentes da Formulação

Variáveis de decisão: $$x_{ij}$$ → quantidade de unidades transportadas da fábrica i para o centro j (i = X, Y, Z | j = A, B, C, D, E)

Função objetivo: Minimizar o custo total de transporte $$Z = \sum_{i}\sum_{j} c_{ij} \cdot x_{ij}$$ onde $$c_{ij}$$ representa o custo unitário de transporte entre fábrica i e centro j

Restrições de produção: A quantidade total enviada por cada fábrica não pode ultrapassar sua capacidade: $$\sum_{j} x_{Xj} \leq \text{produção de X}$$ $$\sum_{j} x_{Yj} \leq \text{produção de Y}$$ $$\sum_{j} x_{Zj} \leq \text{produção de Z}$$

Restrições de capacidade de distribuição: Cada centro de distribuição recebe no máximo sua demanda: $$\sum_{i} x_{iA} \leq \text{demanda de A}$$ $$\sum_{i} x_{iB} \leq \text{demanda de B}$$ $$\sum_{i} x_{iC} \leq \text{demanda de C}$$ $$\sum_{i} x_{iD} \leq \text{demanda de D}$$ $$\sum_{i} x_{iE} \leq \text{demanda de E}$$

Restrições de não negatividade: $$x_{ij} \geq 0$$ para todos os pares i, j

Importância da Atividade

A modelagem deste problema simula cenários reais de logística e gestão de cadeias produtivas, aplicando matemática e inteligência operacional na tomada de decisões estratégicas.

Resultado da Avaliação

Nota máxima com elogio pela estrutura e entendimento do tema: “Parabéns! Você conseguiu realizar o que era esperado em sua resposta.”
