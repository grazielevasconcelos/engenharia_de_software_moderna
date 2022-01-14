1. Segundo Frederick Brooks, desenvolvimento de software enfrenta dificuldades essenciais (para as quais não há bala de prata) e acidentais (para as quais existe uma solução melhor). Dê um exemplo de dificuldade acidental que já tenha experimentado ao desenvolver programas, mesmo que pequenos. Sugestão: elas podem estar relacionadas a ferramentas que tenha usado, como compiladores, IDEs, bancos de dados, sistemas operacionais, etc.

- Documentações de API de terceiros que não tinham exemplos na linguagem que estava desenvolvendo e também APIs de terceiros não respeitarem os HTTPs Codes.


2. Diferencie requisitos funcionais de requisitos não-funcionais.
- Funcionais define o que o sistema deve fazer
- Não-funcionais define o comportamento/como o sistema deve comportar-se, exemplo: segurança e disponibilidade.

3. Explique por que testes podem ser considerados tanto uma atividade de verificação como de validação de software. Qual tipo de teste é mais adequado se o objetivo for verificação? Qual tipo de teste é mais adequado se o objetivo for validar um sistema de software?
- Os testes vão executar o que foi solicitado pelo cliente, o que a demanda precisa entregar. E podem também serem executados no momento de aceitação do cliente validando assim se sua necessidade foi atendida.
- Para verificação os testes unitários atendem bem no momento de desenvolvimento.
- Para validação os testes BDD automatizados usando ferramentas como cucumber ou selenium atendem bem para validarem a funcionalidade. (testes de usabilidade / testes de integração)

4. Por que testes não conseguem provar a ausência de bugs?
"Testes de software mostram a presença de bugs, mas não a sua ausência.", Dijkstra
- Acredito que existe um fator tempo pensando em quantidade de tempo para elaborar os fluxos possíveis para cada funcionalidade, nos testes tentamos descrever esses fluxos mas também entregar a funcionalidade. No momento da entrega e com o uso identificamos mais fluxos não antes pensado e consequentemente a identificação de bugs.

5. Suponha um programa que tenha uma única entrada: um inteiro de 64 bits. Em um teste exaustivo, temos que testar esse programa com todos os possíveis inteiros (logo, 264). Se cada teste levar 1 nanossegundo (10-9 segundos), quanto tempo levará esse teste exaustivo?
- 264 entradas diferentes, se houver 1 teste apenas para cada entrada são 264 nanossegundo (44 minutos - 39,6 minutos)

6. Se considerarmos o contexto histórico, por que foi natural que os primeiros processos de desenvolvimento de software tivessem características sequenciais e fossem baseados em planejamento e documentação detalhados?
- Pela características militar dos primeiros projetos onde possuem uma sequência definida e pela construção civil também ter essa característica.

7. Alguns estudos mostram que os custos com manutenção e evolução podem alcançar 80% ou mais dos custos totais alocados a um sistema de software, durante todo o seu ciclo de vida. Explique por que esse valor é tão alto.
- Devido as linhas de códigos já existentes precisarem se adaptar a nova entrega, logo precisamos garantir o que já existe manter-se funcional com a nova demanda e também para atender as atualizações de versão da linguagem, bibliotecas, ajuste de vulnerabilidade encontradas, etc.

8. Refactoring é uma transformação de código que preserva comportamento. Qual o significado da expressão preservar comportamento? Na prática, qual restrição ela impõe a uma operação de refactoring?
- Manter a funcionalidade sem alterar o comportamento, logo todos os testes que existem para ela devem manter a funcionalidade. Seria algo como 'escrever de outra maneira' sem mudar o resultado do método por exemplo.

9.  Dê exemplos de sistemas A (Acute, ou críticos) e B (Business, ou comerciais) com os quais já tenha interagido.
- acute: nunca atuei, mas por exemplo o software para aparelhos hospitalares durante uma cirurgia.
- business: e-commerce, site para empregos.

10. Dê exemplos de sistemas C (casuais) que você já tenha desenvolvido.
- casuais: sistema de agendar quadras esportivas para uma entrega da época de faculdade.

11. Em 2015, descobriu-se que o software instalado em mais de 11 milhões de carros da Volkswagen detectava quando eles estavam sendo testados em um laboratório de certificação. Nessas situações, o carro emitia poluentes dentro das normas legais. Fora do laboratório, emitia-se mais poluentes, para melhorar o desempenho. Ou seja, o código incluía uma estrutura de decisão como a seguinte (meramente ilustrativa, para fins deste exercício):

if "Carro sendo testado em um laboratório"
   "Emita poluentes dentro das normas"
else 
   "Emita poluentes fora das normas"

O que você faria se seu chefe pedisse para escrever um if como o acima? Para mais informações sobre esse episódio, consulte essa página da Wikipedia.

- Eu explicaria que para o cliente e para o meio ambiente não seria benéfico e que para o desenvolvimento iríamos ter até mais esforço para atender cenários distintos.
