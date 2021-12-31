# Credit Score de Clientes de Telecomunicações


 Muito se ouve falar sobre modelos preditivos, sobre como a Inteligencia artificial, o aprendizado de maquína (famoso Machine Learning) ajudam as empresas nas tomadas de decisões. Mas será que todo esse esforço é nescessário para resolver todos os problemas? Em muitos casos uma boa análise dos dados é suficiente para direcionar muitas decisões de grande impacto nas empresas, sem gastar os preciosos e caros recursos computacionais processando grandes bases de dados.

Aqui temos exatamente essa proposta, ver o quanto de informações relevantes conseguimos extrair dos dados sem a nescessidade de implementar modelos de Machine Learning.

Vamos partir da situação que recebemos um conjunto de dados de uma empresa de telecomunicações (da qual nada sabemos), e vamos tentar aumentar gerar informações que aumente seus lucros e melhore sua base de clientes rentáveis. E ao longo do processo, vamos tentar responder algumas perguntas SEM o uso de Machine Learning:

   - Quais é o perfil de cliente menos/mais rentável?
   - Quais planos/serviços oferecemos que dão maior retonro?
   - Quais clientes são os mais/menos rentáveis e importantes para empresa?
   - Como podemos auxiliar os setores de vendas/market com esses dados?
   - Somente com a análise dos dados, é possivel a tomada de decisões que tenham impacto na empresa?

As respostas destas perguntas serão respondidas ao longo deste projeto. As conclusões alcançadas se encontram ao final, junto com algumas conclusões sobre o conjunto de dados.

O que será abordado neste projeto?

Vamos fazer uma análise exploratória de um conjunto de dados de uma empresa de telecomunicações a fim de encontrar formas de melhorar o rendimento da empresa sem a nescessidade de implementar Machine Learning, através de insights. Será feita uma breve discussão sobre como os dados analisados podem auxiliar as outras áreas da empresa, algumas particularidades do modelo de negócio da empresa e com o axílio de gráficos, vamos tornar visual algumas informações.

---

# Conclusões

Através da analise dos dados foram identificados um perfil inicial dos clientes, a maioria deles não é idoso não possui dependentes, metade possui um parceiro e o sexo estão balanceados entre homens e mulheres. Essas informações podem ser relevantes para o oferecimento de produdos ou contas com multiplos usuários (caso de serviços de streaming).

Foi possível notar também que o serviço essencial da empresa é a prestação de serviço de internet e telefonia, mas que também são oferecidos serviços adicionais que dependem dos essenciais.

Com a análise da base de dados, foi possível chegar ao objetivo de categorização entre 'normal' e 'premium' de quase 69% dos nossos clientes sem aplicação de um único algoritimo de Machine Leaning. Isso traz muitos beneficios para empresa, entre eles:

    Redução de custos computacionais locais e/ou em nuvem;
    Redução do tempo de processamento dos dados, uma vez que não demanda um pré-processamento nem o treinamento dos algorítimos ou predições feitas por eles(como no caso do KNN que é uma etapa bem demorada);
    Explicabilidade do processo, onde todas as etapas podem ser constatadas e vizualmente explicadas;
    Direcionabilidade dos resultados para cada setor, onde o setor de vendas, por exemplo, pode se interessar por aqueles clientes que tem maiores propensões a adquirir pacotes que ainda não tenham (clientes premium tem essa tendencia), ou o setor de cobranças que podem se interessar pelas formas de pagamento dos clientes.
