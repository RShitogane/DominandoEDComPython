
- `lista_ordenada_encadeada.ipynb` - Contém a implementação da Lista Ordenada Encadeada construída em aula.
  
Mudanças Realizadas:

- Método insert: O método foi modificado para inserir elementos ordenados com base no atributo descricao (a descrição do item). Anteriormente, a ordenação era feita com base no atributo preco. Agora, ao inserir um novo nó, ele é colocado na posição correta da lista de acordo com a ordem alfabética da descricao.
- Método search: O método foi modificado para buscar um elemento com base em descricao. Antes, a busca era feita com base em preco.
- Método remove: O método foi modificado para remover um elemento com base em descricao. Anteriormente, a remoção era feita com base em preco.

Testes Efetuados:

- Inserção de Elementos: Elementos com diferentes descricoes foram inseridos na lista para verificar se eles estavam sendo inseridos na ordem correta de acordo com a ordem alfabética das descrições.
- Busca por Elementos: Realizou-se buscas com base em descrições específicas para garantir que o método search funcionava corretamente.
- Remoção de Elementos: Realizou-se remoções com base em descrições específicas para garantir que o método remove funcionava corretamente e atualizava a lista após a remoção.

Observações sobre os Desafios Encontrados e Implicações da Ordenação por Descrição:

- Comparação de Strings: A comparação de strings em Python pode ser um pouco mais complexa do que a comparação de números, uma vez que strings são comparadas alfabeticamente e podem ter casos especiais (por exemplo, acentuação, maiúsculas e minúsculas).
- Desempenho: A escolha de ordenar por descricao pode afetar o desempenho das operações na lista, pois a comparação de strings pode ser mais lenta do que a comparação de números. Além disso, se a lista for grande, o desempenho das operações de inserção, busca e remoção pode ser afetado pela necessidade de percorrer a lista para encontrar a posição correta para inserção ou remoção com base na descricao.
- Desafios com Dados Heterogêneos: Se houver descrições com acentos ou caracteres especiais, pode haver desafios adicionais na comparação das strings.
