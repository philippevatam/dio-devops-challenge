# Desafio DevOps DIO

![CI Pipeline](https://github.com/philippevatam/dio-devops-challenge/actions/workflows/ci.yml/badge.svg)

Este projeto implementa o desafio "Criando seu Primeiro Projeto de DevOps com GitLab" da DIO, adaptado para GitHub. Ele demonstra práticas fundamentais de DevOps, incluindo a configuração de pipelines de CI/CD com GitHub Actions, automação e organização de repositórios.

## Referências
- Repositório original: [aula-devops-fundamentals](https://gitlab.com/sandro.lechner/aula-devops-fundamentals)
- Slides: [Estudo de caso](https://hermes.dio.me/files/assets/588d3e66-5ecd-4b01-9f0a-be3d7aa81a3c.zip)

## Tecnologias Utilizadas
- **GitHub Actions**: Pipeline de CI/CD para automação de builds e testes.
- **Python**: Para scripts e testes automatizados.
- **Bash**: Para automação de processos (ex.: scripts de deploy).
- **Docker** (opcional): Para conteinerização.

## Estrutura do Projeto
- `.github/workflows/ci.yml`: Pipeline de CI/CD com GitHub Actions.
- `requirements.txt`: Dependências do projeto (ex.: pytest).
- `tests/test_app.py`: Testes automatizados com pytest.
- `docs/estudo-de-caso.zip`: Slides do desafio.
- `scripts/`: Scripts de automação (ex.: deploy.sh).
- `configs/`: Configurações, como Dockerfile (opcional).

## Como Executar
1. Clone o repositório:
   ```bash
   git clone git@github.com:philippevatam/dio-devops-challenge.git
