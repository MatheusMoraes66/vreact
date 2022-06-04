# Template React (VReact)

Esse é um template para projetos React usando **Vite**, com uma estrutura já pronta para evoluir o projeto.

### 🧰 Tecnologias & Libs:

| Done      | Tool              | Version    | Link                           |
|-----------|-------------------|------------| ------------------------------ |
| ✔️        | Vite              | 2.9.9      |https://vitejs.dev/
| ✔️        | Jest              | 28.1.0     |https://jestjs.io/
| ✔️        | Storybook         | 6.5.3      |https://storybook.js.org/
| ✔️        | StyledComponents  | 5.3.5      |https://styled-components.com/

Esse projeto tambem usa o Eslint e o Prettier, rode o seguinte comando caso queira indetar o condigo:
`npx eslint ./ --ext "js,jsx" --fix`

Comando para rodar os test:
`npm run test`

### ⚠️ ALERTAS:
 Tive alguns problemas para rodar o storybook nesse projeto, por causa da versão do Node. Para não ter problemas rode a versão lts do Node ou se você tiver uma versão superior use os comandos abaixo.
 
> #### ️ macOS, Linux or Windows Git Bash
`export NODE_OPTIONS=--openssl-legacy-provider`

>#### ️ Windows CMD
`set NODE_OPTIONS=--openssl-legacy-provider`
