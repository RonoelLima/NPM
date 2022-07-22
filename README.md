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

17. "npm outdated" - verifica os pacotes que estão desatualizados e apresenta o nome do pacote, versão atual, versão disponível e nome do projeto;

18. "npm update" - atualiza os pacotes pendentes de atualização - Atenção, cuidado para não quebrar a aplicação, antes de realizar a atualização verifique a documentação do pacote;

19. "npm cache verify" , "npm chache clean --force";

20. "npm audit" - verifica vulnerabilidades nos pacotes instalados e mostra um relatório deletalhado. 

21. "npm audit fix" - realiza uma tentativa de corrigir os problemas encontrados e as vunerabilidades do projeto.     

22. "npm view "pacote" - realiza uma busca e retorna algumas informações sobre o pacote na base do npm.

23. "npm docs "pacote" - redireciona para página oficial do pacote na internet.

24. "npm dedupe" - verifica a existência de pacotes duplicados.           


