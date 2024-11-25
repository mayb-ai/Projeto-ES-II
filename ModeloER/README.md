
## Modelo Entidade-Relacionamento: GAMERAL
### Estado atual: Em revisão
**Data**: 25/11/2024

**Descrição**: O modelo entidade-relacionamento do projeto GAMERAL descreve como as entidades (Jogo, Doador, Freelancer, Idealizador) se relacionam e se caracterizam.

### Observações:
1. Optamos por não criar uma entidade específica para o voluntário, dado que suas características são muito semelhantes às da entidade Freelancer. Em vez disso, incluímos o atributo **profissão**, onde é possível:
   - Indicar "Voluntário".
2. Também tem o atributo **valor**, onde é possível:
   - Definir um valor de pagamento (use $0,00 caso o objetivo seja aprendizado).
