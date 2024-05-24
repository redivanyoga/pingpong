SPESIFIKASI MINIMUM 

VPS UBUNTU 20 / 22
2CPU ROM 1G
SSD 50 - 100

### INSTALATION :
#### jANGAN LUPA INSTALL GIT DULU 
    apt-get update -y && apt-get install git -y
### Steps
#### TIRU REPOSITORY INI :
    git clone https://github.com//pingpong.git
#### SET UP MESIN : 
    cd pingpong && chmod ug+x *.sh && ./setup.sh
####  JALANKAN DENGAN SCRIPT INI :
    ./start_pingpong.sh && ./check_log.sh
### BEBERAPA COMMAND YANG BISA DIGUNAKAN :
    ./start_pingpong.sh
    ./stop_pingpong.sh
    ./check_log.sh
###  MATIKAN NODE :
     cd 
     rm -rf pingpong
     
