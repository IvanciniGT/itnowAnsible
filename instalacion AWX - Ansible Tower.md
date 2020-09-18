ATower.AWX
-----------
Dependencias:
    docker
    docker-compose
    python3
    python3-pip
        docker
        docker-compose
        requests
    javascript
        -nodejs
        -npm
    -pwgen

Instalacion Dependencias:
    sudo apt install <paquete>
    sudo pip3 install requests
    sudo npm install npm -- global

Descargar AWX:
git clone --depth 50 https://github.com/ansible/awx.git

pwgen -N 1 -s 30 

Modificar el fichero de Inventario
    Puerto
    usuario/contraseña
    clave cifrar contraseñas