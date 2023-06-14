# psiphon-vps-server
stabilizing vps psiphon server pro termux 
$$$$$$$$$$$$$$$


apt-get update

apt-get upgrade

apt-get install screen



wget https://raw.githubusercontent.com/Psiphon-Labs/psiphon-tunnel-core-binaries/master/psiphond/psiphond


chmod +× psiphond 



./psiphond --ipaddress 0.0.0.0 --web 3000 --protocol SSH:3001 --protocol OSSH:3002 --protocol FRONTED-MEEK-OSSH:443 generate


screen -dmS psiphon ./psiphond run

cat server-entry.dat






Android Ghosts 👻 
أشباح أندرويد
