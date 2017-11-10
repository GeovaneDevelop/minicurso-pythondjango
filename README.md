# Minecurso introdutório à Web com Python e Django

## Instalação em ambiente Linux
1º Cole no terminal

	cd ~

2º Cole no terminal

	mkdir ~/www ~/env

3º Cole no terminal

	gedit ~/.bashrc

4º Cole no final do arquvivo .bashrc

	export PROJECT_HOME=~/www
	export WORKON_HOME=~/env
	source /usr/local/bin/virtualenvwrapper.sh

5º Cole no terminal Obs: Comando único

	sudo apt-get install -y python-pip python3-pip build-essential git python python3  python-dev python3-dev libsdl2-dev  libsdl2-image-dev  		libsdl2-mixer-dev  libsdl2-ttf-dev libportmidi-dev  libswscale-dev libavformat-dev libavcodec-dev zlib1g-dev ffmpeg

6º Cole no terminal Obs: Multiplus comandos

	sudo pip install --upgrade pip virtualenv setuptools
	sudo pip install virtualenvwrapper
	mkvirtualenv --no-site-packages -p /usr/bin/python3 django
	pip install django

7º [Atom](https://atom-installer.github.com/v1.21.2/atom-amd64.deb?s=1509401758&ext=.deb) editor de texto


## Instalação em ambiente Windows

1º Baixe o [Python3.6](https://www.python.org/ftp/python/3.6.3/python-3.6.3-amd64.exe) compatível com seu SO

2º Copie o path abaixo e coloque na variável do SO, Propriedades do Sistema > Configurações avançadas do sistema > Variáveis de ambiente > Edite a variável path e cole o caminho abaixo.
	
	C:\Users\"NomeDoUsuário"\AppData\Local\Programs\Python\Python36

3º Abra o cmd em 'C:\Users\"NomeDoUsuário">' e digite os dois comando abaixo.

	python -m pip install virtualenv
	mkdir virtual
	cd virtual
	python -m virtualenv django
	C:\Users\"NomeDoUsuário"\virtual\django\Scripts>activate.bat
	

4º Depois instale o Django, cole comando abaixo

	pip install django

5º [Atom](https://atom-installer.github.com/v1.21.2/atom-amd64.deb?s=1509401758&ext=.deb) editor de texto
	
