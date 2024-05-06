Para o ecommerce utilizamos um WAF (Web Aplication Firewall e um Anti DDOS)
Para garantia de segurança de código utilizamos o Sonarqube e juntamente com o SNYK para verificar as bibliotecas
O Siem é integrados aos 3 servidores e ao ecommerce para gerar logs
O banco de dados é integrado ao SIEM
O Siem é utilizado para gerenciar eventos de segurança da informação
O Siem é integrado ao SOAR
O Soar é integrado também ao XDR
O Soar é utilizado para responder a incidentes de segurança da informação de forma automatizada
O XDR está instalado no Endpoint
O Endpoint possui DLP para prevenir vazamento de dados
O DLP é instalado também nos 3 servidores
É utilizado MFA para acesso aos servidores
Utiliza-se um Firewall NSFW para os servidores (Cloud Pública) além das configurações de segurança em cloud
Para rede local utiliza-se um IPS/IDS (Pode ser o snort)
Implementa-se uma DMZ para segregação de rede para maior segurança
Utiliza-se um firewall para proteção de rede (Pfsense por exemplo)
Para segurança do email utiliza-se DLP, Criptografia TLS, Módulo de integração de segurança do XDR (Se for possível trocar, existem bons fabricantes como Trendmicro que possui essas integrações),SPF,DKIM
O SPF é para configurar um registro SPF no DNS para especificar quais servidores de e-mail podem enviar mensagens em nome do seu domínio.
O DKIM é para assinar digitalmente os e-mails enviados com uma chave privada para permitir que o destinatário valide a autenticidade da mensagem.
Juntamente com toda essa infraestrutura de segurança da informação:
Fazer backups
Implementar segurança física
Treinamento e Conscientização
Análise de Vulnerabilidades
Pentests
SAST/DAST
Gestão de Vulnerabilidades


