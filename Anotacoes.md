# Diretório de pastas do Angular

**e2e** - parte de testes do projeto
**src/app** - lá está a nossa aplicação
**src/app/app-routing.module.ts** - arquivo de rotas da aplicação
**src/app/app.module.ts** - módulo principal da aplicação. Toda aplicação Angular ela está englobada em módulos e cada módulo tem seu componente. Por padrão, tudo no Angular é componente e um componente precisa estar dentro de um módulo.
**environments** - contém as variaveis de ambiente do sistemas
**angular.json** - lá tem todas as configurações nescessárias para a aplicação
**browerlist** - arquivo de testes para navegadores
**app/shared** - pasta que contém todos os componentes que serão compartilhados no sistema

# Templates Angular

Toda vez que eu quiser referênciar uma variavel no template vou utilizar **{{ nome }}**

## Condição
Quando eu precisar de uma condição em alguma tag, eu utilizo o _*ngIf_
Exemplo:

```javascript {.line-numbers}
    <span *ngIf="title === 'n'">{{ title }} app is running!</span>
```

## Repetição
Quando eu precisar de uma repetição de alguma tag, eu utilizo o _*ngFor_
Exemplo:

```javascript {.line-numbers}
    <li *ngFor="let car of cars">{{ car }}</li>
```
