# Controle Financeiro

Aplicação web desenvolvida com **React.js** para controle de finanças pessoais. Permite registrar entradas e saídas financeiras, exibindo um resumo atualizado em tempo real.

## ✨ Funcionalidades

- **Adicionar transações** com descrição, valor e tipo (entrada ou saída)
- **Resumo financeiro** em cards com total de entradas, saídas e saldo
- **Listagem** de todas as transações cadastradas
- **Exclusão** de transações individualmente
- **Persistência de dados** via `localStorage` — os dados são mantidos mesmo ao recarregar a página

## 🛠️ Tecnologias Utilizadas

- [React.js](https://reactjs.org/) — biblioteca de interface
- [styled-components](https://styled-components.com/) — estilização com CSS-in-JS
- [react-icons](https://react-icons.github.io/react-icons/) — ícones

## 📁 Estrutura de Componentes

```
src/
├── App.js                  # Componente raiz: gerencia estado e lógica principal
└── components/
    ├── Header/             # Cabeçalho da aplicação com o título "Controle Financeiro"
    ├── Resume/             # Cards de resumo (Entradas, Saídas e Total)
    ├── Card/               # Card individual de resumo financeiro
    ├── Form/               # Formulário para adicionar novas transações
    ├── Spents/             # Tabela com a listagem de todas as transações
    └── SpentItem/          # Linha individual da tabela de transações
```

## 🚀 Como Executar

### Pré-requisitos

- [Node.js](https://nodejs.org/) instalado

### Instalação e execução

```bash
# Instalar dependências
npm install

# Iniciar em modo de desenvolvimento
npm start
```

A aplicação estará disponível em [http://localhost:3000](http://localhost:3000).

### Outros comandos

| Comando | Descrição |
|---|---|
| `npm test` | Executa os testes |
| `npm run build` | Gera a versão de produção na pasta `build/` |
