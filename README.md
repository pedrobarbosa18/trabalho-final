1. Compreendendo o Problema e o Contexto:
• Enchentes no Rio Grande do Sul:
o Impacto: Familiarize-se com a magnitude das enchentes, as áreas afetadas, o número de pessoas
desabrigadas e as necessidades imediatas das vítimas.
o Recursos Existentes: Pesquise sobre as ações já em andamento por governos, ONGs e outras entidades para
auxiliar as vítimas.
o Lacunas e Oportunidades: Identifique as lacunas existentes na assistência às vítimas e as oportunidades que
o sistema de doações pode oferecer para complementar os esforços já realizados.
• Público-alvo:
o Doadores: Compreenda as motivações dos doadores para contribuir com as vítimas, os diferentes tipos de
doações que podem ser feitas e os canais de comunicação mais eficazes para alcançá-los.
o Vítimas das Enchentes: Identifique as necessidades específicas das vítimas, como alimentos, roupas, abrigo,
medicamentos e apoio psicológico.
2. Definindo as Funcionalidades Essenciais do Sistema:
2.1 Recebimento de Doações:
• Tipo de Doação:
o Menu ou Formulário: Crie um menu intuitivo ou formulário online para que os doadores selecionem o tipo
de doação que desejam fazer (dinheiro, alimentos, roupas, itens de higiene pessoal, medicamentos, etc.).
o Opção "Outro": Inclua a opção "Outro" para permitir que os doadores especifiquem doações que não se
encaixam nas categorias pré-definidas.
• Quantidade:
o Campos de Entrada: Implemente campos de entrada para que os doadores informem a quantidade de cada
item doado (ex: número de peças de roupa, quantidade de alimentos em kg, valor monetário da doação em
dinheiro).
o Validação de Dados: Aplique regras de validação para garantir que os dados inseridos sejam válidos e
consistentes (ex: quantidade maior que zero, valor monetário positivo).
• Data da Doação:
o Registro Automático: Utilize a data e hora do sistema para registrar automaticamente a data da doação.
o Opção de Seleção: Permita que o doador selecione a data da doação caso seja diferente da data atual
(doações retroativas).
2.2 Cálculo do Total de Doações:
• Função de Cálculo: Crie uma função que some os valores das doações em dinheiro e converta as doações em itens para
um valor monetário equivalente.
o Utilização de Preços Referenciais: Utilize preços referenciais de mercado para converter as doações em
itens para valores monetários.
o Atualização de Preços: Implemente um mecanismo para atualizar os preços referenciais periodicamente,
garantindo a precisão dos cálculos.
• Apresentação do Total:
o Interface Clara: Exiba o total de doações em uma interface clara e amigável, utilizando recursos visuais
como gráficos e tabelas para facilitar a visualização.
o Desglosamento por Tipo: Apresente o total de doações por tipo de doação (dinheiro, alimentos, roupas, etc.),
permitindo uma análise mais detalhada da arrecadação.
2.3 Armazenamento de Informações de Doações:
• Escolha do Armazenamento: Decida se as informações de doações serão armazenadas em um banco de dados
(MySQL, PostgreSQL, etc.) ou em arquivos texto (CSV, JSON).
o Banco de Dados:
▪ Vantagens: Estrutura robusta, segurança de dados, consultas complexas, escalabilidade.
▪ Desvantagens: Maior curva de aprendizado, necessidade de administração do banco de dados.
o Arquivos Texto:
▪ Vantagens: Simplicidade, fácil acesso e manipulação, não requer instalação de software adicional.
▪ Desvantagens: Limitações para consultas complexas, menor segurança de dados, escalabilidade
limitada.
• Segurança e Integridade: Implemente medidas de segurança para proteger as informações dos doadores, como
criptografia de dados e controle de acesso.
 • Criptografia: Utilize técnicas de criptografia para proteger os dados armazenados contra acessos não
 • Tipo de doação: Permitir a seleção de diferentes tipos de doações (dinheiro, alimentos, roupas, etc.).
 • Quantidade: Campos para inserir a quantidade de cada item doado.
 • Dados do doador: Coleta de informações básicas do doador (nome, contato, endereço).
 • Opção de doação anônima: Permitir que o doador faça a doação anonimamente
 • Agradecimento: Enviar um e-mail de agradecimento ao doador após a doação.
