sudo apt update
mkdir ganesh
cd ganesh
git clone
ls
cd
sudo apt install docker.io 
sudo docker build -t gannu .
sudo docker run -d -p 8000:8000 gannu


ip:8000
