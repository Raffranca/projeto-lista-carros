# ListaCarros

Projeto proposto como teste técnico.
A aplicação consiste em uma lista de carros contendo marca, modelo, cor e valor. 
Para que os dados sejam renderizados foi utilizada uma API criada a partir do JSON-server, a qual simula uma API rest.
É possível que o usuario faça todas as requisições HTTP.
-----------------------------------------------
No projeto foi utilizado a estrutura SPA (Single page application), um conceito de gerar experiência para os usuários, atualizando partes do código em vez da página inteira.

## `Tecnologias usadas:`
| Ferramenta | Descrição |
| --- | --- |
| `Angular` | Framework |
| `JSON-server` | Gerar API |
| `HttpClientModule` | Biblioteca para consumir API|
| `FormsModule` | Biblioteca para criação de formularios|
| `CSS ` | Folha de estilo|
| `npm ` | Gerenciador de pacotes|

---------

## 📁 Arquitetura 

```
 📁 projeto
   |
   |-  📁 src
   |    |
   |    |- 📁 app
   |         |- 📁 models
   |              |- 📄 car.ts
   |
   |         |- 📁 services
   |              |- 📄 car.service.spec.ts
   |              |- 📄 car.service.ts   
   |         |- 📄 app.componet.css
   |         |- 📄 app.componet.html
   |         |- 📄 app.componet.spec.ts        
   |         |- 📄 app.componet.ts  
   |         |- 📄 app.module.ts        
   |
   |    |- 📁 assets
   |         |- 📁 data
   |               |- 📄 db.json 
   |               |- 📄 .gitkeep 
   |
   |    |- 📁 environments
   |         |- 📄 environment.prod.ts
   |         |- 📄 environment.ts
   |                
   |    |- 📄 main.ts
   |    |- 📄 polyfills.ts
   |    |- 📄 styles.css 
   |    |- 📄 test.ts
   |
   |    |- 📄 package-lock.json
   |    |- 📄 package.json
   |    |- 📄 proxy.conf.json
   |    |- 📄 README.md
   |    |- 📄 tsconfig.app.json
   |    |- 📄 tsconfig.json
   |    |- 📄 tsconfig.spec.json
   |      
   |

```