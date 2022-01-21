# Requisitos
## Exercícios de Fixação 🔗

1. [POSCOMP 2010, adaptado] Sobre Engenharia de Requisitos, marque Verdadeiro (V) ou Falso (F).

(V) A Engenharia de Requisitos, como todas as outras atividades de Engenharia de Software, precisa ser adaptada às necessidades do processo, do projeto, do produto e do pessoal que está fazendo o trabalho.

(V) No estágio de levantamento e análise dos requisitos, os membros da equipe técnica de desenvolvimento do software trabalham com o cliente e os usuários finais do sistema para descobrir mais informações sobre o domínio da aplicação, que serviços o sistema deve oferecer, o desempenho exigido do sistema, as restrições de hardware, dentre outras informações.

(F) Na medida em que a informação de vários pontos de vista é coletada, os requisitos emergentes são consistentes.

(V) A validação de requisitos se ocupa de mostrar que estes realmente definem o sistema que o cliente deseja. Ela é importante porque a ocorrência de erros em um documento de requisitos pode levar a grandes custos relacionados ao retrabalho.

2. Cite o nome de pelo menos cinco técnicas para elicitação de requisitos.
histórias do usuário
   - casos de uso
   - diagrama de caso de uso
   - Design Sprint
   - Testes A/B
   - Protótipos

3. Quais são as três partes de uma história de usuário? Responda usando o acrônimo 3C's.
   - Cartão + Conversas + Confirmação

4. Suponha uma rede social como o Facebook. (1) Escreva um conjunto de cinco histórias para essa rede, assumindo o papel de um usuário típico; (2) Pense agora em mais um papel de usuário e escreva pelo menos duas histórias para ele.
    - Como um pessoa usuária da rede, eu gostaria de compartilhar posts
    - Como um pessoa usuária da rede, eu gostaria de iniciar conversas para apenas uma pessoa da minha rede
    - Como um pessoa usuária da rede, eu gostaria de curtir posts
    - Como um pessoa usuária da rede, eu gostaria de publicar stories
    - Como um pessoa usuária da rede, eu gostaria de ler o meu feed na home

---

    - Como um pessoa gestora da rede, eu gostaria de remover posts de fake news
    - Como um pessoa gestora da rede, eu gostaria de bloquear contas de usuários iligítimos.

5. Em Engenharia de Software, anti-patterns são soluções não recomendadas para um certo problema. Escreva pelo menos cinco anti-patterns para histórias de usuários. Em outras palavras, descreva formatos de histórias que não são recomendados ou que não possuem propriedades recomendáveis.

    - Como um pessoa usuária da rede, eu gostaria de compartilhar posts rapidamente
    - Como um pessoa usuária da rede, eu gostaria de ler o meu feed de forma clara
    - Como um pessoa usuária da rede, eu gostaria de curtir posts com o botão de joinha ou coração ou estrela
    - Como um pessoa usuária da rede, eu gostaria de remover a minha conta de forma segura
    - Como um pessoa usuária da rede, eu gostaria de não visualizar nenhum post ofensivo


6. Pense em um sistema e escreva uma história épica para o mesmo.
    - Como CEO de rede social, eu gostaria de ter métricas de visualizações de das contas registradas categorizadas por localização, faixa etária e dispositivo.

7. No contexto de requisitos, o que significa a expressão gold plating?
    - Designa a situação na qual os desenvolvedores decidem, por conta própria, sofisticar a implementação de algumas histórias — ou requisitos, de forma mais genérica —, sem que isso tenha sido pedido pelos clientes. 

8. Escreva um caso de uso para um Sistema de Controle de Bibliotecas (similar ao que usamos para ilustrar a escrita de histórias na Seção 3.3.1).


    Como usuário típico, eu gostaria de pagar as multas dos livros atrasados


9. O seguinte caso de uso possui apenas o fluxo normal. Escreva então algumas extensões para ele.

>     Comprar Livro
>     Ator: Usuário da loja virtual
>     Fluxo normal:
>         Usuário pesquisa catálogo de livros
>
>         Usuário seleciona livros e coloca no carrinho de compra
> 
>         Usuário decide fechar a compra
> 
>         Usuário seleciona endereço de entrega
> 
>         Usuário seleciona tipo de entrega
> 
>         Usuário seleciona modo de pagamento
> 
>         Usuário confirma pedido