Requisitos Funcionais
Completude:
o Porcentagem de Funcionalidades Documentadas: Meça a porcentagem de funcionalidades que foram
documentadas de forma clara e concisa.
▪ Objetivo: Essa métrica garante que todos os requisitos funcionais estejam bem definidos e
compreendidos pelas partes envolvidas no projeto.
▪ Cálculo: Divida o número de funcionalidades documentadas pelo número total de funcionalidades
estimadas e multiplique por 100%.
o Análise de Cobertura de Requisitos: Utilize ferramentas como o Volere Requirements Management ou o
Doors NextGen para analisar a cobertura dos requisitos funcionais nos documentos de especificação.
▪ Objetivo: Essa métrica garante que cada requisito funcional esteja claramente mapeado para um
elemento do sistema, como uma funcionalidade, um caso de uso ou uma regra de negócio.
▪ Interpretação: Uma alta taxa de cobertura de requisitos indica que a maioria dos requisitos está
bem documentada e relacionada a elementos específicos do sistema.
• Clareza:
o Nível de Ambiguidade: Avalie a clareza e precisão da linguagem utilizada na documentação dos requisitos
funcionais.
▪ Objetivo: Essa métrica garante que os requisitos sejam compreensíveis para todos os envolvidos
no projeto, evitando interpretações errôneas e conflitos.
▪ Análise: Utilize ferramentas como o Clarity ou o Linguix para identificar frases ambíguas,
complexas ou com termos técnicos que podem gerar dúvidas.
▪ Exemplo: Evite frases como "O sistema deve ser amigável" e substitua por definições mais
objetivas, como "O sistema deve permitir que usuários realizem tarefas de forma intuitiva e com
um tempo mínimo de aprendizado".
• Priorização:
o Matriz de Priorização: Utilize uma matriz como a de MoSCoW ou Eisenhower para classificar os
requisitos funcionais de acordo com sua importância e urgência.
▪ Objetivo: Essa métrica garante que os requisitos mais importantes para o sucesso do projeto sejam
implementados nas primeiras etapas do desenvolvimento.
▪ Definição das Categorias:
▪ Must Have (Imprescindível): Requisitos essenciais para o funcionamento básico do
sistema.
▪ Should Have (Importante): Requisitos que agregam valor ao sistema, mas não são
críticos para sua operação.
▪ Could Have (Desejável): Requisitos que aprimoram a experiência do usuário, mas
podem ser adiados ou implementados em fases posteriores.
▪ Wont Have (Não Terá): Requisitos que foram considerados fora do escopo do projeto
ou desnecessários para o seu sucesso.
• Validação:
o Revisões por Stakeholders: Realize revisões dos requisitos funcionais com stakeholders como usuários,
doadores, representantes de ONGs e especialistas em gestão de desastres.
▪ Objetivo: Essa métrica garante que os requisitos estejam alinhados com as expectativas e
necessidades de todas as partes envolvidas no projeto.
▪ Coleta de Feedback: Utilize questionários, entrevistas ou workshops para coletar feedback dos
stakeholders sobre os requisitos.
▪ Análise do Feedback: Analise o feedback recebido e identifique pontos de aprimoramento nos
requisitos, como a necessidade de maior clareza, priorização ou completude.
2. Métricas para a Fase de Implementação:
• Completude:
o Porcentagem de Funcionalidades Implementadas: Meça a porcentagem de funcionalidades documentadas
que foram implementadas no sistema.
▪ Objetivo: Essa métrica indica o quão abrangente o sistema é em relação às suas funcionalidades
inicialmente planejadas.
Cálculo: Divida o número de funcionalidades implementadas pelo número total de
funcionalidades documentadas e multiplique por 100%.
Crítica á IA
 1. Riscos à Autonomia e à Privacidade:
