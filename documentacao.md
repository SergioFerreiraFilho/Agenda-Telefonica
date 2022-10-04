 ## Documentação para Utilizar a Agenda Telefonica ##

Primeiro e Preciso ter instalado o NodeJS, acesse `https://nodejs.org/`, faça o download e instale no seu computador.

## Instale o servidor JSON ##

Execute no terminal( Pode ser tanto utilizado o PowerShell, como o Terminal do GitBash): `npm install -g json-server`

## Iniciando o servidor, e utilizando a Agenda Telefonica ##

Com a pasta aberta, utilize o comando no terminal: `npx json-server db.json --port 8000`

No endereço http://localhost:8000 o servidor ira ser rodado.

Dentro do arquivos eventos, existe uma variante chamada API_URL, caso queria mudar a porta, mude nesta variante.

Pronto, agora basta abrir o arquivo `index.html` com seu navegador.

## Funcionalidades ##

Quando a pagina for exibida, ira ter algumas funções que são facilmente visualizadas, sendo elas :

ADICIONAR CONTATO: Com esta função você ira adicionar um contato a lista telefonica.

EDITAR: Ira fazer a possibilidade de editar informações de um contato

BUSCAR: Busca os contatos adicionandos, o mesmo não e "Case Sensitive"

EXCLUIR: Irá fazer a exclusão de um contato (Cuidado, esta ação não pode ser revertida)