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
citation: 'QUADROS, J. P. T; CALEGARI, P. C. Comparação Entre Métdos Multigrid, CGS e BICGSTAB na solução da Equação de Poisson. <i>Anais do III Encontro Regional de Matemática Aplicada e Computacional de Santa Catarina.</i> 2026.'
---
A equação de Poisson é uma Equação Diferencial Parcial Elíptica que aparece frequentemente em modelos matemáticos, como o problema da distribuição de um potencial eletrostático ou na solução da equação de Navier-Stokes em escoamentos incompressíveis.

$$- \dfrac{\partial^2 \phi}{\partial x^2} - \dfrac{\partial^2 \phi}{\partial y^2} =  f(x,y),$$

sendo \( \phi(x,y) \) uma propriedade a ser determinada e \( f(x,y) \) o termo fonte. A equação foi discretizada pelo método das diferenças finitas centrada nos nós, em um domínio \(\Omega = [0,1]^2 \). Comparou-se a eficiência entre os métodos Multigrid, CGS e BICGSTAB na solução do sistema linear oriunda da discretização da equação.