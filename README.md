# terminal

-> Instalar zsh
        #apt-get install zsh

-> Cambiar la terminal por defecto a zsh(te pide contra y luego ya puedes añadir el directorio del terminal)
        #chsh

-> Instalar ohmyzsh(vas a la pagina y pillas el curl)
        -Esto es un framework de zsh, que te cambia el fichero de configuracion por uno de ellos, que tienen mejorado.

-> Ahora vamos a instalar un tema para zsh que va a ser powerlevel10k:
        #https://github.com/romkatv/powerlevel10k
        -Hay que cambiar una línea en ./zshrc:
        #ZSH_THEME="powerlevel10k/powerlevel10k"
        -Luego cuando reinicies ya te va a pedir que especifiques como quieres el terminal.

-> Si entras en el repo ya te lo pone pero si quieres volver a cambiar la configuracion:
        #p10k configure

-> Las fuentes que he usado son 4 y es la "MesloLGS NF" y estan en la carpeta fonts.

-> Despues de bajarlas hay que instalarlas, en ubuntu con dar doble click e instalar ya está.

-> Para aplicar las fuentes vamos a la terminal-preferencias-perfil-cambiar fuente y la aplicamos

-> Tambien vamos a poder aplicar estas fuentes en VSCode:
        -Visual Studio Code: Open File → Preferences → Settings (PC) or Code → Preferences → Settings (Mac), enter terminal.integrated.fontFamily in the search box at the top of Settings tab and set the value below to MesloLGS NF.
