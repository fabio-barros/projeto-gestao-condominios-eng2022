## Sistema de Gerênciamento de Condomínio

## Integrantes do grupo 
 * Fábio Ribeiro - whatupfabio@gmail.com
 * Filipe Moreira Gomes - filipe_m_gomes@hotmail.com
 * Matheus Gabriel Vieira Soares - mgvsmatheus1@gmail.com
 * Pedro Henrique de Oliveira Santos - pedrohenrique110401@outlook.com
 * Paulo Henrique da Silva - paulo.hsilva6@ufrpe.br
 * João Victor de Sena Lemos Gomes Marinheiro - joaovictordesena2020@gmail.com
 * Rubson Hebrain de Lima Freire - limarubson@hotmail.com

## Descrição geral do projeto 

>### Condomínios têm se tornado um tipo de habitação cada vez mais comum. Diariamente, tarefas, obrigações e problemas se apresentam aos seus residentes e administradores, tais como solicitação de serviços, controle do pagamento de despesas e obtenção de informações. 
>### Por via de regra, a responsabilidade de gerenciamento de tais demandas se concentra na figura do Síndico, seja ele condômino eleito por assembleia ou profissional de Gestão Condominial. De modo que pode por um lado um condômino pode não ter conhecimentos administrativos, burocráticos e habilidades para lidar com essa demanda de forma eficiente; Por outro lado a contratação de empresa especializada pode acarretar em custos recorrentes ao condomínio. 
>### Tornando nesse cenário uma opção praticável e de demanda evidente a disponibilidade de um software de gerenciamento a disposição de síndicos e condôminos, de modo a agilizar e desburocratizar as tarefas de um condomínio; tendo a disposição do síndico informações como lista de moradores com dados pessoais e informações sobre pagamentos de despesas, produzir informativos que ao invés de serem fixados em murais possam ser notificados aos moradores por e-mail, WhatsApp, etc... E aos moradores opções como a possibilidade de solicitação de serviços, informações sobre possíveis intervenções estruturais que ocorrerão no seu piso. Tornando assim o síndico independente na administração do condomínio, e os condôminos menos frustrados e mais insformados.

 ### 1. Quem vai usar o programa?
	Síndicos e moradores de um condomínio.
 ### 2. Que serviços são “necessários” (leia-se: importantes para os clientes e usuários)?
	 > Realizar pagamentos, Solicitar Serviços...
 ### 3. Quais serviços cada usuário pode executar?
**Síndico**:

	  Gerar de relatórios de serviços, pagamento...;
	  Cadastro de moradores, veículos e funcionários;
	  Aprovação de solicitações de serviços;
	  Gerar notificações gerais e individuais;
	  Convocação de assembleias;
	  Aplicação de multas;
**Morador**:
	  
	  Obter informações sobre e realizar pagamentos;
	  Solicitar documentos;
	  Solicitar servições de manutenção, entre outros;
	  
	  
	  
	 

## Requisitos do projeto
Liste de forma numerada e com identificadores únicos os seus requisitos de projeto. 
 * **REQ1** - O sistema deve permitir o gerenciamento (Create, Recover, Update e Delete - CRUD) de moradores, veículos, funcionários (?) 
 * **REQ2** - O sistema deve controlar o acesso através de login e senha. Os usuários do sistema serão do tipo administrador, morador e funcionário(?).
 * **REQ3** - O sistema deve permitir solicitação de serviços básicos de um condomínio por parte dos moradores.
 * **REQ4** - O sistema deve permitir o geração de informativos e a notificação dos usuários através de email.
 * **REQ5** - O sistema deve permitir o gerenciamento de despesas de moradores e esta ação somente poderá ser executada por usuários administradores(síndicos).
 * **REQ6** - O sistema deve permitir emitir relatórios de pagamento e de solicitação de serviço, salvando em um histórico com relação ao morador.
 
## Cronograma de MVPs com seleção de requisitos
Exemplo de sequência de MVPs:
* **MVP1 - Cadastros** - [REQ1, REQ2]: Sistema de autenticação e cadastro de todas as entidades.
* **MVP2 - Serviços e Informativos** - [REQ3, REQ4]: Solicitação de serviços pelo moradores
* **MVP3 - Pagamentos e relatórios** - [REQ5, REQ6]: Pagamentos por parte dos moradores
