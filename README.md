 # Simulador de Tabela de Descontos 

Este projeto é uma tabela interativa desenvolvida em JavaScript que permite aplicar descontos em tempo real a uma lista de serviços. É ideal para simulações rápidas e demonstrar como os preços são ajustados com base em diferentes percentuais de desconto.

## Recursos

- **Calculo em Tempo Real**: Ao inserir um valor de desconto no campo fornecido (entre 1% e 100%), a tabela é atualizada dinamicamente.
- **Proteção contra erros**: O valor com desconto nunca será negativo.
- **Interatividade**: O desconto é aplicado assim que o usuário digita, sem a necessidade de recarregar a página.

## Pré-visualização

A tabela é composta por:

- **Coluna "Tipo de Serviço"**: Lista os serviços simulados.
- **Coluna "Valor/Hora"**: Exibe os valores originais.
- **Coluna "Com Desconto Aplicado"**: Mostra os valores ajustados após o desconto.

Exemplo inicial:

| Tipo de Serviço | Valor/Hora | Com Desconto Aplicado |
|------------------|------------|-----------------------|
| Freelance        | R$ 200,00 | R$ 160,00            |
| Design           | R$ 300,00 | R$ 240,00            |

## Como usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/simulador-tabela-descontos.git
   ```
2. Abra o arquivo `index.html` no navegador.
3. Insira um valor de desconto no campo para ver a tabela atualizada em tempo real.

## Código

O projeto é construído em **JavaScript puro**, sem dependências externas. Todo o código está encapsulado para facilitar sua reutilização.

## Personalização

- Você pode alterar os dados da tabela editando o array `dados` no código-fonte. 
- Para mudar o desconto padrão, ajuste o valor inicial do campo `<input>` no atributo `value`.

## Contribuições

Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias.

---

Se precisar de ajustes ou algo mais detalhado, é só avisar! 😊
