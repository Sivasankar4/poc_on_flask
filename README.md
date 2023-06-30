# poc_on_flask
a simple example of how we run a flask application using miniconda


#prerequisites
1.linux based OS
2.latest version of miniconda installed
3.docker installed
4.Visual Studio Code


conda Installation:

$cd /tmp
$wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
$chmod +x Miniconda3-latest-Linux-x86_64.sh./Miniconda3-latest-Linux-x86_64.sh 
$conda config --set auto_activate_base false
$conda create -n py38 -y python=3.8

conda activation and deactivation commands:

$conda activate py38
$conda deactivate

docker installation:

Update the apt package index and install packages to allow apt to use a repository over HTTPS:


 $sudo apt-get update
 $sudo apt-get install ca-certificates curl gnupg
