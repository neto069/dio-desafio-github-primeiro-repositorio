Link para download do git: https://git-scm.com/downloads
O Git Bash é um terminal extendido para otimizar o uso do Git.

### Comandos Básicos git

* **Gitt add** (Este comando adiciona os arquivos solicitados ao ambiente de stage, é uma forma de dizer que o *git* que você deseja que as modificações daquele arquivo seja, gravadas na próxima remessa. Ex.: git add . )
* **Git commit**   *Agora fazemos a gravação em si das modificações, desta forma criamos um snapshot do estado atual do nosso projeto. Uma forma muito usada é o **git commit -m**  "Descrição das atualizações do projeto " onde o -m é uma flag que aponta para a mensagem em descrição.*  
* **Git push** *Por fim precisamos subir essas informações no nosso repositório remoto, para isso basta utilizar o comando **gitpush** e, se já estiver tudo devidamente configurado, os arquivos serão salvos no repositório remoto correspondente ao seu repositório local!*
* **Git branch**  _É usado para verificar todas as branches presentes no repositório. Ao utilizar a flag -r no final do comando é possível ver todas as branches presentes no repositório remoto e se você quiser criar uma nova branch basta utilizar este comando: git branch <branch_name>._
* **Git checkout** _É o comando utilizado para trocar de branch passando o nome da branch destino no final do comando. Caso a flag -b seja colocada após o “checkout” é possível criar a branch em questão e já trocar para esta imediatamente._
* **Git Status** _Este comando permite ver quais arquivos estão sendo “rastreados” pelo git e quais modificações já foram enviadas para o stage. É bem útil para quando se tem dúvidas sobre o que está sendo enviado_

***

---

