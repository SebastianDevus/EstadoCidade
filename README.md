# EstadoCidade
### Exercício de dev web - Etec Adolpho Berezin - 2022
Faça um formulário contendo um `select` para seleção de estado e um para seleção de cidade.

Estados e cidades, com seus textos e seus `value`s:

- Paraná ("PR")
  - Curitiba (1)
  - Cascavel (2)
  - Maringá (3)
- Santa Catarina ("SC")
  - Florianópolis (4)
  - Blumenau (5)
  - Lages (6)
- Rio Grande do Sul ("RS")
  - Porto Alegre (7)
  - Gramado (8)
  - Caxias do Sul (9)

A cidade deve estar bloqueada (`disabled="disabled"`) até que o estado tenha um valor válido (use o evento `change` para capturar as alterações). Quando o estado estiver selecionado, habilite a seleção das cidades equivalentes.

Quando ambos os valores estiverem selecionados, exiba a cidade e o estado.
