# 🐧 Linux & Cybersecurity: Meu Segundo Cérebro com IA

Projeto desenvolvido como parte de um desafio prático da **DIO**, utilizando o **Google NotebookLM** para construir uma base de conhecimento sobre Linux e fundamentos de cibersegurança.

## 🎯 Objetivo

Criar um assistente de estudos especializado em Linux e segurança da informação, capaz de explicar comandos, permissões, processos e conceitos básicos de cibersegurança com base em fontes técnicas confiáveis e citações verificáveis.

## 🧠 Ferramenta utilizada

**Google NotebookLM**, utilizado para organizar fontes de conhecimento, responder perguntas contextualizadas e gerar materiais de estudo.

**[Acessar o notebook](https://notebook.google.com/notebook/2401c751-8187-4567-b8fd-4e59d7e5beae)**

*Observação: o acesso depende das permissões de compartilhamento configuradas no NotebookLM.*

## 📚 Curadoria de fontes

O notebook reúne aproximadamente 30 fontes, incluindo documentação oficial, materiais educativos e videoaulas.

| Fonte | Finalidade |
|---|---|
| Ubuntu Documentation | Fundamentos do terminal e comandos Linux |
| LinuxCommand.org | Permissões, shell e administração básica |
| GNU Coreutils | Referência técnica dos comandos |
| Red Hat | Conceitos e administração Linux |
| NetworkChuck, Linux for Hackers | Processos, usuários, sudo e serviços |
| Curso em Vídeo | Introdução ao Linux em português |
| OWASP Top 10 | Conceitos de segurança em aplicações |
| PortSwigger Web Security Academy | Estudos de vulnerabilidades web |

As fontes foram escolhidas pela relevância técnica, caráter educativo e possibilidade de consultar o material original.

## ⚙️ Configuração do assistente

A seguinte instrução foi utilizada para personalizar o comportamento do notebook:

> Atue como um professor especializado em Linux e cibersegurança. Ensine em português brasileiro, com explicações para iniciantes, exemplos práticos e exercícios. Baseie suas respostas exclusivamente nas fontes fornecidas, apresentando citações verificáveis. Caso não encontre informações suficientes, informe isso claramente.

## 🧪 Testes realizados

### Teste 1: Permissões no Linux

**Pergunta:** Explique como funcionam as permissões de arquivos no Linux, incluindo chmod, usuários, grupos e permissões numéricas. Apresente exemplos práticos e cite as fontes utilizadas.

**Resultado:** O NotebookLM explicou o modelo de permissões `rwx`, os grupos de acesso `u/g/o` e a notação octal, incluindo exemplos com `chmod 755`, `644` e `600`.

**Fontes consultadas:** LinuxCommand.org e Curso em Vídeo.

### Teste 2: Gerenciamento de processos

**Pergunta:** Explique como funcionam os processos em primeiro plano e segundo plano no Linux. Demonstre os comandos sleep, jobs, ps, kill e os sinais SIGTERM e SIGKILL. Cite as fontes utilizadas e apresente exemplos práticos.

**Resultado:** O assistente explicou a execução em foreground/background, o uso de `&`, a identificação de processos e a diferença entre encerramento solicitado (`SIGTERM`) e forçado (`SIGKILL`).

**Fonte consultada:** NetworkChuck, Linux for Hackers, episódio 7.

### Teste 3: Riscos de segurança

**Pergunta:** Quais são os principais riscos de segurança causados por permissões mal configuradas, uso indevido do sudo e processos executados com privilégios elevados no Linux?

**Resultado:** Foram abordados os riscos de permissões excessivas, execução privilegiada, configurações de sudo e serviços expostos, acompanhados de comandos de inspeção e medidas preventivas.

**Fontes consultadas:** LinuxCommand.org, Ubuntu e videoaulas Linux for Hackers.

## 🗺️ Materiais gerados

- Mapa mental interativo sobre Linux.
- Apresentação **A Anatomia do Linux**.
- Relatório de referência sobre terminal, shell e comandos.
- Capturas de tela com respostas e trechos das fontes originais.

**[Visualizar mapa mental no NotebookLM](https://notebook.google.com/notebook/2401c751-8187-4567-b8fd-4e59d7e5beae/artifact/a1bcf57d-5476-4718-a620-4f181f7cab9f)**

## 💡 Aprendizados

O projeto demonstrou como uma ferramenta de IA baseada em fontes pode apoiar os estudos técnicos, permitindo:

- Centralizar materiais de diferentes formatos.
- Consultar conteúdos em português, mesmo quando a fonte original está em inglês.
- Conferir trechos originais por meio das citações.
- Gerar materiais complementares para revisão.
- Reconhecer a importância de verificar respostas produzidas por IA.

## ⚠️ Limitações

As respostas e os materiais gerados por IA podem conter imprecisões técnicas. Por isso, as informações devem ser verificadas nas fontes originais antes de serem aplicadas em ambientes reais.

## 📌 Contexto

Projeto educacional desenvolvido para fins de aprendizagem e documentação de conhecimentos sobre Linux, IA e cibersegurança.

Os materiais de terceiros permanecem sujeitos às respectivas licenças e direitos autorais.
