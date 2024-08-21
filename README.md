# Descrição
Este script Python recebe até 10 números inteiros fornecidos pelo usuário e realiza diversas operações estatísticas, dividindo os números em dois conjuntos: números pares e números ímpares. Para cada conjunto, ele calcula a soma, média, moda, mediana, variância e coeficiente de variação.

# Pré-requisitos
Para executar este script, você precisará de:

Python 3.x

# Modo de Uso
Clone ou baixe este repositório para o seu ambiente local.
Navegue até o diretório onde o script está localizado.
Execute o script usando o comando:
  python nome_do_arquivo.py

# Funcionamento do Script

O script solicita ao usuário que insira até 10 números inteiros. O usuário pode interromper a entrada de números digitando "parar".
Os números inseridos são divididos em dois conjuntos:
x: números pares
y: números ímpares

O script calcula as seguintes estatísticas para cada conjunto:
Soma: A soma de todos os números no conjunto.
Média: A soma dos elementos dividida pelo número total de elementos.
Moda: O número que aparece com mais frequência no conjunto.
Mediana: O valor central do conjunto ordenado.
Variância: A média dos desvios quadráticos dos números em relação à média do conjunto.
Coeficiente de Variação: A raiz quadrada da variância dividida pela média, expressa em porcentagem.

# Observações
Caso o conjunto de números pares ou ímpares esteja vazio, as estatísticas relacionadas a esse conjunto serão tratadas como zero ou None, conforme apropriado.
