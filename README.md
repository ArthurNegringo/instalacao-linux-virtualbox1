# instalacao-linux-virtualbox1
Documentação técnica de instalação do Ubuntu 24.04 via VirtualBox.
# Relatório de Instalação: Deepin OS no VirtualBox 🐧

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![OS](https://img.shields.io/badge/OS-Deepin%2025-blue)
![VirtualBox](https://img.shields.io/badge/VirtualBox-7.0-blue)

Este repositório contém a documentação detalhada da instalação da distribuição Deepin OS em ambiente virtualizado para a atividade prática de administração de sistemas.

---

## 👥 Integrantes da Dupla
* **Piloto:** [Eduardo]
* **Copiloto:** [Arthur Brasil]

---

## 🚀 Manual de Instalação Passo a Passo

### 1. Configuração Inicial da VM
No VirtualBox, definimos o nome do projeto como `Deepin_OS_Projeto`, selecionamos o tipo "Linux" e a versão "Ubuntu (64-bit)" para compatibilidade com a ISO do Deepin.
<img width="875" height="662" alt="image" src="https://github.com/user-attachments/assets/1338d10b-4dab-48ed-8f7b-420d82663e20" />


### 2. Visão Geral do Hardware
Configuramos a máquina com **4096 MB (4GB) de RAM** e **4 núcleos de CPU** para garantir um bom desempenho da interface gráfica.
<img width="595" height="650" alt="image" src="https://github.com/user-attachments/assets/56ec0311-f998-428b-904c-572cdf997e86" />


### 3. Menu de Boot
Ao iniciar a VM, selecionamos a opção principal `Try Deepin 25 desktop` para carregar o ambiente de instalação.
<img width="711" height="598" alt="image" src="https://github.com/user-attachments/assets/9da5af14-97bc-4f9e-9ec5-0b53da041ea4" />


### 4. Seleção de Idioma
Dentro do instalador, definimos o idioma como **Português (Brasil)** para facilitar a configuração do sistema e do teclado.
<img width="961" height="566" alt="image" src="https://github.com/user-attachments/assets/f62a22e4-fc7c-4fc5-8b3c-896c6fbcb156" />


### 5. Progresso da Instalação
O sistema realiza a cópia dos arquivos e a configuração do ecossistema de aplicações.
<img width="953" height="574" alt="image" src="https://github.com/user-attachments/assets/278674bd-54ef-4057-9626-842e6e46d3eb" />

### 6. Tela de Login e Interface
Após o reinício, o usuário `eduardo478` foi criado com sucesso. Note o design moderno da tela de bloqueio do Deepin.
<img width="962" height="549" alt="image" src="https://github.com/user-attachments/assets/b4da3dab-c0eb-425f-bdd7-e88ee9489405" />


### 7. Área de Trabalho Finalizada
O sistema está totalmente operacional, com a barra de tarefas (dock) e o menu de aplicativos prontos para uso.
<img width="797" height="655" alt="image" src="https://github.com/user-attachments/assets/b57c3a77-b498-4ae7-a996-df1fa742c7ea" />

---

## 🛠️ Comandos de Pós-Instalação (Terminal)

Após a instalação, atualizamos os repositórios para garantir a segurança do sistema:

```bash
# Atualizar lista de repositórios
sudo apt update

# Aplicar atualizações de sistema
sudo apt upgrade -y
