## Fundamentos de computação em nuvem

A computação em nuvem nada mais é que uma oferta de serviço de computação sob demanda e por meio da internet com pagamento baseado em uso. Com isso vem algumas facilidades e desafios, por conta que você consegue acessar qualquer dados em qualquer lugar, por outro lado a segurança bate na porta, então deve ter os seus cuidados.

*O uso do termo “nuvem” tem sua origem nos diagramas das antigas redes de dados ISDN (Services Digital Network ou rede de serviços digitais) e Frame Relay, projetadas pelas operadoras de telefonia.*

#### Vantagens

- Só paga pelo o que usa;
- Flexibilidade, agilidade e escalabilidade;

#### Desvantagens

- Necessidade de internet, então necessário uma internet confiável e boa;
- Os dados podem sofrer ataques;

#### Provedores

Empresa contratada para disponilizar uma infraestrutura, exemplo: Amazon Web Services AWS (Líder de mercado), Google Cloud Platform, Microsoft Azure, IBM Cloud, Oracle Cloud...

#### Linha do tempo

O sua surgimento está atrelado ao susrgimento da internet. 

Arpanet foi a primeira rede que permitiu o compartilhamento de informações entre computadores que não estavam no mesmo espaco físico.

Nos anos 2000 o cloud computing ficou mais comum no mundo da tecnologia, e daí então foi o começo da AWS onde começou a disponibilizar recursos para empresas e usuários alugarem uma parte de sua infraestrutura.

Em 2007 a Netflix lança o seu stream de vídeo onde os usuário poderiam assistir os vídeos de qualquer lugar do mundo.

A virtualização é um conceito que descreve a utilização de mais de um sistema operacional em um único servidor, simulando a estrutura de vários servidores físicos.

A computação em nuvem depende da virtualização de servidores, essa técnica é a essência do funcionamento da cloud computing.


### Modelos de computação em nuvem

#### Essência da computação em nuvem

-> Cinco características essênciais:
  - Autoatendimento sob demanda

  Acesso direto e sob demanda, garantindo que a alocação e a liberação de recursos ocorram sem a necessidade de interação humana entre o usuário e o provedor.

  - Amplo acesso à rede

  Capacidade da infraestrutura de rede de se conectar a uma ampla variedade de dispositivos, como telefones celulares, laptops, estações de trabalho e tablets, para permitir acesso contínuo aos recursos de computação nessas diversas plataformas.

  - Agrupamento de recursos

  Os recursos de computação do provedor são agrupados para atender a vários consumidores usando um modelo multilocatário, ou seja, os recursos computacionais são compartilhados entre diversos usuários, os quais não precisam ter conhecimento acerca da localização dos recursos que estão utilizando. Esses recursos computacionais devem ser abstraídos por dispositivos físicos reais, o que é alcançado na maioria das vezes por meio de virtualização.

  - Elasticidade dinâmica

  Capacidade de ampliar e reduzir conforme necessário, seja automática ou manualmente, sem a necessidade de lead times. Dessa maneira, a rápida alocação e liberação de recursos da nuvem a qualquer momento e conforme a demanda da aplicação proporciona ao usuário a não preocupação com a quantidade de recurso a que tem direito e tenha a sensação de capacidade de armazenamento infinita, podendo a qualquer momento requisitar recursos.

  - Serviço mensurável

  A capacidade de medir exatamente quais recursos estão sendo usados, monitorar e controlar esses serviços para podermos posteriormente apresentar esses dados ao cliente ou ao usuário final, por exemplo. O conceito de serviço mensurável contribuiu para o surgimento do modelo pay-as-you-go.

-> Três modelos de serviço:
  - Infraestrutura como um Serviço - (IaaS)
  - Plataforma como um Serviço (PaaS)
  - Software como um Serviço (SaaS)

-> Quatro modelos de implantação
  - Nuvem privada
  - Nuvem comunitária
  - Nuvem pública
  - Nuvem híbrida

