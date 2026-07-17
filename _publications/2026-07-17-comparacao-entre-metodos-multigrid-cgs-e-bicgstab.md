---
title: "Comparação Entre Métdos Multigrid, CGS e BICGSTAB na solução da Equação de Poisson"
mathjax: true
collection: publications
category: manuscripts
permalink: /publicacoes/2026-07-17-comparacao-entre-metodos-multigrid-cgs-e-bicgstab
excerpt: 'Trabalho apresentado em formato de Banner no ERMAC 2026, que ocorreu em Florianópolis'
date: 2026-07-17
venue: 'Anais do III Encontro Regional de Matemática Aplicada e Computacional de Santa Catarina (ERMAC-SC 2026)'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.even3.com.br/anais/ermac-sc-2026-632874/1438079-comparacao-entre-metodos-multigrid-cgs-e-bicgstab-na-solucao-da-equacao-de-poisson/'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'QUADROS, J. P. T; CALEGARI, P. C. .(2026). &quot;Comparação Entre Métdos Multigrid, CGS e BICGSTAB na solução da Equação de Poisson".&quot; <i>Anais do III Encontro Regional de Matemática Aplicada e Computacional de Santa Catarina.</i>'
---
A equação de Poisson modela diversos problemas de equilíbrio, isto é, problemas em que as propriedades de interesse são invariantes no tempo. Dentre eles,  a distribuição de um Potencial Eletrostático $V$, em um domínio dielétrico \\(\Omega\\), de permissividade elétrica \\(\epsilon\\) em que há uma distribuição de cargas \\(\rho(x, y) \\).

$$- \dfrac{\partial^2 V}{\partial x^2} - \dfrac{\partial^2 V}{\partial y^2} =  \dfrac{\rho(x,y)}{\epsilon}.$$

O objetivo do presente trabalho é avaliar a eficiência de métodos iterativos para a solução do sistema linear oriundo da discretização da equação de Poisson com, \\(\rho(x,y) = 8 \pi ^2sen(2\pi x)sen(2\pi y)\\) e \\(\epsilon = 1.0\\), em um domínio \\(\Omega : [0, 1] \times [0, 1]\\) com condições de contorno Dirichlet.