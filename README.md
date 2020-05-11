# Starter HTML #

Starter pack para desenvolvimento de Frontend.
Instalação e configuração.

## Configuração do Software necessário ###

* Instalar GIT
* * fazer download a partir de [https://git-scm.com/downloads]

* Instalar NodeJS
* * fazer download a partir de [https://nodejs.org/en/]

* Instalar ruby
* * fazer download a partir de [http://rubyinstaller.org/]
* * * **NOTA**: Marcar as 3 opções "Install Td/Tk support", "Add Ruby executables...", "Associate .rb and .rbw files..."

* Abrir linha de comandos (GIT Bash / Windows Powershell / Terminal)
* Instalar Compass
* * **gem install compass --no-document** - (mais informações em http://compass-style.org)*
* * **Nota**: Caso a instalação páre, carregar em Enter para continuar

* Instalar o GULP
* **npm install -g gulp**

## Criar um novo projeto ##

Na linha de comandos:


* Clonar este repositório com **git clone git@bitbucket.org:xxx/starter-html.git nome_do_projeto**
* Aceder à pasta do projeto  
* * **cd nome_do_projeto**
* Executar os comandos seguintes
* * **npm install** - (Instalar o NPM no projeto)
* * **gulp** - (Arranca compilador SASS e Wiredep; automaticamente é aberto o browser em http:://localhost:3000)

## Primeiros Passos ##

**1. Adaptar os Componentes**
A partir do ficheiro localizado em: **assets\css\bootstrap\_bootstrap.scss** é possivel ativar/desativar os seguintes componentes:

*CSS*

* bootstrap/component-animations
* bootstrap/dropdowns
* bootstrap/button-groups
* bootstrap/input-groups
* bootstrap/navs
* bootstrap/navbar
* bootstrap/breadcrumbs
* bootstrap/pagination
* bootstrap/pager
* bootstrap/labels
* bootstrap/badges
* bootstrap/jumbotron
* bootstrap/thumbnails
* bootstrap/alerts
* bootstrap/progress-bars
* bootstrap/media
* bootstrap/list-group
* bootstrap/panels
* bootstrap/responsive-embed
* bootstrap/panels
* bootstrap/wells
* bootstrap/close

*JavaScript*

* bootstrap/modals
* bootstrap/tooltip
* bootstrap/popovers
* bootstrap/carousel

###NOTA###
* É sugerivel que apenas comentem os componentes que nao precisam;
* Não é recomendado desativar "@ import" fora da lista de "Components w/ JavaScript" ou "Components".

### MIXINS CHEATSHEET ###
https://gist.github.com/anthonyholmes/b397e8a95ce2aca71f8e
