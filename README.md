# NPM

Comandos do NPM - para mais informações podemos acessar o site oficial do npm: https://docs.npmjs.com/cli/v8/using-npm/config

1. "npm - v" - apresenta a versão do npm instalada;

2. "npm install latest-version" - instala a versão mais recente do npm;

3. "npm init --yes" - cria o package.json com as configurações padrões do npm, podendo alterar depois o arquivo criado;

4. "npm config set init-author-name "nome" - seta nas configurações do npm por padrão o nome informado;

5. "npm config set init-author-email "email" - seta nas configurações do npm por padrão o email informado; 

6. "npm config set init-author-license "license" - seta nas configurações do npm por padrão a license informada;

7. "npm get" mostra todas as chaves de configuração que serão gravadas no package.json;

8. "npm config set init-author-url "htpps://eixo3engenharia.web.app" - seta por padrão uma url nas configurações do projeto;

9. "npm config delete "chave" " - deleta a chave selecionada para ser deletada;

10. "npm install "pacote" -g" - instala um pacote de forma global que não vai aparecer na relação de pendências do package.json;

11. "npm link" - realiza o link entre um pacote instalado globalmente em um porjeto que não tem esse pacote instalado em suas dependências; 

12. "npm remove "pacote" -g" - remove um pacote instalado globalmente 

13. "npm list" - lista todas as dependências instaladas no projeto; 

14. "npm list --deph=0" lista as dependências instaladas sem mostrar as subdependências instaladas;

15. "npm prune" verifica as dependências que estão presentes na pasta node-modules e não estão sendo utilizadas na lista de dependências do projeto no package.json;

16. "npm search "pacote" " - procura pacotes pela linha de comandos do terminal e mostra o resultado da busca com o nome, descrição, author, versão e palavra chave;         


