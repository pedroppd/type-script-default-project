##Fazer a instalação do Typescript na pasta do projeto, como uma dependência de desenvolvimento
<h3>
1 - npm install typescript ts-node-dev @types/node tsconfig-paths -D
</h3>
##Criar o arquivo "tsconfig.json" que conterá as configurações do Typescript##
<h3>2- npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true</h3>

##Eslint
<h3>npm i -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin</h3>

##prettier
<h3>npm add prettier -D</h3>
