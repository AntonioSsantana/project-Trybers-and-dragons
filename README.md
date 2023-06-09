# Trybers and Dragons

Este é um projeto de jogos de interpretação de papéis (RPG) chamado "Trybers and Dragons". O objetivo deste projeto é aplicar os princípios da arquitetura SOLID e os princípios de Programação Orientada a Objetos (POO) em uma estrutura de jogo RPG.

## Dependências

O projeto utiliza as seguintes dependências:

- "express": "4.17.1"
- "express-async-errors": "3.1.1"

```json
"dependencies": {
    "express": "4.17.1",
    "express-async-errors": "3.1.1"
  }
``` 

## Dependências de Desenvolvimento

- "@jest/test-sequencer": "27.4.6"
- "@types/express": "4.17.13"
- "@types/jest": "27.0.2"
- "@types/node": "16.11.7"
- "@typescript-eslint/eslint-plugin": "5.3.1"
- "@typescript-eslint/parser": "5.3.1"
- "eslint": "7.32.0"
- "eslint-config-airbnb-base": "15.0.0"
- "eslint-config-airbnb-typescript": "15.0.0"
- "eslint-plugin-editorconfig": "3.2.0"
- "eslint-plugin-import": "2.25.3"
- "eslint-plugin-mocha": "9.0.0"
- "eslint-plugin-sonarjs": "0.10.0"
- "jest": "27.3.1"
- "nodemon": "2.0.14"
- "ts-jest": "27.0.7"
- "ts-node-dev": "1.1.8"
- "typescript": "4.4.3"

```json
"devDependencies": {
    "@jest/test-sequencer": "27.4.6",
    "@types/express": "4.17.13",
    "@types/jest": "27.0.2",
    "@types/node": "16.11.7",
    "@typescript-eslint/eslint-plugin": "5.3.1",
    "@typescript-eslint/parser": "5.3.1",
    "eslint": "7.32.0",
    "eslint-config-airbnb-base": "15.0.0",
    "eslint-config-airbnb-typescript": "15.0.0",
    "eslint-plugin-editorconfig": "3.2.0",
    "eslint-plugin-import": "2.25.3",
    "eslint-plugin-mocha": "9.0.0",
    "eslint-plugin-sonarjs": "0.10.0",
    "jest": "27.3.1",
    "nodemon": "2.0.14",
    "ts-jest": "27.0.7",
    "ts-node-dev": "1.1.8",
    "typescript": "4.4.3"
  }
```

## Scripts

O projeto possui os seguintes scripts:

- `start`: Inicia o projeto utilizando o `ts-node`.
- `dev`: Inicia o projeto em modo de desenvolvimento utilizando o `nodemon` e o `ts-node`.
- `test`: Executa os testes utilizando o Jest.
- `fasttest`: Executa os testes de forma rápida, interrompendo no primeiro erro utilizando o Jest.
- `lint`: Executa a verificação de linting utilizando o ESLint.

```json
  "scripts": {
    "start": "ts-node src/index.ts",
    "dev": "nodemon --watch \"./src/**\" --ext \"ts,js\" --ignore \"src/**/*.spec.ts,src/**/*.json\" --exec \"ts-node src/index.ts\"",
    "test": "jest --runInBand --verbose",
    "fasttest": "jest --runInBand --verbose --bail",
    "lint": "eslint . --ext .js,.jsx,.ts,.tsx"
  }
```

## Como Utilizar

1. Clone o repositório em sua máquina local.
2. Instale as dependências do projeto utilizando o comando `npm install`.
3. Execute o projeto utilizando o comando `npm start` ou `npm run dev`.
4. Execute os testes utilizando o comando `npm test` ou `npm run fasttest`.
5. Verifique o linting do código utilizando o comando `npm run lint`.