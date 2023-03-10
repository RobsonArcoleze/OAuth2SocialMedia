# OAuth2SocialMedia
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE)

Aplicação simples para implementar alguns conceitos de segurança utilizando Spring Security e OAuth2.

## Informações sobre o código

Utilizando a implementação do OAuth2 foi possivel permitir acesso a aplicação usando perfil do google e do linkedin.

**Passo 1**

- Criar Perfil de desenvolvedor no google e linkedin
  - https://console.cloud.google.com/
  - https://www.linkedin.com/developers/
  
 **Passo 2:**
- Google:
  - Crie uma credencial de aplicativo e configure a Autorização
  URI de domínio e URI de redirecionamento para o domínio do seu aplicativo
  - Configure seu arquivo de propriedades com seu client_id e client_secret
- Linkedin:
  - Crie um aplicativo no link do desenvolvedor do linkedin com sua página do linkedin.
  - Verifique se você está vinculado ao aplicativo.
  - Configure o URI do domínio de autorização e o URI de redirecionamento para o domínio do seu aplicativo.
  - Configure seu arquivo de propriedades com seu client_id e client_secret.
  - Configure suas propriedades com a configuração do provedor linkedin.

Para executar este aplicativo:
- Depois de configurar o arquivo de propriedades do aplicativo
  - execute o projeto no seu IDE
  - acesse http://localhost:8080 no seu navegador
  - escolha seu servidor de autenticação
 
 
 
![img](https://github.com/RobsonArcoleze/OAuth2SocialMedia/blob/main/img/socialLogin.png)

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git@github.com:RobsonArcoleze/OAuth2SocialMedia.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```
  
# Autor

Robson de Oliveira Arcoleze

https://www.linkedin.com/in/robsonarcoleze/  
