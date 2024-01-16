# Projeto PizzaShop - Vite

## Iniciando projeto com o Vite

```shell
npm create vite@latest
```

## Instalando o shadcn/ui

```zsh
pnpm add -D tailwindcss postcss autoprefixer

npx tailwindcss init -p
```

## Editar `tsconfig.json`

```js
{
  "compilerOptions": {
    // ...
    "baseUrl": ".",
    "paths": {
      "@/*": [
        "./src/*"
      ]
    }
    // ...
  }
}
```

## Instalando pacote de tipagens

```sh
npm i -D @types/node
```

## Inicializando o shadcn/ui

```sh
pnpm dlx shadcn-ui@latest init
```

## Eslint da rocketseat

```sh
pnpm i eslint @rocketseat/eslint-config -D
```

Ajustar no arquivo `.eslintrc.json`:

```json
{
  "extends": ["@rocketseat/eslint-config/next"]
}
```
