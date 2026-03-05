---
title: "Métodos Iterativos para a Solução da Equação de Poisson"
collection: publications
category: manuscripts
permalink: /publicacoes/2026-02-13-metodos-iterativos-para-sol-da-eq-de-poisson
excerpt: 'Trabalho apresentado em formato de Banner no CNMAC 2025, que ocorreu na cidade do Rio de Janeiro'
date: 2026-02-13
venue: 'Proceeding Series of the Brazilian Society of Computational and Applied Mathematics'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://proceedings.sbmac.org.br/sbmac/article/view/5197'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'QUADROS, J. P. T; CALEGARI, P. C. .(2026). &quot;Métodos Iterativos para a Solução da Equação de Poisson".&quot; <i>Proceeding Series of the Brazilian Society of Computational and Applied Mathematics</i>. v. 12. n. 1.'
---
A equação de Poisson modela diversos problemas de equilíbrio, isto é, problemas em que as propriedades de interesse são invariantes no tempo. Dentre eles,  a distribuição de um Potencial Eletrostático $V$, em um domínio dielétrico $\Omega$, de permissividade elétrica $\epsilon$ em que há uma distribuição de cargas $\rho(x, y)$.

$$- \dfrac{\partial^2 V}{\partial x^2} - \dfrac{\partial^2 V}{\partial y^2} =  \dfrac{\rho(x,y)}{\epsilon}.$$

O objetivo do presente trabalho é avaliar a eficiência de métodos iterativos para a solução do sistema linear oriundo da discretização da equação de Poisson \eqref{POT_ELETRICO} com, $\rho(x,y) = 8 \pi ^2sen(2\pi x)sen(2\pi y)$ e $\epsilon = 1.0$, em um domínio $\Omega : [0, 1] \times [0, 1]$ com condições de contorno Dirichlet.