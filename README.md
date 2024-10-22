# pi-2024

## explicando: 
No public, tem o html, e nele tem o componente 'app' sendo chamado:
```html
    <div id="app"></div>
```
- esse id='app' chama o app.vue <br>
- a pasta src tem todos os arquivos vue (e a pasta assets, pra colocar imagens) <br>
- cada pagina tem uma pasta própria em src, sendo o seu nome. Vou explicar mais daqui a pouco. Mas prestem atenção no entrar da página! <br>
- 'App.vue' é o pai, e na pasta 'components' voces colocam os componentes filhos e importam no pai <br>
- Caso trocarem o nome de alguma pasta ou arquivo (e der erro) me chamem no zapzap que eu resolvo <br>
- Mexam no src/home/App.vue (ele é a página principal) <br>

## quando for usar pela primeira vez:
```
npm install
```

### Pra fazer rodar o live server:
```
npm run serve
```
isso faz o site se atualizar em tempo real, então é só salvar no vscode que vai diretao no navegador. Ele é um arquivo em lote (que fica rodando em segundo plano), então, pra para ele, usem ctrl c no terminal e digite s.
