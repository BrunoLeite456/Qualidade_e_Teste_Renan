# Quais as características de um Tester Ágil? Em quais momentos o Testes Ágil aparece no desenvolvimento de um software?
O Tester Ágil é o profissional que garante a qualidade ao longo de todo o desenvolvimento, especialmente em frameworks como o Scrum, atuando desde a definição dos requisitos até a entrega. Ele trabalha de forma colaborativa, tem visão de negócio e conhecimento técnico, aplica práticas como Test-Driven Development (TDD) e Behavior-Driven Development (bdd practice), e foca na prevenção de defeitos, garantindo que a qualidade seja responsabilidade de todo o time.




# Quando um code reviem faz sentido e quando ele deixa de fazer sentido (no mínimo 3 motivos)? De sua opinião sobre.
**Quando um code review faz sentido**

**Antes de integrar código na branch principal** – Evita que problemas cheguem à produção.
Minha opinião: Esse é o momento mais importante para review. Corrigir antes de integrar é muito mais barato e protege a qualidade do projeto.

**Para compartilhar conhecimento** – Espalha contexto e boas práticas no time.
Minha opinião: Fundamental para evitar “ilhas de conhecimento”. Times que revisam juntos crescem tecnicamente mais rápido.

**Para manter padrões e qualidade** – Garante legibilidade e consistência no código.
Minha opinião: Extremamente válido, mas padrões devem estar bem definidos. Se não houver critérios claros, a review vira opinião pessoal.

**Em mudanças críticas** – Refatorações grandes ou regras de negócio sensíveis.
Minha opinião: Aqui o review deixa de ser opcional e passa a ser estratégico. Quanto maior o risco, maior a necessidade de validação.

**Quando deixa de fazer sentido (ou perde valor)**

**Quando vira burocracia automática** – Aprovação sem análise real.
Minha opinião: Nesse caso é melhor nem fazer. Um “LGTM” sem leitura só cria falsa sensação de segurança.

**Quando o foco é criticar estilo pessoal** – Discussões subjetivas e ego.
Minha opinião: Review não é palco para vaidade técnica. O foco deve ser clareza, performance, segurança e regras do projeto — não gosto pessoal.

**Quando substitui testes automatizados** – Review não detecta tudo.
Minha opinião: Pessoas falham. Testes automatizados são a base; review é complemento. Um não substitui o outro.

**Quando gera gargalo e atrasa entregas** – Dependência de poucos revisores.
Minha opinião: Se o processo trava o fluxo, ele precisa ser ajustado. Qualidade também envolve velocidade sustentável.