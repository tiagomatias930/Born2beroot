# Born2beroot

---

# Born2beroot

## Descrição

Born2beroot é um projeto da 42 que tem como objetivo configurar uma máquina virtual com um sistema operacional baseado em Linux (Debian) ou BSD (FreeBSD). O foco do projeto é aprender sobre administração de sistemas, segurança, e a implementação de boas práticas de configuração e gerenciamento de sistemas.

## Estrutura do Projeto

O projeto envolve a configuração de uma máquina virtual seguindo as diretrizes fornecidas pelo projeto. Você pode usar software de virtualização como VirtualBox ou VMware.

## Requisitos

- Configurar uma máquina virtual com um sistema operacional Debian ou FreeBSD.
- Configurar um firewall usando `ufw` (para Debian) ou `pf` (para FreeBSD).
- Implementar particionamento de disco conforme especificado.
- Configurar um servidor SSH seguro.
- Configurar um servidor Web (nginx).
- Configurar usuários e grupos com permissões específicas.
- Implementar backups automáticos.
- Configurar e usar um software de monitoramento (como `cron` para tarefas agendadas e `logrotate` para gerenciamento de logs).

## Funcionalidades

### Configuração do Sistema Operacional

1. **Instalação do SO:**
   - Baixar a ISO do Debian ou FreeBSD.
   - Instalar o SO na máquina virtual.

2. **Particionamento de Disco:**
   - Configurar o particionamento do disco de acordo com as instruções do projeto.

3. **Configuração de Rede:**
   - Configurar a rede para permitir acesso SSH e outras funcionalidades necessárias.

### Segurança

1. **Firewall:**
   - Debian: Configurar `ufw` para permitir apenas tráfego necessário.
   - FreeBSD: Configurar `pf` para permitir apenas tráfego necessário.

2. **SSH:**
   - Configurar o servidor SSH para usar autenticação por chave pública.
   - Desabilitar login de root via SSH.
   - Alterar a porta padrão do SSH para aumentar a segurança.

### Usuários e Grupos

1. **Configuração de Usuários:**
   - Criar usuários com permissões específicas.
   - Configurar grupos para gerenciar permissões de forma eficiente.

2. **Sudo:**
   - Configurar `sudo` para permitir que certos usuários executem comandos com privilégios elevados.

### Servidor Web

1. **Nginx:**
   - Instalar e configurar o servidor web nginx.
   - Configurar o firewall para permitir tráfego HTTP e HTTPS.

### Backups

1. **Automação:**
   - Configurar tarefas de backup usando `cron`.
   - Implementar rotinas de backup de arquivos importantes.

### Monitoramento

1. **Logs:**
   - Configurar `logrotate` para gerenciar logs.
   - Monitorar o sistema para garantir que ele está funcionando corretamente.

## Como Configurar

### Passo a Passo

1. **Baixar e instalar a máquina virtual:**
   - Use VirtualBox ou VMware para criar uma nova máquina virtual.
   - Instale Debian ou FreeBSD a partir da ISO baixada.

2. **Configurar o sistema operacional:**
   - Siga as instruções do projeto para configurar o particionamento de disco, firewall, SSH, e outras funcionalidades.

3. **Verificação:**
   - Use comandos como `ufw status`, `systemctl status ssh`, e `nginx -t` para verificar se os serviços estão configurados corretamente.
## Para ter informacoes mais detalhadas viste:
  
    https://github.com/pasqualerossi/Born2BeRoot-Guide
