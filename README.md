# Laboratórios GitHub Actions

Gerência de Configuração - Eng. de Software. Um diretório por exercício; os workflows ficam em `.github/workflows/` (o GitHub só lê workflows da raiz), com prefixo do laboratório.

| Pasta | Exercício | Workflow |
|---|---|---|
| `lab01/` | Lab 01 - Ex. 01, 02 e 03 (manual, agendado, push) | `lab01-helloFlow.yml` (Ex. 03, push); `lab01-helloFlow-schedule.yml` (Ex. 02, schedule) |
| `lab02-ex01/` | Lab 02 - Ex. 01 (checkout + node) | `lab02-ex01-build.yml` |
| `lab02-ex02/` | Lab 02 - Ex. 02 (Build V1 e Build V2) | `lab02-ex02-build01.yml`, `lab02-ex02-build02.yml` |
| `lab03-jest/` | Lab 03 - Ex. 01 (Jest + cobertura, matriz Node) | `lab03-jest-teste.yml` |
| `lab03-docker/` | Lab 03 - Ex. 02 (build e push no Docker Hub) | `lab03-docker-build.yml` |
| `lab04/` | Lab 04 (lint com condicional + Docker Hub) | `lab04-gcp-deploy.yml` |