### Camadas e atores na computação em nuvem

  - A camada de infraestrutura é a camada mais baixa. Nessa camada, os provedores de infraestrutura disponibilizam os serviços de armazenamento e rede. Nela encontram-se os servidores, os sistemas de armazenamento e os roteadores.

  - A camada de plataforma está relacionada com os serviços de aplicações que podem ser utilizadas para desenvolver, testar e implementar aplicações na nuvem.

  -A camada de aplicação fornece o maior nível de abstração, oferecendo diversas aplicações como serviços para serem consumidos pelos usuários.


  Visualizando:

  -> Aplicação:
    - Aplicações como serviços
    - Usuários de serviços

  -> Plataforma:
    - Desenvolvimento de aplicações
    - Prestadores de serviços

  -> Infraestrutura:
    - Serviços de rede e armazenamento
    - Prestadores de infraestrutura

  Os três principais atores da computação em nuvem são: os provedores de serviço, os usuários da nuvem e os provedores de infraestrutura.
 

#### Modelos de serviços para computação em nuvem

São três principais modelos de serviço de computação em nuvem

-> Infraestrutura como Serviço (IaaS)
  É um modelo de serviço de nuvem que permite ao usuário utilizar recursos de infraestrutura sob demanda, como armazenamento, virtualização e rede. Nesse cenário, os serviços de virtualização e rede são fornecidos pelo provedor enquanto o usuário cuida do sistema operacional, dos aplicativos e dados. Exemplos desse tipo de serviço incluem o serviço de máquinas virtuais do Azure e da AWS.

-> Plataforma como Serviço (PaaS)
  É um tipo de modelo de serviço de computação em nuvem que oferece uma plataforma de nuvem flexível e escalonável para desenvolver, implantar, executar e gerenciar apps. Nesse cenário, o usuário tem todas as ferramentas necessárias para criar aplicativos, as necessidades de software, hardware, rede e sistemas operacionais são atendidas pelo provedor de serviços. Exemplo desse tipo de serviço é o Google App Engine.

-> Software como Serviço (SaaS)
  É um modelo que permite aos usuários se conectar e usar aplicativos baseados em nuvem pela internet, como e-mail, serviços de armazenamento, entre outros. Nesse cenário, as necessidades de computação e armazenamento são atendidas pelo provedor de serviços em nuvem, o usuário só precisa fazer upload e baixar dados. Manutenção, tempo de inatividade, atualização e segurança são atendidos pelo provedor de serviços. Exemplos desse tipo de serviço são o Dropbox, Google APPS, Pipedrive e Shopify.


![alt text](./imagems/image.png)

**Em resumo:**

- IaaS – Requer o máximo de gerenciamento do usuário entre os serviços da nuvem.
- PaaS – Requer menos gerenciamento do usuário.
- SaaS – Requer o mínimo de gerenciamento do usuário.


#### Nuvens públicas e privadas

-> Public Cloud - nuvem pública
  As nuvens públicas são aquelas nas quais os provedores de serviços disponibilizam todos os recursos, como computação, armazenamento e aplicativos para o público em geral pela internet. Qualquer usuário pode efetuar login e usar esses serviços. Você paga pelo número de recursos que usa. Nesse modelo, os usuários possuem menos controle sobre seus dados.

  -> Vantagens:
    - Preço;
    - Facilidade de contratação, configuração e infraestrutura;
    - Escalabilidade;
    - Performance;

  -> Desvantagens:
   - Segurança;
   - Controle feito por terceiros;
   - Requisitos legais;


-> Private Cloud – nuvem privada
  As nuvens privadas são ambientes de nuvem construídos exclusivamente para um único usuário, ou uma única empresa, normalmente localizados por trás do firewall do usuário.

  Ela oferece todos os benefícios da nuvem pública, como flexibilidade, escalabilidade, provisionamento, automação, monitoramento, entre outros, com a diferença de não ser dividida com outras empresas.

  Normalmente, esse tipo de nuvem é usado por organizações com foco na segurança de dados e que gerenciam dados muito sensíveis, como transações financeiras, por exemplo. Ela também pode ser empregada por empresas que possuem controle interno bem rígido.

  -> Vantagens:
    - Disponibilidade;
    - Customização de infraestrutura;
    - Suporte exclusivo;
    - Segurança;

  -> Desvantagens:
    - Custo inicial e a necessidade de uma equipe de TI própria.
    - O custo inicial é elevado, pois será necessário a compra do hardware, instalação e configuração. - E a contratação de profissionais de TI, pois são necessárias habilidades de TI pelo usuário ou empresa.

