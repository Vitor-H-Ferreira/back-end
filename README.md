# |-  Introdução sobre BACK-END  -|

# BACK-END
## O que é?
* Parte "invisível" da aplicação.
Responsável pelo processamento dos dados.
Executa a lógica de negócio.
Gerencia a comunicação entre sistemas.
Faz a conexão com o banco de dados.
# Front-end x Back-end
## Front-end
* Interface visual.
Interação com o usuário.
Foco em UX e UI.
Executado no navegador.
## Back-end
* Processa informações.
Controla regras do sistema.
Garante segurança.
Gerencia armazenamento de dados.
Executado no servidor.
# API
## O que é?
* Ponte entre o Front-end e o Back-end.
Recebe requisições.
Envia respostas.
Não permite acesso direto ao banco de dados.
## Funções da API
* CRUD (Criar, Ler, Atualizar e Deletar).
Validar dados.
Autenticar usuários.
Proteger informações.
Organizar rotas.
## Boas práticas da API
* Validar todos os dados recebidos.
Não expor senhas e dados sensíveis.
Proteger rotas com autenticação.
Retornar apenas os dados necessários.
Deixar a interface para o Front-end.
# Node.js
## O que é?
* Ambiente de execução JavaScript.
Permite executar JavaScript no servidor.
Baseado no motor V8 do Google.
Utilizado para desenvolvimento Back-end.
## Vantagens
* Alta velocidade.
E/S (Entrada e Saída) não bloqueante.
Grande quantidade de bibliotecas.
Mesmo JavaScript no Front-end e Back-end.
# E/S Não Bloqueante
* O servidor não fica esperando uma tarefa terminar.
Continua atendendo outras requisições.
Melhor desempenho.
Maior concorrência.
Menor consumo de recursos.
# Promises
* Utilizadas para operações assíncronas.
Estados:
###### Pending - Operação em andamento.
###### Fulfilled - Operação concluída com sucesso.
###### Rejected - Operação falhou.
# Pacotes (Packages)
## O que são?
* Blocos de código reutilizáveis.
Desenvolvidos por outros programadores.
Evitam criar tudo do zero.
Aumentam a produtividade e a segurança.
# NPM (Node Package Manager)
* Funções
Buscar pacotes.
Instalar pacotes.
Gerenciar dependências.
Atualizar bibliotecas.
# package.json
## Arquivo responsável por:
* Nome do projeto.
Versão.
Descrição.
Scripts.
Dependências.
Autor.
Licença.
# Comandos Principais
* npm init -y 
###### Cria o package.json.
* npm install <pacote>
###### Instala um pacote.
* npm uninstall <pacote>
###### Remove um pacote.
* npm update
###### Atualiza os pacotes.
* npm start
###### Inicia a aplicação.
# Pacotes Essenciais
## Express
* Cria servidores.
Gerencia rotas.
Processa requisições HTTP.
Facilita a criação de APIs.
## Nodemon
* Reinicia automaticamente o servidor.
Detecta alterações no código.
Aumenta a produtividade.
## MySQL2
* Faz a conexão com o banco MySQL.
Executa consultas.
Suporta operações assíncronas.
Alto desempenho.
## CORS
* Controla quais aplicações podem acessar a API.
Libera requisições entre origens diferentes.
Aumenta a segurança.
## Chalk
* Colore mensagens no terminal.
Facilita identificar erros, avisos e sucessos.