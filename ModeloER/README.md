
## Modelo Entidade-Relacionamento: GAMERAL
### Estado atual: Em revisão
**Data**: 25/11/2024

**Descrição**: O modelo entidade-relacionamento do projeto GAMERAL descreve como as entidades (Jogo, Doador, Freelancer, Idealizador) se relacionam e se caracterizam.

**Duvidas**:
1 Carnalidade correta?
2 Como posso inserir o Administrador (Ele supervisiona todo o sistema para banir conteudos improprios ou pessoas com comportamentos inadequados), considerando que ele não interage de forma tão incisiva com as entidades principais para ser colocado diretamente no modelo?"

**Correções**:

### Observações:
1. Optamos por não criar uma entidade específica para o voluntário, dado que suas características são muito semelhantes às da entidade Freelancer. Em vez disso, incluímos o atributo **profissão**, onde é possível:
   - Indicar "Voluntário".
2. Também tem o atributo **valor**, onde é possível:
   - Definir um valor de pagamento (use $0,00 caso o objetivo seja aprendizado).

