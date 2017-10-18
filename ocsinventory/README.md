Membros:
- Felipe Lima
- Rayson Vinicius

Descrição do Projeto:
- Monitorar os ativos na rede, a fim de gerenciar os softwares instalados na máquina, sistema operacional, processos e afins.

Interface com o usuário:
- Arquivo disponível no repositório.

Casos de uso:
- Verificar Alteração
- Inventariar Máquinas
- Analisar Dados

Análise crítica das tecnologias a serem empregadas:
- Open Audit ou OCS Inventory.
    Open Audit:  Software de inventário de ativos, porém licenciado, limitando as funcionalidades de acordo com a licença, inviabilizando o desenvolvimento do projeto.
    OCS Inventory:  Software de inventário de ativos, gratuito, contendo duas instâncias (servidor e agente).
    
    Parecer:  De acordo com o exposto acima, optamos pelo OCS Inventory pois é um software gratuito, repleto de plugins para complementação e com inúmeras possibilidades de complementações, possibilitando melhor proveito da ferramenta.
    
Itens de gerência:
  - Gerência de Contabilização
  - Gerência de Desempenho
  
Limiar:
    Se uma máquina sem comunicação com o servidor a mais de 30 dias.

Gatilho:
    Enviar e-mail para Gerente de TI, Administrador de Rede e Gerente de Suporte.
    Excluir a máquina da listagem de inventário.

Ação:
    Abrir um chamado para o Suporte de Hardware verificar se está máquina ainda está na rede da empresa. 
