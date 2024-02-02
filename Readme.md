# The Originals Automation Postman


### Projeto de automação com Postman e Report com Newman

Projeto de automação com Postman.

## Instalação
```bash
    npm install -g newman
    npm install -g newman-reporter-htmlextra
```

## Execução com report html extra
```bash
    newman run signup.json -e env-automacao.json -g env-global.json
```

## Git e GitHub

No Git e GitHub, realize as seguintes etapas:

### **Instalar e Configurar uma conta no Git** 

Instale e Configure uma conta no Git. Para saber mais, [acesse o Git](https://git-scm.com/download/win).

### **Verificando se existe a Chave SSH** 
 
Verifique se tem uma Chave SSH cadastrada, para que você possa conectar o seu repositório local com o repositório remoto. Para saber mais, [acesse o conteúdo do GitHub](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh).

 Abra o Git Bash e digite:

 ```sh default
 ls -al ~/.ssh
 ```
 <p align="center">
  <img src="./.images/verifica_chave_ssh.png" alt="verifica chaves SSH existentes" width="45%" />

### **Para clonar o repositório fazer:**

 ```sh default
 git clone https://github.com/rhswire/theoriginals-academy-postman.git
 ```
 
### **Transferindo arquivos do repositório local para o repositório Git** 

Dentro do repositório local, abra o Git Bash e digite:

 1. Adicionar todos os ficheiros alterados
 ```sh default
 git add .
 ```
 2. Colocar na zona de "preparação do computador"
 ```sh default
 git commit -m "nome ou descrição da inclusão ou alteração"
 ```
 3. Criar nome para as versões
 ```sh default
 git tag -a vx.x -m "version x.x"
 ```
 4. Para carregar as alterações no Git
 ```sh default
 git push origin main
 ```

 <p align="center">
  <img src="./.images/transferindo_alteracoes.png" alt="verifica chaves SSH existentes" width="60%" />

## Projeto Desenvolvido por: 
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/137322187?v=4" width=90><br/><sub>Danielle Sousa</sub>](https://github.com/rhswire)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/daniellesousadads/)](https://www.linkedin.com/in/daniellesousadads/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/116200326?v=4" width=90><br/><sub>Karine Bueno</sub>](https://github.com/karinebueno)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/karinebueno-quality-assurance-tester/)](https://www.linkedin.com/in/karinebueno-quality-assurance-tester/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/93127535" width=90><br/><sub>Raquel Swire Guimarães</sub>](https://github.com/rhswire)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rhswire)](https://www.linkedin.com/in/rhswire) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/92730333?v=4" width=90><br/><sub>Rebeca Swire</sub>](https://github.com/BekaSwire)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rebeca-swire/)](https://www.linkedin.com/in/rebeca-swire/) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/106667633?v=4" width=90><br/><sub>Thalita Lisboa</sub>](https://github.com/ThalitaLisboa)<br/>[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thalita-lisboa/)](https://www.linkedin.com/in/thalita-lisboa/)
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |