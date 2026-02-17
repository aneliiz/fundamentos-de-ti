## **Ambientes de Software: Desenvolvimento, Homologação e Produção**

Em projetos profissionais, o sistema não vai direto para o usuário final. Ele passa por ambientes separados, cada um com um objetivo específico para garantir qualidade, segurança e estabilidade.

*Os três principais são:*

* Ambiente de Desenvolvimento (Dev)
* Ambiente de Homologação (Staging)
* Ambiente de Produção (Prod)


### *1. Ambiente de Desenvolvimento (Dev)*

É o ambiente onde o software é criado e modificado pelos desenvolvedores.
Ele pode rodar tanto na máquina local do dev, em um servidor interno ou em um ambiente compartilhado na nuvem.


*Objetivo:*

* Desenvolver novas funcionalidades
* Corrigir bugs
* Testar implementações iniciais
* Integrar código com outros módulos

*Características:*

* Ambiente mais instável
* Atualizações frequentes
* Pode conter dados fictícios
* Pode quebrar com facilidade

<u>Aqui erros são esperados. É onde o código nasce.</u>


##



### *2. Ambiente de Homologação (Staging)*

É o ambiente que simula a Produção. Aqui o sistema já passou pelo desenvolvimento e testes internos e está pronto para validação final.
Também chamado de Staging ou UAT (User Acceptance Testing).

*Objetivo:*

* Validar regras de negócio
* Confirmar que os requisitos foram atendidos
* Aprovação do cliente ou área de negócio

*Características:*

* Muito parecido com Produção
* Pode usar dados quase reais
* Última etapa antes da liberação oficial

<u>Se algo der errado aqui, ainda dá tempo de corrigir antes do usuário final ser impactado.</u>


##


### *3. Ambiente de Produção (Prod)*

É o ambiente oficial onde o sistema está disponível para os usuários reais. Tudo que acontece aqui impacta diretamente clientes e negócios.


*Objetivo:*

* Disponibilizar o sistema ao público
* Garantir estabilidade e performance
* Proteger dados reais

*Características:*

* Dados reais
* Monitoramento constante
* Controle rigoroso de mudanças
* Deploy planejado

<u>Erros em Produção podem gerar prejuízo financeiro e impacto na reputação da empresa.</u>


##


## **Como funciona o fluxo entre os ambientes**

1️. Dev cria funcionalidade

2️. Código é testado em Desenvolvimento

3️. Vai para Homologação

4️. Cliente/negócio valida

5️. Aprovado → Deploy em Produção



### *3. Diferença entre ambientes:*

| Ambiente         | Quem usa                     | Tipo de dados         | Objetivo Principal                         |
|------------------|----------------------------- |---------------------- |------------------------------------------------------------------------- |
| Desenvolvimento  | Desenvolvedores             | Fictício ou teste      | Criar e modificar funcionalidades          |
| Homologação      | QA / Cliente / Negócio      | Próximo do real        | Validar requisitos antes da liberação      |
| Produção         | Usuários finais             | Dados reais           |  Uso oficial do sistema                     |
