# MacOS vim settings

Steps:
 * install brew
 * create custom settings file ~/.vimrc
 * create plugin directory ~/.vim
 * install vim patogen - plugin manager for vim
   **execute 
	```
	mkdir -p ~/.vim/autoload ~/.vim/bundle && \
	curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
	```
   **inser this into .vimrc:
      ```
		execute pathogen#infect()
		syntax on
		filetype plugin indent on
	  ```	
  **Finally** All the plugins will be installed into ~/.vim/bundle and automatically added to vim runtime

