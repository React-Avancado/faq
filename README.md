## FAQ

> Dúvidas e erros frequentes do curso de [React Avançado](https://reactavancado.com.br/) e coisas relacionadas também.

Abaixo segue o índice com todas as coisas, sinta-se a vontade para adicionar novas dúvidas/soluções. E caso não encontre direto no índice, tenta dar um `search` primeiro, as vezes não está no título, mas está dentro do documento, um `ctrl+F` sempre ajuda =)

Para dúvidas sobre termos/ferramentas usados no curso, temos também o [Glossário](https://github.com/React-Avancado/links-estudo/blob/master/glossary.md)

## Índice

- [FAQ](#faq)
- [Índice](#índice)
  - [Qual plugin você usa para graphql/cor/tema/etc?](#qual-plugin-você-usa-para-graphqlcortemaetc)
  - [Meu prettier não está formatando o código](#meu-prettier-não-está-formatando-o-código)
  - [Cannot find module 'prettier' / Cannot find module 'jsdom' (insira qualquer outro aqui)](#cannot-find-module-prettier--cannot-find-module-jsdom-insira-qualquer-outro-aqui)
  - [Command not found: eslint](#command-not-found-eslint)
  - [Warnings aparecendo ao rodar algum yarn add / npm install](#warnings-aparecendo-ao-rodar-algum-yarn-add--npm-install)
  - [Meu NVM sempre para de funcionar quando reinicio o terminal](#meu-nvm-sempre-para-de-funcionar-quando-reinicio-o-terminal)
  - [Error Cannot create "/usr/local/bin/create-next-app" due to insufficient permissions.](#error-cannot-create-usrlocalbincreate-next-app-due-to-insufficient-permissions)
  - [Meu `test:watch` não está funcionando, ele roda os testes e acaba](#meu-testwatch-não-está-funcionando-ele-roda-os-testes-e-acaba)
  - [Como saber os types do NextJS?](#como-saber-os-types-do-nextjs)
  - [sudo: service: command not found](#sudo-service-command-not-found)
  - [Cannot find module 'core-js/modules/es.array.iterator'](#cannot-find-module-core-jsmodulesesarrayiterator)
  - [Can't resolve `@ckeditor/ckeditor5-build-classic`](#cant-resolve-ckeditorckeditor5-build-classic)
  - [Como rodar o dump no Docker? O comando `psql` não existe](#como-rodar-o-dump-no-docker-o-comando-psql-não-existe)
  - [Como exportar a base localmente com o Docker?](#como-exportar-a-base-localmente-com-o-docker)
  - [pg_restore: error: could not read from input file: end of file](#pg_restore-error-could-not-read-from-input-file-end-of-file)
  - [Server wasn't able to start properly.](#server-wasnt-able-to-start-properly)
  - [Como usar o Docker no Windows?](#como-usar-o-docker-no-windows)
  - [Estou usando o WSL mas está muito lento!](#estou-usando-o-wsl-mas-está-muito-lento)
  - [error The client `pg` is not installed](#error-the-client-pg-is-not-installed)
  - [O termo 'NODE_ENV=production' não é reconhecido como nome de cmdlet](#o-termo-node_envproduction-não-é-reconhecido-como-nome-de-cmdlet)
  - [Not implemented: window.computedStyle ao rodar os testes](#not-implemented-windowcomputedstyle-ao-rodar-os-testes)
  - [Cannot read property 'map' of undefined](#cannot-read-property-map-of-undefined)
  - [Property 'propriedade_aqui' does not exist on type 'propriedade'](#property-propriedade_aqui-does-not-exist-on-type-propriedade)
  - [Não tem mais opção de selecionar template ao rodar create-next-app](#não-tem-mais-opção-de-selecionar-template-ao-rodar-create-next-app)
  - ['Error: You have both a "main" and a "config"' ao rodar o Storybook](#error-you-have-both-a-main-and-a-config-ao-rodar-o-storybook)
  - [Como fazer o Storybook funcionar com caminho absoluto](#como-fazer-o-storybook-funcionar-com-caminho-absoluto)
  - [You are currently running a version of TypeScript which is not officially supported by @typescript-eslint/typescript-estree.](#you-are-currently-running-a-version-of-typescript-which-is-not-officially-supported-by-typescript-eslinttypescript-estree)
  - [Connection test failed: autenticacao do tipo password falhou para usuario "strapi"](#connection-test-failed-autenticacao-do-tipo-password-falhou-para-usuario-strapi)
  - [rating must be one of the following values: FREE, pegi3, pegi7, pegi12, pegi16, pegi18 | GoG não tá retornando os ratings](#rating-must-be-one-of-the-following-values-free-pegi3-pegi7-pegi12-pegi16-pegi18--gog-não-tá-retornando-os-ratings)
  - ["Expected a value of type \"ENUM_COMPONENTPAGESOCIALLINKS_TITLE\" but received: \"Dribble\"](#expected-a-value-of-type-enum_componentpagesociallinks_title-but-received-dribble)
  - [Estou usando tanto a API como o Client no mesmo repositório, como subo no Heroku?](#estou-usando-tanto-a-api-como-o-client-no-mesmo-repositório-como-subo-no-heroku)
  - [Meu SVG não está pegando no Cloudinary.](#meu-svg-não-está-pegando-no-cloudinary)
  - [Cannot find module 'utils/tests/helpers' from 'src/components/Main/test.tsx'](#cannot-find-module-utilstestshelpers-from-srccomponentsmaintesttsx)
  - [Cannot find module '../build/Release/sharp.node'](#cannot-find-module-buildreleasesharpnode)
  - [Estou recebendo `no-unused-vars` em coisas do TypeScript](#estou-recebendo-no-unused-vars-em-coisas-do-typescript)
  - [toHaveStyle tá dando erro nos testes](#tohavestyle-tá-dando-erro-nos-testes)
  - [BABEL ssr is not a valid Plugin property](#babel-ssr-is-not-a-valid-plugin-property)
  - [O termo 'touch' não é reconhecido como nome de cmdlet, função, arquivo de script](#o-termo-touch-não-é-reconhecido-como-nome-de-cmdlet-função-arquivo-de-script)
  - [System limit for number of file watchers reached, watch](#system-limit-for-number-of-file-watchers-reached-watch)
  - [Esqueci meu usuário/senha de Admin do Strapi, como faço?](#esqueci-meu-usuáriosenha-de-admin-do-strapi-como-faço)
  - [As fotos dos autores não aparecem na Landing Page](#as-fotos-dos-autores-não-aparecem-na-landing-page)
  - [Error: Validation error - slug must match the following](#error-validation-error---slug-must-match-the-following) 
  - [Qual é o link do Figma da Won Games?]()

---

### Qual plugin você usa para graphql/cor/tema/etc?

Todas as extensões que uso no curso podem ser baixadas [aqui](https://marketplace.visualstudio.com/items?itemName=willianjusten.reactavancado-extension-pack) ou só buscar por `React Avançado Extension Pack` dentro do VS Code e baixar por lá.

---

### Meu prettier não está formatando o código

1. Verifique se você já instalou o pacote do `prettier`, como no [boilerplate](https://github.com/React-Avancado/boilerplate/blob/master/package.json#L59).

Caso não tenha, instale com `yarn add -D prettier`, reinicie o editor e tente novamente.

2. Verifique se o teu VS Code está configurado para formatar ao salvar. Você precisa ter um arquivo *na raiz do projeto* como [.vscode/settings.json](https://github.com/React-Avancado/boilerplate/blob/master/.vscode/settings.json), segue abaixo o código:

```json
{
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```

3. Se já fez tudo acima e ainda não funciona, verifique se o seu arquivo do [.eslintrc.json](https://github.com/React-Avancado/boilerplate/blob/master/.eslintrc.json#L18) está configurado corretamente com o plugin do prettier sendo passado.

---

### Cannot find module 'prettier' / Cannot find module 'jsdom' (insira qualquer outro aqui)

Sempre que tiver um erro dizendo `cannot find module` significa que você não tem o pacote que está tentando importar. Verifique se o nome está escrito certo e caso esteja tudo certo, verifique se está de fato instalado, caso contrário, é só instalar com:

```sh
# caso seja uma dependência de desenvolvimento
yarn add -D <nome_modulo>

# caso seja uma dependência do projeto
yarn add <nome_modulo>
```

---

### Command not found: eslint

Se você tentar rodar o `eslint` diretamente pelo terminal e der esse erro, isso indica que você não tem o `eslint` instalado globalmente no seu sistema. Você tem duas opções:

1. Instalar globalmente com `npm install -g eslint` ou `yarn global add eslint`.
2. Rodar através do projeto com `yarn lint` (verifique se possui o comando no `package.json`) ou com `yarn eslint`.


---

### Warnings aparecendo ao rodar algum yarn add / npm install

É normal terem alguns warnings dependendo da dependência e suas sub dependências.

Isso ocorre quando alguma dependência interna é depreciada ou modificada ou tem algum erro de segurança.

Não precisa se preocupar que em 99% dos casos isso não chega a te afetar. Quem precisa verificar e mudar é a biblioteca em questão.


---

### Meu NVM sempre para de funcionar quando reinicio o terminal

Se você está usando o WSL e está tendo problema com o NVM, basta adicionar a linha:

```sh
source ~/.zsh-nvm/zsh-nvm.plugin.zsh
```

No seu arquivo `.zshrc` e então reiniciar seu terminal, prontinho, estará funcionando normalmente.

---

### Error Cannot create "/usr/local/bin/create-next-app" due to insufficient permissions.

É possível que você esteja tentando rodar o comando em alguma pasta sem permissão ou até mesmo que tenha instalado globalmente e para o usuário em questão você não está tendo permissão. Recomendo que remova qualquer traço do comando global, com:

```sh
# tente remover via npm primeiro
npm uninstall -g create-next-app

# ou então remova direto a pasta
# primeiro verifique onde está o comando com
which create-next-app

# com a pasta retornada, use o comando
rm -rf <pasta> # por padrão, costuma ser /usr/bin/create-next-app
```

Após removido, utilize o comando através do `npx` para não necessitar instalar nada na máquina.

```sh
npx create-next-app nome-do-app
```

---

### Meu `test:watch` não está funcionando, ele roda os testes e acaba

Nosso comando no boilerplate está utilizando o `yarn` e nele nós podemos passar simplesmente como:

```sh
yarn test --watch
```

Mas no `npm` nós precisamos passar dois traços `--` para passar o comando abaixo e de fato funcionar, ou seja, o comando precisa ser:

```sh
npm run test -- --watch
```

---

### Como saber os types do NextJS?

Todos os types estão definidos no [repositório oficial](https://github.com/vercel/next.js/tree/canary/packages/next/types).

---

### sudo: service: command not found

Se você tentou usar o comando `service` no MacOS é bem possível que você recebeu esse erro, afinal de contas o `service` é um comando para inicializar serviços no Linux.

No Mac você pode usar:

```sh
brew services start <nome-do-serviço>
brew services stop <nome-do-serviço>
brew services restart <nome-do-serviço>
```

---

### Cannot find module 'core-js/modules/es.array.iterator'

Se você estiver tendo esse erro é possível que está rodando com o `npm` e portanto ele não tem polyfill para certos métodos do es6 e quebra. Normalmente mudar para utilizar o `yarn` já resolve o problema.

Outra maneira é instalar o pacote do `core-js` com:

```sh
npm install -D core-js
```

---

### Can't resolve `@ckeditor/ckeditor5-build-classic`

Se você tiver ao tentar subir o projeto do Strapi no Heroku, basta adicionar um método de `postinstall` no projeto para que ele instale as dependências do plugin, segue [o commit de como fazer](https://github.com/React-Avancado/landing-page-api/pull/1/commits/66029a0ebf42f1efb63182f7ccd824fdd83ef56a)

---

### Como rodar o dump no Docker? O comando `psql` não existe

Existem várias formas de rodar o comando, o mais simples e indicado é:

```sh
cat strapi.sql | docker exec -i NOME_DO_SEU_CONTAINER psql -U SEU_USUARIO -d SUA_DATABASE
```

---

### Como exportar a base localmente com o Docker

Esse comando irá exportar a base de dados para a sua máquina com o seguinte formato: `DUMP_DIA-MES-ANO_HORA_MINUTO_SEGUNDO`, por exemplo, DUMP_06-10-2020_09_27_44.

```sh
docker exec -i NOME_DO_SEU_CONTAINER pg_dump --username SEU_USUARIO --password SUA_DATABASE > DUMP*`date +%d-%m-%Y"_"%H_%M_%S`.sql
```

---

### pg_restore: error: could not read from input file: end of file

Se você tiver esse problema quando estiver tentando importar o `dump` lá do S3, é muito possível que você não tenha liberado as permissões para o arquivo. Basta entrar no painel do S3, selecionar o arquivo e então na parte das permissões, deixar como público.

---

### Server wasn't able to start properly.

Se você fez o Dump e começou a ter esse erro, é muito possível que terá uma linha logo abaixo com algo similar a:

```sh
[2020-07-25T14:16:53.112Z] error error: column "<algum nome aqui>" contains null values
```

Isso acontece pois a estrutura que você montou está com alguma coisa diferente de como eu construí e é por isso que o dump acaba não preenchendo o dado e aí acaba quebrando.

A dica é você comparar seus arquivos com [a api do repositório](https://github.com/React-Avancado/landing-page-api/tree/master/api) e também [os componentes](https://github.com/React-Avancado/landing-page-api/tree/master/components/page), muito possivelmente irá achar o arquivo com o campo diferente.

Ao achar a diferença, as soluções são:

- Substituir o seu arquivo pelo arquivo oficial
- Apagar o banco defeituoso
- Rodar o dump novamente

Ou você também pode verificar se o campo possui `required: true` na model e então remover, isso vai permitir valores `null` no banco e assim o Strapi vai conseguir inicializar e aí basta você preencher esse dado faltante.

---

### Como usar o Docker no Windows?

A primeira coisa que recomendo é que você utilize o WSL, [aqui eu ensino como configurar tudo em 30min](https://www.youtube.com/watch?v=YcR8pKvjx44&list=PLlAbYrWSYTiOpefWtd6uvwgKT1R-94Zfd).

E já tendo o WSL configurado, basta [seguir os passos da documentação](https://docs.docker.com/docker-for-windows/wsl/). Você irá instalar e rodar o Docker do lado do Windows, mas com a opção de habilitar o docker no WSL.

---

### Estou usando o WSL mas está muito lento!

Verifique se você não está rodando com os arquivos do lado do Windows como: `C:\...`. O indicado é **ter sempre** do lado do WSL, algo como `/development/...`

Verifique se a versão que está rodando é a WSL2, ela é bem rápida que sua versão anterior. Para verificar, abra o Windows Powershell e rode o comando:

```sh
wsl --list --verbose

# deve retornar algo como
  NAME                   STATE           VERSION
* Ubuntu-20.04           Running         2
  docker-desktop         Running         2
  docker-desktop-data    Running         2
```

---

### error The client `pg` is not installed

Isso pode acontecer na hora de subir no Heroku se você não tiver a dependência instalada no projeto, para corrigir é só instalar com:

```sh
yarn add pg
```

---

### O termo 'NODE_ENV=production' não é reconhecido como nome de cmdlet

Esse erro acontece no Windows, pois ele não identifica corretamente as variáveis de ambiente.

A primeira coisa que recomendo é que você utilize o WSL, [aqui eu ensino como configurar tudo em 30min](https://www.youtube.com/watch?v=YcR8pKvjx44&list=PLlAbYrWSYTiOpefWtd6uvwgKT1R-94Zfd).

Mas caso queira continuar usando o Windows, você precisa instalar um pacote chamado `cross-env` com o comando:

```sh
yarn add -D cross-env
```

E depois modificar o seu comando para ficar:

```sh
cross-env NODE_ENV=production yarn build
```

---

### Not implemented: window.computedStyle ao rodar os testes

Esse erro acontece quando você tenta rodar métodos do `jest-dom` e não o tem configurado. Para configurar, você precisa ter um arquivo [.jest/setup.ts](https://github.com/React-Avancado/boilerplate/blob/master/.jest/setup.ts#L1) e então chamar o setup na configuração do [jest.config.js](https://github.com/React-Avancado/boilerplate/blob/master/jest.config.js#L6).


---

### Cannot read property 'map' of undefined

Esse é um erro muito comum no JavaScript e muitas pessoas tem dificuldade, então vamos tentar entender o que está acontecendo.

O erro diz que não consegue usar `map` em `undefined`, isso significa que o array que você está tentando percorrer não existe. Pensemos no seguinte código:


```js

const arr = [1, 2, 3];

// aqui vai funcionar normal, afinal de contas o `arr` existe e é de fato um array
arr.map(n => console.log(n))

// aqui ele vai dizer exatamente "Cannot read property 'map' of undefined"
arrayQueNaoExiste.map(n => console.log(n))
```

Nesses casos, você precisa verificar:

- O array realmente foi criado?
- O nome que está chamando está correto?
- Você está passando essa variável para dentro do componente?

Faça essas verificações, tente ler o código e ir entendendo o processo.

---

### Property 'propriedade_aqui' does not exist on type 'propriedade'

Esse é um erro super comum do TypeScript, verifique na criação do seu Type Alias se a propriedade foi de fato criada, normalmente você esqueceu de criar. Segue exemplo:

```ts

type AuthorProps = {
  name: string
  description: string
}

// Property 'age' does not exist on type 'AuthorProps'.
const renderAuthor = ({ name, description, age }: AuthorProps) => (...)

```

---

### Não tem mais opção de selecionar template ao rodar create-next-app

De fato nas novas versões não existe mais a opção, mas você pode buscar o exemplo na lista oficial:

https://github.com/vercel/next.js/tree/canary/examples

E então pode rodar o comando:

```sh
npx create-next-app myapp -e <nome-do-exemplo>
```

Ou se você quiser usar um boilerplate específico, basta rodar:

```sh
npx create-next-app myapp -e <url-do-boilerplate>
```

---

### 'Error: You have both a "main" and a "config"' ao rodar o Storybook

Depois da atualização do Storybook 6, a configuração ficou mais simplificada, agora podemos ter somente a `main.js` e o `preview.js` caso queira adicionar algum wrapper.

Você pode seguir o padrão [do boilerplate oficial](https://github.com/React-Avancado/boilerplate/tree/master/.storybook)

---

### Como fazer o Storybook funcionar com caminho absoluto

Para importar o componente direto como `components/Logo` ao invés de `../src/components/Logo` basta editar o seu arquivo `main.js` de configuração do Storybook para incluir as seguintes linhas:

```js
webpackFinal: (config) => {
  config.resolve.modules.push(`${process.cwd()}/src`)
  return config
}
```

Você pode ver o [arquivo completo aqui](https://github.com/React-Avancado/boilerplate/blob/master/.storybook/main.js)

---

### You are currently running a version of TypeScript which is not officially supported by @typescript-eslint/typescript-estree.

Basta verificar se a versão do Eslint e do TypeScript estão na mesma major version, ou seja, tudo `4.x` ou `3.x`. Recomendo usar a `4.x` visto que é a versão atual.

---

### Connection test failed: autenticacao do tipo password falhou para usuario "strapi"

Verifique se o serviço do banco está de fato em pé e também verifique se as configurações (host, porta, username e password) estão corretos.

---

### rating must be one of the following values: FREE, pegi3, pegi7, pegi12, pegi16, pegi18 | GoG não tá retornando os ratings

Aparentemente a GoG mudou essa parte do rating para verificar de acordo com o país. Para o Brasil eles estão usando:

https://items.gog.com/brazilian_ratings/L.png
https://items.gog.com/brazilian_ratings/10.png
https://items.gog.com/brazilian_ratings/12.png
https://items.gog.com/brazilian_ratings/14.png
https://items.gog.com/brazilian_ratings/16.png
https://items.gog.com/brazilian_ratings/18.png

O ideal é mudar o `enum` do `rating` para ficar de acordo com os novos dados. Segue o [commit da mudança](https://github.com/Won-Games/api/commit/8867654658b966c90fa3635f547d3dfdb19863c8).

---

### "Expected a value of type \"ENUM_COMPONENTPAGESOCIALLINKS_TITLE\" but received: \"Dribble\"

Verifique o seu arquivo de [social-links](https://github.com/React-Avancado/landing-page-api/blob/master/components/page/social-links.json#L11-L17), os nomes precisam ser exatamente iguais ao do Enum.

Exemplo, se o erro for no `Dribble`, é porque ele precisa de 3 `b`, o certo é `Dribbble`. O mesmo deve ser tratado para `Github` sem `H` maiusculo e por aí vai.

---

### Estou usando tanto a API como o Client no mesmo repositório, como subo no Heroku?

Para subir somente o backend para o Heroku, basta rodar o comando:

```sh
git subtree push --prefix <pasta-backend> heroku master

# exemplo, se a pasta for /api
git subtree push --prefix api heroku master
```

---

### Meu SVG não está pegando no Cloudinary.

A Cloudinary aparentemente tem alguns problemas em interpretar o SVG se ele estiver sem o cabeçalho completo, basta adicionar a seguinte linha no início do arquivo SVG:

```xml
<?xml version="1.0" encoding="utf-8"?>
```

---

### Cannot find module 'utils/tests/helpers' from 'src/components/Main/test.tsx'

Muito possivelmente o Jest não está reconhecendo o absolute path, basta editar seu `jest.config.js` para ter essa linha:

```js
modulePaths: ['<rootDir>/src/']
```

Verifique sempre o [arquivo original no boilerplate](https://github.com/React-Avancado/boilerplate/blob/master/jest.config.js)

---

### Cannot find module '../build/Release/sharp.node'

Verifique sua versão do Node, se estiver na `14`, é muito possível que esse seja o erro. Tente usar a versão LTS `12.x`, delete o `node_modules` e tente instalar novamente.

---

### Estou recebendo `no-unused-vars` em coisas do TypeScript

Isso é muito possivelmente um conflito das versões do `@typescript-eslint/eslint-plugin`, `@typescript-eslint/parser` e o `typescript`.

Verifique as versões e mantenha sempre na versão major delas, ou seja, `4.x`.

Caso continue dando erro, remova o `node_modules`, reinstale tudo e reinicie o servidor de TypeScript do VS Code.

Para reiniciar o servidor, basta pressionar `ctrl+shift+P` (cmd no Mac) e buscar por `restart TypeScript server`.

---

### toHaveStyle tá dando erro nos testes

Esse é um [bug já reportado](https://github.com/styled-components/styled-components/issues/3262) que veio em algumas otimização da versão `5.2.x`. Para corrigir esse problema, a solução `atual` está sendo mapear no Jest o uso do bundle de browser que o Styled Components cria. Para isso, edite seu arquivo `jest.config.js` para incluir as seguintes linhas:

```js
moduleNameMapper: {
  '^styled-components':
  '<rootDir>/node_modules/styled-components/dist/styled-components.browser.cjs.js'
}
```

Você pode ver o [arquivo completo aqui](https://github.com/React-Avancado/boilerplate/blob/master/jest.config.js)

---

### BABEL ssr is not a valid Plugin property

Provavelmente você não está encapsulando o plugin em um `[ ]` extra. Verifique se a configuração do `.babelrc` [está batendo com o boilerplate](https://github.com/React-Avancado/boilerplate/blob/master/.babelrc).

---

### O termo 'touch' não é reconhecido como nome de cmdlet, função, arquivo de script

O comando `touch` é exclusivo do UNIX e não funciona no Windows puro. Eu recomendo fortemente que você utilize o WSL, [aqui eu ensino como configurar tudo em 30min](https://www.youtube.com/watch?v=YcR8pKvjx44&list=PLlAbYrWSYTiOpefWtd6uvwgKT1R-94Zfd).

---

### System limit for number of file watchers reached, watch

O file watchers são parte do sistema operacional, que vão assistir as mudanças de arquivos e atualizar. Em alguns sistemas, o número de watchers é baixo, basta que você atualize o arquivo de configuração.

No Ubuntu/WSL:

https://dev.to/rubiin/ubuntu-increase-inotify-watcher-file-watch-limit-kf4

---

### Esqueci meu usuário/senha de Admin do Strapi, como faço?

Se você lembrar o email cadastrado, recomendo utilizar a opção "Esqueceu sua senha" e você irá receber na sua caixa de `Spam` uma mensagem para refazer a senha (funciona mesmo localmente!)

Se você não lembrar o email, você pode deletar a tabela `strapi_administrators` e a próxima vez que tenta acessar o sistema, ele vai pedir para criar o usuário.

Para deletar, basta rodar `truncate strapi_administrators;` dentro do Postgres no seu banco.

---

### As fotos dos autores não aparecem na Landing Page

Verifique se na sua API do Strapi, a `photo` está com a opção de `Single Media` definida. Precisa estar conforme [esta linha](https://github.com/React-Avancado/landing-page-api/blob/master/api/author/models/author.settings.json#L13).

---

### Error: Validation error - slug must match the following

Se você estiver populando o nosso banco de dados do Strapi e tiver esse erro, é possível que o slug de algum jogo esteja fora dos padrões que o Strapi definiu. Para normalizar tudo, basta editar para que o método de `slugify` remova qualquer símbolo estranho:

```js
slug: slugify(name, { strict: true, lower: true }),
```

Você pode ver o arquivo inteiro e sua linha modificada, [bem aqui](https://github.com/Won-Games/api/blob/master/api/game/services/game.js#L59)

---

### Qual é o link do Figma da Won Games?

Você pode acessar o link do Figma [aqui](https://www.figma.com/file/8KXr60mZZqL6kqecp1ZeeP/Won-Games-English?node-id=139%3A0). 

Lá você encontrará: 
- Protótipos para Mobile e Desktop
- Styleguide do projeto
- Inspirações usadas para construção
- Branding da Won Games
- Wireframes
- Imagens
- Icones
- Landing Page de venda do curso
