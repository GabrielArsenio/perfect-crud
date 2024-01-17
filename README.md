# perfect-crud

Check-list com itens que EU considero importantes em um CRUD

## Frontend

### Listagem

- [ ] Paginação
  - [ ] Botões de primeira, última, anterior e próxima página
  - [ ] 5 botões com os números da página: 1 atual, 2 próximas e 2 anteriores
  - [ ] Dropdown com número de registros por página (25, 50, 100)
  - [ ] Salvar na URL o número da página e o número de registros e utilizá-los quando recarregar a página (?page=3&limit=25)
- [ ] Filtros
  - [ ] Salvar na URL o termo filtrado e utilizá-lo quando recarregar a página (`?q=termo+da+busca` para um campo genérico e `?campo1=termo1&campo2=termo2` para campos específicos)
- [ ] Ordenação
  - [ ] Permitir ordenar por TODAS as colunas da lista, mesmo em listas genéricas onde se pode adicionar mais colunas
  - [ ] A ordenação de cada coluna deve conter 3 estados: ASC, DESC e desativada
  - [ ] A ordenação de uma coluna não deve desativar a ordenação de outra
  - [ ] Salvar na URL a ordenação de cada campo e utilizar quando recarregar a página. Repetir o parâmetro em forma de array quando houver mais de um campo (`?order=nome,ASC` ou `?order[]=nome,ASC&order[]=id,DESC`)