• Coleta e Uso de Dados: A IA se alimenta de vastas quantidades de dados, muitas vezes coletados de forma passiva ou
sem o consentimento explícito dos indivíduos. Essa prática levanta preocupações sobre a privacidade e o controle que as
pessoas têm sobre seus dados pessoais.
• Algoritmos Biased: Algoritmos de IA podem perpetuar e amplificar vieses existentes na sociedade, discriminando
grupos minoritários ou tomando decisões injustas com base em dados tendenciosos.
• Vigilância e Controle Social: A IA pode ser utilizada para fins de vigilância em massa, controle social e repressão,
limitando a liberdade de expressão e o direito à privacidade.
2. Impactos no Mercado de Trabalho:
• Automação de Tarefas: A automação de tarefas repetitivas por máquinas movidas a IA pode levar à perda de empregos
em diversos setores, especialmente aqueles que exigem mão de obra manual ou atividades rotineiras.
• Desigualdade Social: A disrupção do mercado de trabalho pela IA pode aprofundar as desigualdades sociais, se não
forem implementadas políticas públicas que redistribuam os benefícios da tecnologia e preparem os trabalhadores para as
novas demandas do mercado.
• Alterações nas Habilidades Necessárias: O mercado de trabalho exigirá cada vez mais habilidades relacionadas à
tecnologia, criatividade, inteligência emocional e adaptabilidade, exigindo dos trabalhadores uma constante atualização e
requalificação profissional.
3. Preocupações Éticas e Filosóficas:
• Consciência Artificial: A possibilidade de criar máquinas com consciência artificial levanta questões éticas sobre seus
direitos, autonomia e impacto na sociedade.
• Tomada de Decisões Autônomas: Sistemas de IA que tomam decisões autônomas, especialmente em áreas como saúde,
justiça criminal ou guerra, podem gerar dilemas éticos e responsabilidades incertas em caso de falhas ou erros.
• Desumanização e Alienação: O uso excessivo de IA pode levar à desumanização de processos e à alienação das
pessoas, diminuindo a empatia, a criatividade e o senso crítico.
4. Desafios para o Desenvolvimento Responsável da IA:
• Falta de Transparência: A "caixa preta" de muitos algoritmos de IA dificulta a compreensão de como as decisões são
tomadas, limitando a capacidade de questioná-las e responsabilizar os desenvolvedores por seus impactos.
• Regulamentação Ineficaz: A rápida evolução da IA exige marcos regulatórios ágeis e eficazes que garantam o
desenvolvimento e o uso responsável da tecnologia, protegendo os direitos individuais e o bem-estar social.
• Falta de Diversidade: A falta de representatividade de grupos minoritários no desenvolvimento de sistemas de IA pode
perpetuar vieses e discriminações, reforçando desigualdades existentes na sociedade.
Lembre-se:
• A IA é uma ferramenta poderosa com o potencial de gerar grandes benefícios para a sociedade, mas deve ser utilizada de
forma responsável, ética e consciente dos riscos potenciais.
• É fundamental promover debates públicos sobre o desenvolvimento e o uso da IA, envolvendo diversos setores da
sociedade, desde cientistas e tecnólogos até especialistas em ética, direito e representantes da sociedade civil.
• O desenvolvimento de mecanismos de governança e regulamentação eficazes é crucial para garantir que a IA seja
utilizada de forma responsável, transparente e justa, beneficiando toda a sociedade.
Para se aprofundar no tema, recomendo a leitura de:
• Livro: "O Futuro da Humanidade" - Yuval Noah Harari
• Artigo: "A ética da inteligência artificial" - John Danaher
• Site: "The Ethics of Artificial Intelligence" - The Markkula Center for Applied Ethics
