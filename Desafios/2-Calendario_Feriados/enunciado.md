# 📅 Desafio 2: Feriados Nacionais (BrasilAPI)

A BrasilAPI é um projeto de código aberto que fornece dados úteis. Vamos construir uma tabela dinâmica que lista todos os feriados nacionais de um determinado ano.

**A sua missão:**
1. Crie uma estrutura de tabela (`<table>`) utilizando o Bootstrap, mas deixe o corpo da tabela (`<tbody>`) vazio.
2. Assim que a página for carregada, faça um `fetch` para: `https://brasilapi.com.br/api/feriados/v1/2024`
3. A API vai devolver um Array de Objetos. Cada objeto representa um feriado.
4. Utilize um laço de repetição (`forEach` ou `map`) para percorrer os feriados.
5. Para cada feriado, crie uma linha na tabela (`<tr>`) mostrando a data e o nome do feriado.