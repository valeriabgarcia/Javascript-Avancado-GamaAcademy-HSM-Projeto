Passo 0 - Criaro os arquivos database.js e app.js
Passo 1 - No arquivo database crie e exporte a sua base no formato array de objetos contendo alguns dos livros que você já leu ou gostaria de ler com os seguintes campos:
	nome: string
	categoria: string
	autor: string
	paginas: number
	recomenda: boolean
	leu: boolean
Passo 2: npm init -y 
	**vai ser criado o arquivo package.json
	** dentro do package.json, deixar "scripts": {"start": "node app.js"},
Passo 3: npm i --save readline-sync
Passo 4: criar .gitignore
	** node_modules
Passo 5 - No arquivo app.js desenvolva sua lógica 
Passo 6: Rodar projeto npm start