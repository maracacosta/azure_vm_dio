# 💻 Projeto DIO: Criação de Máquina Virtual no Azure

Este repositório documenta o desafio proposto no bootcamp **IA Generativa com Azure e XP Inc.**, com foco na **criação e configuração de uma Máquina Virtual Linux (Ubuntu) usando o Microsoft Azure**.

---

## 🧠 Objetivo do Desafio

- Praticar a criação de uma VM na nuvem com o Azure.
- Testar o acesso via SSH.
- Documentar o processo técnico usando GitHub.

---

## ⚙️ Etapas Realizadas

### 1. Criação da VM

- **Imagem escolhida**: Ubuntu Server 20.04 LTS – Gen2
- **Tamanho**: B1s (gratuito - 750h/mês)
- **Região**: East US - Zona 2
- **Grupo de Recursos**: `rg-vm-dio`
- **Nome da VM**: `vm-dio-linux`
- **Portas abertas**: 22 (SSH)

### 2. Conexão via SSH

```bash
ssh maracosta@52.186.170.8
