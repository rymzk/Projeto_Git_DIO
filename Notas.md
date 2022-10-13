##Git SSH
ssh-keygen -t ed25519 -C andre.yamazaki@gmail.com
cd /.ssh
cat id_ed25519.pub
Add GitHub

##Inicializar
git config --global user.email "email"
git config --global user.name "name"

git init

##Editar
git add <arquivo> ou git add *
git commit -m "Mensagem"
