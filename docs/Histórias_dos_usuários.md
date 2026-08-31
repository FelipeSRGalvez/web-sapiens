# Entrevistas — Levantamento de Requisitos (Conecta+)

Registro de campo das entrevistas realizadas com microempreendedores para levantamento de necessidades, referente aos módulos Estoque, Mercado e Agenda.

---

## Entrevista 1 — Estoque

**Entrevistado:** Marcos R., 34 anos
**Negócio:** Loja de variedades e presentes (comércio de pequeno porte)

> "Hoje eu controlo meu estoque num caderno mesmo. Quando chega mercadoria eu anoto, quando vendo eu tento lembrar de descontar, mas nem sempre dá tempo, principalmente quando tá cheio de cliente. Já aconteceu de eu vender uma coisa que na verdade já tinha acabado, porque eu não tinha atualizado o caderno. E outra: às vezes eu só percebo que um produto tá acabando quando o cliente pergunta e eu vou lá no estoque físico olhar. Eu queria saber quando um produto tá ficando baixo antes de faltar de vez, sem precisar ficar contando toda hora. E também não tenho como saber depois quanto eu perdi de mercadoria estragada ou quebrada no mês, porque isso também só fica anotado meio solto."

**Necessidades identificadas no relato:**
- Registro de entrada e saída de itens de estoque, com data da movimentação.
- Registro de perdas/descarte separado da venda normal, com motivo.
- Aviso quando a quantidade de um item estiver baixa, antes de esgotar.
- Possibilidade de consultar o histórico de movimentações de um item específico.
- Facilidade para localizar um item entre vários (por nome, categoria ou situação de estoque).

**Requisitos relacionados:** RF24, RF27, RF28, RF29, RF30

---

## Entrevista 2 — Mercado / Vitrine e Pedidos

**Entrevistada:** Juliana S., 29 anos
**Negócio:** Confeitaria artesanal, vendas por encomenda

> "Meus pedidos hoje chegam tudo pelo WhatsApp. Cliente manda mensagem perguntando o preço, eu respondo, às vezes demoro porque tô ocupada fazendo encomenda de outro cliente. Aí quando eu volto pro celular já tem cinco mensagens novas e eu não sei mais qual pedido é de quem nem em que pé cada um tá. Teve vez de eu esquecer de avisar um cliente que o bolo dele já ficou pronto. Eu queria que o cliente conseguisse ver o que eu tenho pra vender sem precisar me perguntar toda hora, tipo um cardápio que ele mesmo acessa, e que ele pudesse fazer o pedido ali, só passando nome e telefone dele, sem precisar criar login nem nada disso, porque cliente não gosta de complicação. E eu queria também conseguir ver rapidinho quando chega um pedido novo, e ir marcando o andamento dele — recebido, fazendo, pronto — pra não me perder no meio de vários pedidos ao mesmo tempo."

**Necessidades identificadas no relato:**
- Vitrine pública dos produtos, acessível pelo cliente sem necessidade de login.
- Registro de pedido pelo cliente informando apenas nome e telefone.
- Notificação para o negócio quando um novo pedido é registrado.
- Acompanhamento do andamento de cada pedido por meio de um status.

**Requisitos relacionados:** RF16, RF18, RF19, RF20

---

## Entrevista 3 — Agenda

**Entrevistado:** Guilherme Torres, 28 anos
**Negócio:** Barbearia, atendimento individual com hora marcada

> "Eu marco os horários dos clientes numa agendinha de papel mesmo, ou às vezes só de cabeça. O problema é que de vez em quando dois clientes acabam vindo no mesmo horário porque eu esqueci que já tinha marcado alguém ali, ou porque um marcou por telefone e outro apareceu direto na loja. Também já aconteceu de eu esquecer de avisar um cliente que precisei remarcar o horário dele, e ele chegou aqui achando que ia ser atendido. Eu queria que o cliente pudesse ver os horários que eu tenho livre e já marcar direto, sem precisar ficar me ligando pra perguntar, e que ele fosse avisado automaticamente se o horário dele for confirmado, remarcado ou cancelado. E pra mim, seria bom conseguir ver de forma organizada, por dia ou por semana, quem eu já tenho marcado, pra não ter mais esse problema de horário batendo um com o outro."

**Necessidades identificadas no relato:**
- Consulta pública dos horários disponíveis para agendamento.
- Solicitação de agendamento pelo cliente, informando nome e telefone.
- Impedimento de dois agendamentos confirmados no mesmo horário.
- Aviso ao cliente quando o status do agendamento mudar (confirmado, remarcado ou cancelado).
- Visualização organizada da agenda por dia e por semana.

**Requisitos relacionados:** RF33, RF34, RF35, RF36, RF38

---

## Observações sobre cobertura

Estas 3 entrevistas cobrem os módulos Mercado, Estoque e Agenda sob a perspectiva do Gerente/dono do negócio. Ficaram fora desta rodada: Autenticação e Conta (RF01–RF07), Gestão de Funcionários e Permissões (RF08–RF13) e Relatórios (RF40–RF43), que podem ser objeto de entrevistas complementares.
