# Reclame-Aqui
Juntamente com um colega de trabalho, fiz um Webscraping do Reclame Aqui das principais concorrentes da empresa em que trabalho, no intuito de identificar os principais motivos pelos quais elas recebem reclamações e trabalhar nossos processos internos para evitar receber as mesmas reclamações e manter nossa boa reputação na plataforma.

O que motivou meu projeto de Webscraping foi que eu percebi que o conteúdo das reclamações não eram 100% compatíveis com as classificações que estavam sendo usadas, o que afetava os dados disponibilizados pelo Reclame Aqui. Por exemplo, cheguei a ver diversas reclamações onde a Tag era "Cobrança Indevida", no entanto, a pessoa estava reclamando sobre a dificuldade no processo de cancelamento.

Após identificar esse GAP e perceber que os dados disponibilizados não me ajudariam da forma que eu queria, resolvi fazer o Webscraping com Python e montar minha própria base de dados, contendo: empresa, reclamação, Tag, localização do reclamante, status, nota da avaliação, resposta do cliente após o atendimento.

Em seguida, utilizei Python para reclassificar as reclamações e montei um dashboard no Power BI para fazer análise das informações.

Como conclusão, percebemos que os principais motivos das reclamações eram falta/demora no atendimento e sobre o processo de cancelamento. Estamos tomando diversa medidas internamento para melhorar nosso processos e evitar recber reclamações desse mesmo tipo.

Por fim, com o intuíto de praticar um pouco mais dos meus conhecimentos de Python, também utilei a base de dados para:
- Identificar palavras chaves mais mencionadas;
- Analisar a tendência temporal das reclamções de uma das concorrentes.
