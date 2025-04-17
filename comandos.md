# 📟 Comandos utilizados

    ✅ ip a: Foi usado para coletar o IP da VM

    ip ➡️ Comando para configurações de rede
    a  ➡️ Abreviação de "Address"

---

    ✅ sudo apt update: Checa se há algo novo disponível para instalar ou atualizar

    sudo    ➡️  Permite executar comandos como administrador
    apt     ➡️  Ferramenta do Ubuntu para gerenciar pacotes
    update  ➡️  Comando para atualizar de pacotes disponíveis

---

    ✅ sudo apt install nginx -y: Instala o NGINX sem pedir confirmação durante a instalação

    sudo     ➡️ Permite executar comandos como administrador
    apt      ➡️ Ferramenta do Ubuntu para gerenciar pacotes
    install  ➡️ Comando para instalar pacotes
    -y       ➡️ Aceita automaticamente qualquer confirmação que o sistema pedir

---

    ✅ systemctl status nginx: permite saber o status do NGINX

    systemctl  ➡️ Ferramenta para controle de sistema e serviços no Linux
    status     ➡️ Informações do serviço naquele momento
    nginx      ➡️ Serviço

---

    ✅ sudo apt install openssh-server -y: Instala a porta SSH sem pedir
    ✅ confirmação durante a instalação

    sudo             ➡️ Permite executar comandos como administrador
    apt              ➡️ Ferramenta do Ubuntu para gerenciar pacotes
    install          ➡️ Comando para instalar pacotes
    openssh-server   ➡️ Pacote que permite que sua VM funcione como um servidor SSH
    -y               ➡️ Aceita automaticamente qualquer confirmação que o sistema pedir

---

    ✅ sudo systemctl start ssh: Inicia o o serviço SSH
    ✅ sudo systemctl enable ssh: Habilita o serviço para iniciar automaticamente junto com o sistema

    sudo       ➡️ Permite executar comandos como administrador
    systemctl  ➡️ Ferramenta para controle de sistema e serviços no Linux
    start      ➡️ Comando para iniciar um serviço
    Enable     ➡️ Comando para Habilitar um serviço para iniciar automaticamente junto com o sistema
    ssh        ➡️ Serviço

---

    ✅ ssh usuario@ip-da-vm: Conectar remotamente à uma máquina via SSH

    ssh              ➡️ Serviço
    usuario@ip-da-vm ➡️ Endereço
    exit             ➡️ Comando para sair da conexão SSH

---

    ✅ cd diretorio-da-aplicação-local: Localiza um diretório desejado
    ✅ scp -r * usuario@ip-da-vm:/tmp: Copia arquivos de uma máquina para uma remota

    cd    ➡️ Comando para mudar diretório
    scp   ➡️ Copia arquivos usando protocolo SSH
    -r    ➡️ Copia o diretório e todas as subppastas
    *     ➡️ Aqui, redudante, serve para especificar TUDO. Neste contexto, copiar TUDO no diretório
    :/tmp ➡️ Diretório da máquina remota

---

    ✅ sudo mv /tmp/* /var/www/html/: Substitui os arquivos do diretório /var/www/html/: pelo diretório /tmp

    sudo           ➡️ Permite executar comandos como administrador
    mv             ➡️ Comando para Mover
    /tmp/          ➡️ Diretório
    *              ➡️ Seleciona tudo no diretório
    /var/www/html/ ➡️ Diretório destino
