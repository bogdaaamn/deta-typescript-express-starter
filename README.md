# Deta Typescript Express Starer

This is a starer template for a Deta project using Node, Express and Typescript.

## Uses

- Node 14.x (as Deta Micros use Node 14.x)
- Express 4.18.1
- Typescript 4.8.3

## Structure

- `src/`: the typescript source files
- `dist/`: the compiled js files
- `index.js`: imports the compiled `index.js` and exports the app for Deta

## Development

Install dependencies.

```
yarn
```

Run `ts-node src/index.ts` and watch all the typescript files inside `src/`.

```
yarn dev
```

## Deployment

Compile the source files. Deploy `index.js` pointing at `dist/index.js` and the other compiled files in `dist/`

```
yarn deploy
```
