EN-US 

System Design Challenge

*AirBnB*

The Challenge consists of creating a scalable architecture for Airbnb. Airbnb has three main products that support the website's listings:

- Back Office: A web-based tool is required for Airbnb employees to support the product. This platform allows for:
    - User Management
    - Listing Management
    - User Disputes
    - Manual Fraud Analysis
    - Reports

- Advertiser APP: A web-based and mobile tool is required for advertisers on the platform to manage their listings, schedules, and receive payments. This platform should allow for:
    - Listing Management
        - Listing CRUD
        - Listing Photos
        - Listing Schedule
        - Listing Proposals (Users who have proposed to rent the property)
        - Evaluate users who have rented the property
    - Dispute Management (to resolve issues reported by users)
    - Property Management Receivables, receive payments made through the platform for the advertiser
    - Chat with users to discuss potential rentals

- End-user APP: A web and mobile tool is required for platform users to register and rent properties. This platform should allow:
    - List ads by geolocation and user reviews
    - View ads, including their schedules and estimated rates
    - Offer properties based on the schedule and proposal
    - Rent the property and make payments to the platform
    - Evaluate the property
    - Open disputes with owners
    - Chat with the owner to discuss potential rentals

- Since we are dealing with APP users, there should also be a way to notify them, whether by push, email, or SMS

__________________________________________________________________________________________________

PT-BR

Desafio System Design 

*AirBnB*

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


- Como estamos lidando com Usuários APP, tenha também um meio de notifica-lo, seja por push, e-mail ou SMS
