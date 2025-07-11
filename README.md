Desafio System Design 

*** AirBnB *** 

O Desafio consiste em criar uma arquitetura escalavel para o AirBnB, o AirBnB possui três principais produtos os quais servem para dar sustentação para os anúncios do site: 

- Back-Office: é necessário uma ferramenta WEB para que os funcionários do airbnb consigam sustentar o produto, nessa plataforma é possível: 
    - Gestão de Usuários
    - Gestão de Anúncios
    - Constestação de Usuários
    - Analíses manuais de Fraude 
    - Relatórios

- APP Anunciante: é necessário uma ferramenta WEB e Mobile para que os anunciantes da plataforma consigam fazer a gestão de seus anúncios, agendas e receber pagamentos, nessa plataforma deve ser possível:
    - Gestão de anúncios
        - CRUD do anúncio
        - fotos do anúncio 
        - Agenda do anúncio
        - Propostas do anúncio (Usuários que propuseram locar o imovel)
        - avaliar os usuários que locaram o imóvel 
    - Gestão de contestação (para resolver problemas relatados pelo usuário)
    - Gestão de recebíveis, receber pagamentos feitos pela plataforma para o anunciante 
    - Chat com usuário para discutir sobre a possível locação

- APP Usuário final: é necessário uma ferramenta WEB e Mobile para que os usuários da plataforma consigam se cadastrar e fazer locação de imovéis, nessa plataforma deve ser possível: 
    - Listagem de anúncios por geolocalização, e avaliações de usuários 
    - Vizualizar anúncios tal como suas agendas e tarifas estimadas
    - Propor locar imóveis dada agenda e proposta (Offer)
    - Locar o imóvel de fato e realizar pagamentos à plataforma
    - Avaliar o imóvel
    - Abrir contestações com proprietários 
    - Chat com proprietário para discutir sobre a possível locação
