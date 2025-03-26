# Desafio-Linux-DIO
Este projeto/Desafio da DIO tem como objetivo criar uma estrutura organizacional em um sistema Linux utilizando Bash Script para gerenciar usuários, grupos e diretórios.
# Provisionamento de Usuários e Diretórios no Linux  

## Descrição  
Este projeto automatiza a criação e configuração de usuários, grupos e diretórios em um ambiente Linux utilizando um script Bash. O objetivo é garantir a correta segmentação de permissões de acesso conforme as diretrizes organizacionais.  

## Estrutura do Projeto  
- **Diretórios:**  
  - `/publico` → Acesso livre para todos os usuários  
  - `/adm` → Exclusivo para o grupo `GRP_ADM`  
  - `/ven` → Exclusivo para o grupo `GRP_VEN`  
  - `/sec` → Exclusivo para o grupo `GRP_SEC`  

- **Grupos:**  
  - `GRP_ADM`  
  - `GRP_VEN`  
  - `GRP_SEC`  

- **Usuários:**  
  - **GRP_ADM:** carlos, maria, joao  
  - **GRP_VEN:** debora, sebastiana, roberto  
  - **GRP_SEC:** josefina, amanda, rogerio  

## Funcionalidades  
✔ Exclusão de diretórios, arquivos e usuários criados anteriormente  
✔ Criação de novos diretórios e grupos  
✔ Adição de usuários aos grupos correspondentes  
✔ Configuração de permissões:  
  - O diretório `/publico` permite acesso total a todos  
  - Cada grupo tem permissão total em seu respectivo diretório  
  - Usuários não podem acessar diretórios de outros grupos  

## Pré-requisitos  
- Sistema operacional baseado em Linux  ou máquina virtual(VirtualBox)
- Permissões de superusuário (root)  
- Git (opcional, para versionamento)  

