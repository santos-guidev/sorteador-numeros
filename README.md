# Jogo de Sorteio

Este é um simples jogo de sorteio de números, onde o usuário pode especificar a quantidade de números a serem sorteados, o intervalo de números e visualizar os resultados.

## Funcionalidades

- Sorteio de números únicos dentro de um intervalo especificado.
- Interface intuitiva para entrada de dados e exibição de resultados.
- Botão de reiniciar para limpar os campos e recomeçar o sorteio.

## Estrutura do Código

### Funções

1. **sortear()**
   - Realiza o sorteio dos números com base na quantidade e intervalo especificados pelo usuário.
   - Atualiza a interface com os números sorteados.
   - Chama a função `alterarStatusBotao()` para atualizar o estado do botão de reiniciar.

2. **obterNumeroAleatorio(min, max)**
   - Gera um número aleatório entre o valor mínimo e máximo fornecidos.

3. **alterarStatusBotao()**
   - Alterna o estado do botão de reiniciar entre habilitado e desabilitado.

4. **reiniciar()**
   - Limpa os campos de entrada e o resultado, permitindo ao usuário realizar um novo sorteio.
   - Chama a função `alterarStatusBotao()` para atualizar o estado do botão de reiniciar.
