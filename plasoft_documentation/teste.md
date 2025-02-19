# Produto

## getTodosProdutos.ts

### method: `GET`

### Body / Query: 
- **ativo**: 
  - `true`: Apenas os produtos ativos.
  - `false`: Apenas os produtos inativos.
  - `todos`: Todos os produtos, ativos e inativos.
### Return:
- **produtos**: Retorna a lista de produto.
- **paginacao**: Retorna o objeto paginacao, sendo que a unica alteração nesse objeto foi o atributo itensTotal
### Lógica: 
- Verifica se isId é true e se textoBusca não é vazio;
- Dependendo da verificação anterior, tem diferentes manipulaçõe das variáveis whereParaProdutos e whereParaQuantidades

#### Links para GitHub:
- [Arquivo no GitHub](https://github.com/seu-usuario/seu-repositorio/blob/main/caminho/para/o/arquivo)
- [Função X](https://github.com/seu-usuario/seu-repositorio/blob/main/caminho/para/o/arquivo#linha-da-funcao)


