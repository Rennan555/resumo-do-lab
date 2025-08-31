# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Benefícios da Nuvem

### SLA (Service Level Agreement)

Refere-se a um contrato realizado entre provedor de serviço e cliente que detalha expectativas, responsabilidades e padrões de desempenho,
incluindo métricas de tempo de atividade, tempo de resposta e tempo de resolução de problemas.

Tempo de inatividade por semana por porcentagem de **SLA**:
<ol>
  <li>
    99%: 1,68h
  </li>
  <li>
    99,9%: 10,1min
  </li>
  <li>
    99,95%: 5min
  </li>
  <li>
    99,99%: 1,01min
  </li>
  <li>
    99,999%: 6s
  </li>
</ol>

### Escalabilidade e Elasticidade
<ol>
  <li>
    Escalabilidade é a capacidade de ajustar para atender à demanda, isso é, mais recurso pode ser alocado para lidar com o aumento da demanda.
    Com escala vertical, uma aplicação receberia mais capacidade de processamento, escalando verticalmente para adicionar mais RAM ou CPU à máquina virtual.
  </li>
  <li>
    Elasticidade se refere à capacidade de alocação de recursos em aplicações onde houveram saltos repentinos de demandas, manual ou automaticamente.
    Possibilita também a redução de recursos implementados horizontalmente em caso de queda significativa de demanda. 
    Disponével, por exemplo, para máquinas virtuais e contêiners.
  </li>
</ol>

### Confiabilidade, Previsibilidade e Segurança
<ol>
  <li>
    Confiabilidade é a capacidade da Nuvem de reagir e responder à falhas, mesmo com alterações ou erros de infraestrutura, e garantir integridade de dados.
    Ocorre devido ao design descentralizado da Nuvem, permitindo implantação de recursos em várias regiões do mundo.
    Assim, mesmo com falhas na infraestrutura de toda uma região, as outras regiões continuam operando normalmente, em escala global.
  </li>
  <li>
    Previsibilidade é a confiança no desempenho ou custo para uma determinada aplicação, permitindo planejamento para sua implementação.
  </li>
  <li>
    A Segurança na Nuvem é feita por meio de ferramentas disponibilizadas pela própria Nuvem, os quais devem ser aplicadas pelo própio cliente.
    PaaS e SaaS são as melhores alternativas para aplicação de patches e manutenção automáticas.
  </li>
</ol>

### Governança e Gerenciabilidade
<ol>
  <li>
    Governança é o gerenciamento e identificação de riscos que podem ser tolerados pelo organização.
    Recursos fora de conformidade dos padrões corporativos, e formas de mitigação, podem der sinalizados por meio de auditorias.
    Dependendo do modelo operacional, patches de software e atualizações podem ser aplicados automaticamente.
  </li>
  <li>
    Gerenciabilidade diz respeito ao gerenciamento de recursos da Nuvem.
    Pode ser implementado a partir de modelo pré-configurado, ser precisar ser configurado manualmente.
    Disponével por mediante APIs e PowerShell. 
  </li>
</ol>

### Criação de Máquina Virtual e Conta de Armazenamento

Detalhamento da Instância:
<img width="1919" height="835" alt="Detalhamento da Instância" src="https://github.com/user-attachments/assets/2cd79954-edeb-4dd8-af37-33137a42dd1c" />

Conta de Armazenamento:
<img width="1919" height="850" alt="Conta de Armazenamento" src="https://github.com/user-attachments/assets/aaaa9324-c926-47c6-bb3d-df5174d83258" />

## Tipos de Serviço de Nuvem

### IasS, PaaS e SaaS
<ol>
  <li>
    IaaS (Infraestrutura como Serviço): detém servidores de armazenamento, firewalls de rede e planta física do datacenter.
    Provê mais liberdade para personalização.
  </li>
  <li>
    PaaS (Plataforma como Serviço): Possui, também, sistema operacional e ferramentas para desenvolvimento, análise de negócios e gerenciamento de database.
  </li>
  <li>
    SaaS (Software como Serviço): Possui, além de tudo, aplicativos/programas de hospedagem. Usuários se conectam com base na Nuvem pela internet.
  </li>
</ol>

### Modelo de Responsabilidade Compartilhada

No datacenter físico (ambiente *on-premisses*), o cliente é responsável por todas as responsabilidades do sistema. A partir do uso dos modelos de Nuvem, as responsabilidades começam a ser compartilhadas.

No IaaS, apenas datacenter físico, rede e hosts físicos são disponibilizados. Hardware configurados e gerenciados.
No PaaS, sistema operacional é responsabiliadede da Nuvem, além de controle de rede, aplicativos e infraestrutura de identidade e diretório serem compartilhados com o cliente. Focado em desenvolvimento de apps.
No SaaS, controle de rede e aplicativos passam a serem responsabilidade da Nuvem, com infraestrutura de identidade e diretório continuando compartilhado. Modelo *Pay as you go*.

Independente do modelo selecionado, contas e identidades, dispositivos utilizados e informações/dados sempre serão responsabilidade do cliente.

## Sistema Operacional

Tipo de Imagem da VM:
<img width="1919" height="852" alt="Tipo de Imagem da VM" src="https://github.com/user-attachments/assets/7c35cd19-3555-4866-b511-3ab360c586a2" />

Configuração de Disco:
<img width="1919" height="842" alt="Configuração de Disco" src="https://github.com/user-attachments/assets/16b3d1e4-08bc-48cd-9b57-38929dca7d55" />

Configuração de Rede:
<img width="1919" height="845" alt="Configuração de Rede" src="https://github.com/user-attachments/assets/585d10bc-4e1e-44fc-a470-5e5cb5a32763" />

Configuração de Gerenciamento:
<img width="1919" height="848" alt="Configuração de Gerenciamento" src="https://github.com/user-attachments/assets/7bcf6758-0da2-493d-bb71-4e1a0768492d" />

Configuração de Monitoramento:
<img width="1919" height="843" alt="Configuração de Monitoramento" src="https://github.com/user-attachments/assets/c2d270f1-f97b-4686-b794-73838b1873ca" />

Criação de BD em SQL:
<img width="1919" height="849" alt="Criação de BD em SQL" src="https://github.com/user-attachments/assets/61c88a9e-c9a3-4b77-98c9-3b6b45f1aa88" />
