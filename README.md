# Unifi_Controller


## Preping Server
```
echo "Installing Docker"
apt-get -y install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
apt-get update
apt-get -y install git docker-ce docker-compose
```

## Preping Folders
```
echo "Creating nescessary folders"
mkdir /docker
mkdir /docker/Unifi_Controller
```


##GIT
```
git config --global user.name "uName"
git config --global user.email "eMail"

git remote add origin https://github.com/dVerschaeve/Unifi_Controller.git

git add modified file
git commit -m "meaningfull text"
git push -u origin master 
```

##Unifi Network
Patch Panel A
|A1|A2|A3|A4|A5|A6|A7|A8|A9|A10|A11|A12|
|---|---|---|---|---|---|---|---|---|---|---|---|
|C1|C2|Living Room 1|Living Room 2|Living Room 3|Living Room 4|Kitchen1|Kitchen2|Master Bedroom 1|Master Bedroom 2|Bedroom 1|Bedroom 2|

Patch Panel B
|B1|B2|B3|B4|B5|B6|B7|B8|B9|B10|B11|B12|
|---|---|---|---|---|---|---|---|---|---|---|---|
|Play Room 1|Play Room 2|Attick|NAS|Office 1|Office 2|Garden 1|Garden 2|ISP 1|ISP 2|ISP 3|ISP 4|

Patch Panel C
|C1|C2|C3|C4|C5|C6|C7|C8|
|---|---|---|---|---|---|---|---|
|A1|A2|Virtual Host|Empty|Empty|Empty|Empty|Unifi Camera Front|
