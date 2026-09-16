# Arquitetura de Software, Uninove 2026.2

Acervo didático da disciplina Arquitetura de Software, curso de graduação da
Universidade Nove de Julho (Uninove), semestre 2026.2.

**Professor:** José Romualdo

## O case

As 20 aulas do semestre são construídas em torno de um único case, a
transportadora fictícia Rota Sul, que evolui de um monólito em três camadas
até uma aplicação distribuída publicada em nuvem.

## Portal publicado

O portal com os decks e os kits de laboratório fica publicado em:

<https://josercf.github.io/uninove-2026-2-arquitetura-software/>

## Preview local

Este repositório é um site estático, sem build e sem bundler. Para
visualizar localmente, a partir da raiz do repositório:

```bash
python3 -m http.server 8000
```

E acessar `http://localhost:8000/` no navegador.

## Estrutura

O andamento do trabalho, a ordem de leitura recomendada e o que falta
construir estão em `docs/ANDAMENTO.md`.

git --version
git config --global user.name "Pedro Henrique dos Santos de Carvalho"
git config --global user.email "Pedrocarvalho.santos@uni9.edu.br"
git clone https://github.com/SEU-USUARIO/uninove-2026-2-rota-sul.git
cd uninove-2026-2-rota-sul
git remote -v

./mvnw spring-boot:run
