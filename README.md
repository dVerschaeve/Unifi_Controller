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