Extensões: Usuário seleciona endereço de entrega
>         Usuário seleciona endereço de entrega
>         Usuário informa endereço de entrega padrão

>         Usuário seleciona endereço de entrega
>         Usuário informa endereço personalizado para entrega corrente


10. Para cada técnica de especificação e/ou validação de requisitos a seguir, descreva um sistema no qual o seu uso seria mais recomendado: (1) Histórias de Usuários; (2) Casos de Uso; (3) MVPs.
    - (1) Histórias de Usuários; Site para críticas de filme, review do filme.
    - (2) Casos de Uso; Sistema portuário informar o recibo da carga contratada.
    - (3) MVPs.: Criação de novo produto. Por exemplo: Contas compartilhadas em serviço de música


11. Qual a diferença entre um Produto Mínimo Viável (MVP) e o produto obtido na primeira iteração de um método ágil, como XP ou Scrum?

    - O MVP busca validar uma hipótese, então a entrega pode ser falha e busca-se a agilidade na entrega em detrimento a qualidade.
    - As demais iterações dos métodos são realizados em produtos já validados.


12. O artigo Failures to be celebrated: an analysis of major pivots of software startups [link](https://arxiv.org/abs/1710.04037) apresenta uma discussão sobre quase 50 casos reais de pivôs em startups da área de software. Na Seção 2.3, o artigo apresenta uma classificação de dez tipos de pivô comuns nessas startups. Leia essa parte do artigo, liste pelo menos cinco tipos de pivôs e faça uma breve descrição de cada um deles.

    - Customer Segment Pivot: Mudança dentro de um mesmo contexto porém para um outro segmento de cliente.
    - Customer Need Pivot: Mudança de contexto dado o conhecimento das necessidades do cliente.
    - Platform Pivot: Mudança de negócio para virar a própria plataforma que hospeda.
    - Engine of Growth Pivot: Mudança de precificação ou planos para atingir o engajamento adequado.
    - Technology Pivot: Mudança ou expansão de plataformar tecnológica para interesses do negócio, adesão dos clientes a alguma certa plataforma tecnológica.


13. Quando começou, a EasyTaxi — a empresa brasileira de aplicativos para solicitação de táxis — construiu um MVP que usava um software muito simples e uma parte operacional realizada de forma manual. Pesquise na Internet sobre esse MVP (basta usar as palavras EasyTaxi e MVP) e faça uma descrição do mesmo.

    A equipe de fundadores disponibilizava uma página web para que usuários entrassem manualmente o endereço onde estavam - e um Submit gerava um e-mail para os sócios. Estes, assim que recebiam uma mensagem, ligavam eles mesmos para as cooperativas pedindo um táxi para o endereço.
[Detalhes](https://www.infoq.com/br/articles/mvp-easy-taxi/)

14. Suponha que estamos em 2008, quando ainda não existia Spotify, e você decidiu criar uma startup para oferecer um serviço de streaming de músicas na Internet. Então, como primeiro passo, você implementou um MVP.

    Quais seriam as principais funcionalidades desse MVP?
        Tocar música e Pesquisar música
    Ele seria desenvolvido para qual hardware e sistema operacional?
        Para dispositivos móveis, de preferência para ambas plataformas ou que fosse possível reproduzir em ambas.
    Elabore um rascunho rápido da sua interface com o usuário.
        - Pesquisar música
        - Listado (música) com player para reproduzir
    Quais métricas você usaria para medir o sucesso/fracasso do MVP?
        - Downloads
        - Quantidades de reproduções de músicas.

15. Suponha que você seja responsável por um sistema de comércio eletrônico. Suponha que na versão atual desse sistema (versão A) a mensagem do carrinho de compra seja "Adicionar ao Carrinho". Suponha que você pretenda fazer um teste A/B testando a mensagem alternativa "Compre Já", a qual vai corresponder à versão B do teste.

    Qual seria a métrica usada como taxa de conversão nesse teste?

    Supondo que no sistema original a taxa de conversão seja de 5% e que você deseja avaliar um ganho de 1% com a mensagem da versão B, qual seria o tamanho da amostra que deveria testar em cada uma das versões? Para responder, use uma calculadora de tamanho de amostras de testes A/B, como aquela que citamos na Seção 3.6.

        - Tamanho da amostra por variação: 4.700.000
[Detalhes](https://www.optimizely.com/sample-size-calculator/?conversion=5&effect=1&significance=95)