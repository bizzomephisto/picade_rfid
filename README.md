# picade_rfid
# place holder for j.bradford picade_rfid interface
sudo apt-get update
sudo apt-get upgrade

start->preferences-> rasppi configuration->interfaces

enable SPI

(terminal) lsmod | grep spi

reboot
(in terminal sudo reboot)

(terminal)
sudo apt-get install python3-dev python3-pip

sudo pip3 install spidev

sudo pip3 install mfrc522


git clone https://github.com/bizzomephisto/picade_rfid.git

cd picade_rfid.git

python3 Read.py

python3 Write.py
