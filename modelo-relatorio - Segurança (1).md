# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 23/09/2024
Empresa: Abstergo Industries 
Responsável: Fernando Lucius

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Fernando Lucius. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1:  Configuração de Multi-Factor Authentication (MFA) no AWS IAM
- Caso de uso: Garantir que os usuários que acessam a AWS façam uso de autenticação em dois fatores (MFA) para evitar acessos não autorizados.
- Implementação: Foi habilitada a MFA para todas as contas de usuário e raiz do AWS IAM. Usuários agora devem fornecer um token gerado por um dispositivo secundário para acessar seus recursos.
- Resultado esperado: Aumenta a segurança de acesso ao sistema, minimizando riscos de acesso indevido mesmo que as credenciais de um usuário sejam comprometidas. 

Medida 2: Criação de políticas de segurança baseadas em função (IAM Roles)
- Caso de uso: Restringir acessos a recursos específicos, concedendo permissões apenas conforme o necessário para realizar determinadas funções (princípio do menor privilégio).
- Implementação: Foram criadas novas IAM Roles com permissões personalizadas para diferentes grupos de usuários, limitando suas ações no ambiente da AWS, conforme as necessidades de cada função.
- Resultado esperado: Melhora na governança de acesso, reduzindo o risco de acesso indevido a recursos sensíveis ou críticos.

Medida 3: Implementação do AWS CloudTrail para auditoria de logs
- Caso de uso: Monitorar e registrar todas as atividades dentro da infraestrutura AWS para auditoria e detecção de atividades suspeitas.
- Implementação: O AWS CloudTrail foi configurado para capturar logs de todas as ações realizadas no ambiente da AWS, como criação de instâncias, alterações em permissões, ou acessos não autorizados.
- Resultado esperado: Aumento da visibilidade sobre as ações realizadas na infraestrutura, permitindo uma auditoria eficiente e a detecção rápida de possíveis incidentes de segurança.

## Conclusão
A implementação das medidas de segurança na Abstergo Industries resultou em melhorias significativas na segurança do ambiente AWS, reduzindo os riscos de ataques externos e de acessos não autorizados. Espera-se que essas ferramentas aumentem a eficiência e a segurança dos processos internos da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas soluções de segurança para aprimorar ainda mais o ambiente tecnológico da empresa.
## Anexos

Documentação de configuração MFA
Políticas IAM criadas
Relatório de auditoria do AWS CloudTrail

Assinatura do Responsável pelo Projeto:

Fernando Lucius