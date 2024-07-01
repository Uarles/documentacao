# Trabalho Segurança da Informação

Esta documentação refere-se ao trabalho desenvolvido na máteria de Segurança da Informação, ministrada pelo professor [**Pedro Rafante**](https://github.com/pedrorafante), do curso técnico de Desenvolvimento de Sistemas, pela **Proz Educação - sede Divinópolis/MG**

## Criação do site de portifólio profissional do Rinaldo



<details>
<summary>Imagens</summary>
<br>
Imagens dropdown.
<br><br>
<pre>
 
![Pagina Inicial!](/Captura%20de%20tela%202024-07-01%20194418.png "Home")

![Outra Imagem!](/6.png "Home")
</pre>
</details>


Visite o site: www.rinaldovieira.com.br

Documentação do Projeto de Criação de um Site no WordPress
Equipe:
 
Rinaldo Vieira,
Klinger Guedes,
Miguel Muniz,
Uarles Lemes,
Daniela Aparecida,
Lucas Teixeira,
Clério Chagas.
 
Escolha do projeto:
Foi decidido a criação de um website para um integrante do grupo com intuito impulsionar seu projeto pessoal de robótica.
Ferramentas que foram utilizadas:
[**Wordpress**](https://wordpress.com/pt-br/) , [**Trello**](https://trello.com/pt-BR),  [**Elementor**](https://elementor.com/), [**Hospedagem Turbo Cloud**](https://wordpress.com/pt-br/),  [**Coudflare**](https://www.cloudflare.com/pt-br/lp/ppc/overview-x/?utm_source=google&utm_medium=cpc&utm_campaign=ao-fy-acq-latam_en_casa-umbrella-ge-ge-prospecting-sch_g_brand_alpha&utm_content=Alpha_Brand_Umbrella_Core&utm_term=cloudflare&campaignid=71700000112000371&adgroupid=58700008461369612&creativeid=664212396473&&_bt=664212396473&_bk=cloudflare&_bm=p&_bn=g&_bg=150613024493&_placement=&_target=&_loc=1001570&_dv=c&awsearchcpc=1&gad_source=1&gclid=EAIaIQobChMIoN3y1YGHhwMVyQCtBh0AjQ2_EAAYASAAEgLe0fD_BwE&gclsrc=aw.ds) e  [**Figma**](https://www.figma.com/login?is_not_gen_0=true&resource_type=team).
Monitoramento do projeto:
Via dailys e monitoramento pelo Trello
Introdução
Este documento descreve o processo de criação de um site no WordPress e as medidas de segurança implementadas tanto no WordPress quanto através do Cloudflare. O objetivo é fornecer um guia detalhado para a implementação de um site seguro, eficiente e de fácil manutenção.
1. Planejamento do Projeto
1.1 Objetivos
<br>
•	Criar um site responsivo e funcional utilizando o WordPress.
<br>
•	Garantir a segurança do site através de práticas recomendadas e o uso de serviços adicionais como o Cloudflare.
<br>
•	Implementar um design intuitivo e amigável ao usuário.
<br>
1.2 Escopo
<br>
•	Configuração inicial do WordPress.
<br>
•	Seleção e personalização de um tema.
<br>
•	Instalação de plugins essenciais.
<br>
•	Implementação de medidas de segurança.
<br>
•	Configuração do Cloudflare para otimização de desempenho e segurança.
<br>
1.3 Requisitos
<br>
•	Acesso a um servidor web com suporte a PHP e MySQL.
<br>
•	Domínio registrado.
<br>
•	Conta no Cloudflare.
<br>
3. Configuração do WordPress
<br>
2.1 Instalação do WordPress
<br>
1.	Baixar o WordPress: Acesse o site oficial do WordPress e baixe a última versão.
<br>
3.	Enviar arquivos para o servidor: Utilize um cliente FTP para enviar os arquivos do WordPress para o servidor.
<br>
5.	Configurar o banco de dados: Crie um banco de dados MySQL e um usuário associado.
6.	Instalar o WordPress: Acesse seu domínio e siga o assistente de instalação, fornecendo as informações do banco de dados.
2.2 Seleção e Personalização de Tema
1.	Escolher um tema: Acesse o repositório de temas do WordPress e selecione um tema que atenda às necessidades do projeto.
2.	Personalizar o tema: Utilize o personalizador do WordPress para ajustar cores, fontes, e layout.
2.3 Instalação de Plugins Essenciais
1.	SEO: Instale um plugin como o Yoast SEO para otimizar o site para mecanismos de busca.
2.	Backup: Configure um plugin de backup automático, como o UpdraftPlus.
3.	Segurança: Instale um plugin de segurança, como o Wordfence ou Sucuri.
3. Segurança no WordPress
3.1 Atualizações Regulares
•	Atualização do Core: Mantenha o WordPress sempre atualizado para a última versão.
•	Atualização de Plugins e Temas: Verifique e atualize regularmente todos os plugins e temas.
3.2 Gerenciamento de Usuários
•	Privilégios de Usuários: Conceda privilégios mínimos necessários para cada usuário.
•	Autenticação em Duas Etapas: Ative a autenticação em duas etapas (2FA) para todos os usuários administrativos.
3.3 Proteção contra Ataques
•	Firewall de Aplicação Web (WAF): Utilize um WAF para proteger contra ataques comuns como SQL Injection e XSS.
•	Limitação de Tentativas de Login: Instale um plugin que limite tentativas de login para evitar ataques de força bruta.
•	Monitoramento de Atividades: Utilize plugins que monitorem atividades suspeitas no site.
4. Configuração do Cloudflare
4.1 Registro e Configuração Inicial
1.	Registrar no Cloudflare: Crie uma conta no Cloudflare e adicione seu domínio.
2.	Alterar DNS: Atualize os registros DNS do seu domínio para usar os servidores DNS do Cloudflare.
4.2 Segurança com Cloudflare
•	SSL/TLS: Configure SSL/TLS para criptografar o tráfego entre os visitantes e o servidor.
•	Firewall: Utilize as regras de firewall do Cloudflare para bloquear tráfego malicioso.
•	Proteção DDoS: O Cloudflare fornece proteção contra ataques DDoS automaticamente.
4.3 Otimização de Desempenho
•	CDN: Ative a CDN do Cloudflare para armazenar em cache conteúdo estático e melhorar a velocidade de carregamento.
•	Minificação: Utilize as opções de minificação do Cloudflare para reduzir o tamanho de arquivos CSS, JavaScript e HTML.
•	Armazenamento em Cache: Configure as opções de cache para armazenar conteúdo frequentemente acessado.
5. Conclusão
A criação de um site no WordPress requer planejamento cuidadoso, desde a configuração inicial até a implementação de medidas de segurança. Utilizar serviços adicionais como o Cloudflare pode ajudar a proteger e otimizar o desempenho do site. Esta documentação serve como um guia para garantir que todas as etapas essenciais sejam cobertas, resultando em um site seguro, eficiente e de fácil manutenção.
6. Referências
•	Documentação Oficial do WordPress
•	Guia de Segurança do WordPress
•	Documentação do Cloudflare
