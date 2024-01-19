# Estrutura de pastas
dev->styles->main.css
dev->scripts
dev->index.html

dist->styles->main.min.css
dist->scripts
dist->index.html

src->styles->main.less
src->scripts->main.js
src->index.html (<link rel="stylesheet" href="@@ENDERECO_DO_CSS">)

#Instalar e configurar o grunt

'npm i -g grunt-cli'
'npm init'
'npm i --save-dev grunt'
'npm i --save-dev grunt-contrib-less'
'npm i --save-dev grunt-contrib-sass'
'npm i --save-dev grunt-concurrent'
'npm i --save-dev grunt-contrib-watch'
'npm i --save-dev grunt-replace'
'npm i --save-dev grunt-contrib-htmlmin'
'npm i --save-dev grunt-contrib-clean'
'npm i --save-dev grunt-contrib-uglify'

criar main.less ou crar main.scss

Ir no package.json e:
    criar novo scripit 
    "grunt": "grunt",
    "build": "grunt build",

Criar arquivo de configuração do grunt Gruntfile.js

copiar o conteúdo deste projeto

npm run grunt build -> para gerar a build (feito)
npm run grunt -> para gerar o dev (fazendo)

No vercel:
BUILD COMMAND npm run build
OUTPUT DIRECTORY dist