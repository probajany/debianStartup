# debianStartup
debian steps

Get root or else... :)

Login as root or su to get root prompt

type visudo

an editor will open find a line says

root ALL=(ALL) ALL

add one with your username below that

user ALL=(ALL) ALL

Type ctrl+x Type Y to the prompt

get nodejs:

wget https://nodejs.org/dist/v4.2.1/node-v4.2.1-linux-x86.tar.gz

sudo tar -C /usr/local --strip-components 1 -xzf node-v4.2.1-linux-x86.tar.gz 

fix npm permissions

sudo npm get prefix
whoami
sudo chown -R 'whoami' /usr/local/
