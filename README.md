
    sudo su root
   ##

    adduser deploy
    
    ##
    
    usermod -aG sudo deploy

    
    ##
    
    sudo apt update
    
    ##
    
    sudo apt install npm
  ##    
    cd /home && git clone https://github.com/gillidaia/wt_install.git

    chmod -R  777 wt_install 

    ls && cd wt_install && ls && ./install_primaria

    Link do git:
    https://github.com/gillidaia/wt_files.git