#### Nuvens híbridas e outros tipos

-> Hybrid cloud – nuvem híbrida
  As nuvens híbridas são aquelas constituídas pelos serviços da nuvem pública e privada. Alguns serviços são hospedados na nuvem privada, enquanto outros na nuvem pública. Assim, a empresa pode manter dados cruciais na nuvem privada e outros dados na nuvem pública, aproveitando o melhor dos dois mundos.

-> Community Cloud – nuvem comunitária
  As nuvens comunitárias são compartilhadas por diversas empresas que possuem interesses comuns, como a missão, os requisitos de segurança, políticas, entre outros. Nesse modelo, a nuvem comunitária pode ser administrada tanto pela própria organização ou por terceiros e pode existir tanto dentro (on premises) quanto fora (off premises) da organização.

-> Distributed Cloud – nuvem distribuída
  A nuvem distribuída se caracteriza pela possibilidade de ser acionada em diferentes localidades, mas possui servidores conectados a uma única rede ou hub de serviços. Optando por essa solução, a empresa garante o máximo de disponibilidade de seus recursos, além de uma baixa latência.

#### Conteinerização
  A conteinerização, também conhecida como virtualização baseada em contêineres, é um método utilizado na implantação e execução de aplicativos distribuídos sem a necessidade de configuração de uma virtual machine (VM) completa para cada um deles. Em vez disso, vários sistemas isolados, chamados de contêineres, são executados em um único host de controle, acessando um único kernel. E assim, surge o conceito de cloud containers ou contêineres na nuvem, isto é, virtualização baseada em contêiner, um modelo de virtualização na nuvem em nível de sistema operacional, com o objetivo de implantar e executar aplicativos distribuídos. Dessa forma, vários sistemas isolados são acionados em um único host, acessando um único kernel.

## Ambiente de Computação em Nuvem - Azure

#### Comparação de modelos de nuvem

1. Nuvem Privada
  - O hardware deve ser comprado para inicialização e manutenção;
  - As organizações têm controle total sobre os recursos e a segurança;
  - As organizações são responsáveis pela manutenção e pelas atualizações;

2. Nuvem Pública
  - Nenhuma despesa de capital para escalar verticalmente;
  - Os aplicativos podem ser provisionados e desprovisionados;
  - As organizações pagam apenas pelo que utilizam;

3. Nuvem Híbrida
  - Fornece a maior flexibilidade;
  - As organizações determinam onde executar seus aplicativos;
  - As organizações controlam a segurança, a conformidade ou requisitos legais;


#### A arquitetura e os serviços do Azure

As regiões do Azure são áreas geográficas do planeta que possuem ao menos um datacenter, e, possivelmente, vários outros próximos, o que proporciona redes de baixa latência conectada por redes de fibra ótica. Cada região garante a residência dos dados. Portanto, se uma máquina virtual for criada na região Sul do Brasil, por exemplo, a Microsoft garante que os dados estão localizados no Brasil. O Azure garante que as cargas de trabalho sejam balanceadas corretamente dentro das regiões disponibilizadas.

As zonas de disponibilidade são datacenters dentro da mesma região que são sepaarados fisicamente, mas conectados a uma rede de alta velocidade. Cada zona possui uma ou mais datacenters, geralmente até três com energia, refrigeração e rede independentes. Uma zona é um limite de isolamento de forma que, caso uma zona fique indisponível, as outras continuam funcionando.

Já os pares de regiões é o emparelhamento de regiões proporcionando a redução da possibilidade de interrupções devido a desastres naturais, quedas de energia, conflitos civis e interrupções de rede física na região específica. A maioria das regiões possui o seu par na mesma geografia, ou a pelo menos 300 milhas, ou 480km. laguns serviços do Azure já possuem, habilitados por padrão, essa configuração de regiões pares, possibilitando que, em caso de algum dos desastres citado, ocorra a migração do serviço para a região par.