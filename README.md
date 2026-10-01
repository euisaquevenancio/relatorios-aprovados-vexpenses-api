# Automação Relatórios Aprovados Vexpenses (API) 🔑✈️✅

Automação destinada para a captura de relatórios aprovados no Vexpenses das mantenedoras **ABEC**, **SOME**, **UBEE** e **UNBEC**, desenvolvida com Node.js. A coleta é feita através da API oficial, garantindo uma extração mais rápida das informações necessárias.

O processo inicia com a validação do token e acesso a API do Vexpenses, seguido da coleta do **Número do relatório**, **Total**, **Nome do Solicitante**, **Tipo** (reembolso, adiantamento ou prestação de contas), **Data de Aprovação Gestor**, **Data de Vencimento** e **Centro de Custos**. Registros já processados são desconsiderados com base no arquivo `relatoriosIgnorados.txt`.

Por fim, todos os relatóriso processados são consolidados em uma **planilha**, que é gerada e aberta automaticamente ao final da execução.

## Variáveis de ambiente

Para executar este projeto é necessário adicionar a seguinte variável no seu arquivo `.env`, referentes ao consumo da API:

`TOKEN_VEXPENSES`.

## Execução

Para executar a automação, é necessário instalar todos os arquivos presentes neste repositório. Após isso, abra o editor de código (ou similar) na pasta do projeto, certifique-se de ter o Node.js instalado e execute o seguinte comando no terminal para instalar as dependências:

```bash
    npm install
```

Após a instalação, execute o comando abaixo no terminal para iniciar a automação:

```bash
    npm run relatoriosAprovadosVexpensesAPI.js
```

## Autores

- *[@euisaquevenancio](https://euisaquevenancio.github.io/portfolio/) - 27/09/2026*

