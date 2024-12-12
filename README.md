# Benefícios da Nuvem

## SLA - Service Level Agreement
O SLA (**Acordo de Nível de Serviço**) fornece uma tabela que explicita o tempo de inatividade aceitável para os serviços. Caso o recurso contratado tenha um tempo de inatividade excedente, o usuário é ressarcido pela Microsoft por meio de créditos.

---

## Todos os Serviços > Computação

### Máquinas Virtuais
Ao criar uma máquina virtual, o usuário pode personalizá-la de acordo com suas necessidades.  
Por exemplo, nas opções de disponibilidade, o usuário pode escolher uma **zona de disponibilidade**, como demonstrado em aula, para definir onde a máquina virtual será criada.  

Essa configuração ajuda a proteger as máquinas contra interrupções, oferecendo **tolerância a falhas** e garantindo maior disponibilidade dos recursos.  

Cada opção de disponibilidade impacta diretamente no valor do SLA. É necessário consultar a documentação oficial para obter detalhes precisos sobre os valores conforme a opção escolhida.

---

###  Todos os Serviços > Contas de Armazenamento
Nesta seção, é possível utilizar diferentes tipos de redundância, que contribuem para a **disponibilidade do serviço**. Cada tipo de redundância está associado a níveis diferentes de proteção e custos.

Tipos de redundância disponíveis:
- **LRS** - Armazenamento com Redundância Local (Dados replicados dentro de um único datacenter.)
- **GRS** - Armazenamento com Redundância Geográfica (Dados replicados entre regiões diferentes, garantindo maior proteção contra falhas regionais.)
- **ZRS** - Armazenamento com Redundância de Zona  (Dados replicados entre zonas dentro de uma mesma região.)
- **GZRS** - Armazenamento com Redundância de Zona Geográfica (Combina redundância de zona e geográfica para máxima resiliência.)

---
