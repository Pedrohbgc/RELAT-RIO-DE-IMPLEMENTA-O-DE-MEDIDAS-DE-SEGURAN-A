# RELAT-RIO-DE-IMPLEMENTA-O-DE-MEDIDAS-DE-SEGURAN-A
RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA ( SEGUNDO RELÁTORIO)
RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: 20/10/2023 Empresa: Abstergo Industries Responsável: Pedro Henrique Barros Gonçalves Camilo

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Henrique Barros Gonçalves Camilo. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: - Amazon VPC (Virtual Private Cloud) - O Amazon VPC permite criar redes virtuais isoladas na AWS, onde você pode lançar recursos da AWS, como instâncias EC2 e bancos de dados RDS. Isso oferece controle total sobre a rede, permitindo que você crie sub-redes públicas e privadas, controle o acesso e configure regras de segurança. - Uso: Configure seu ambiente de produção em uma VPC privada, mantendo seus servidores e bancos de dados internamente inacessíveis a partir da internet. Use grupos de segurança e listas de controle de rede (NACLs) para restringir o tráfego de entrada e saída, garantindo que apenas tráfego autorizado possa acessar seus recursos. 

Medida 2: - AWS Identity and Access Management (IAM) - O AWS IAM permite gerenciar o acesso e as permissões dos usuários e recursos na AWS. Você pode conceder permissões granulares e criar políticas personalizadas para controlar quem pode fazer o quê dentro da sua infraestrutura. - Uso: Atribua funções específicas a equipes ou usuários individuais, garantindo que eles tenham acesso apenas aos recursos necessários para realizar suas tarefas. Isso reduz o risco de acesso não autorizado e ajuda a manter a segurança dos dados.

Medida 3: - Amazon CloudWatch e AWS Config - O Amazon CloudWatch oferece monitoramento e registro de recursos da AWS em tempo real, enquanto o AWS Config registra as configurações dos recursos e as alterações ao longo do tempo. Juntos, eles ajudam a manter o controle sobre as configurações e o desempenho da infraestrutura. - Uso: Configure alertas no CloudWatch para detectar atividades suspeitas ou eventos fora do padrão em sua infraestrutura. O AWS Config permite que você monitore mudanças não autorizadas na configuração de recursos, mantendo um registro histórico para fins de auditoria e conformidade.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado aprimorar a segurança e melhorar a eficiencia operacional, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.
