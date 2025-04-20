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

A conexão foi feita com sucesso usando o terminal.

Foi necessário confirmar a autenticidade da máquina na primeira conexão com yes.

3. Comandos Testados na VM
bash
Copiar
Editar
lsb_release -a     # Verificar versão do Ubuntu
df -h              # Verificar espaço em disco
uptime             # Verificar tempo de atividade da máquina


✅ Conclusão
A máquina virtual foi criada e conectada com sucesso. O desafio proporcionou uma experiência prática de uso da nuvem e reforçou conhecimentos de CLI, Linux e boas práticas de documentação técnica.

Projeto realizado por Mara Costa 💙 | Bootcamp DIO + XP Inc.
