
## Modelo Entidade-Relacionamento: GAMERAL
### Estado atual: Em revisão
**Data**: 25/11/2024

**Descrição**: O modelo entidade-relacionamento do projeto GAMERAL descreve como as entidades (Jogo, Doador, Freelancer, Idealizador) se relacionam e se caracterizam.

**Duvidas**:
1 Ter relação entre? freelancer e idealizador (contrato) ou deixar no constroi?

2 Como funciona a relação/Herança entre jogos e etapadev

**Correções**:

### Observações:
1. Optamos por não criar uma entidade específica para o voluntário, dado que suas características são muito semelhantes às da entidade Freelancer. Em vez disso, incluímos o atributo **profissão**, onde é possível:
   - Indicar "Voluntário".
2. Também tem o atributo **valor**, onde é possível:
   - Definir um valor de pagamento (use $0,00 caso o objetivo seja aprendizado).
3. O Arquivo PNJ está dando problema para converte no BRmodelo
   - Caso de emergencia olhar no arquivo original (nome: ModeloERGameral.brM3)

