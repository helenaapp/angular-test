# Instruções

- Você deve criar uma aplicação front-end utilizando angular na versão 6 ou superior;
- Utilize **boas práticas** de desenvolvimento e **componentização**. Essa é sua oportunidade de demonstrar suas habilidades;
- Não nos importamos se a solução estiver *incompleta*, estamos interessados em ver a construção da sua solução;
- Não é obrigatório seguir fielmente as cores e icones do guia (veja no final do teste), mas é importante seguir a mesma estrutura;
- Você pode utilizar qualquer framework ou componente de terceiros que desejar;

# GitHub

- Faça um *fork* do projeto no GitHub;
- Adicione @helena-app-dev como um colaborador do seu *fork*. Você pode facilmente fazer isso em https://github.com/`seu-usuario`/angular-test
/settings/collaboration;
- Quando iniciar o teste, faça um *commit* vazio com a mensagem `iniciando teste` e quando finalizar, faça um *commit* com a mensagem `finalizando teste`;
- Faça vários *commits* com o objetivo de demonstrar a construção da solução;
- Não use *branches*;
- Tente não gastar mais do que 4 horas para finalizar o teste;

-------------------------------------------------------------

# Teste

**API:** https://api.helena.app/test/

**Documentação:** https://api.helena.app/test/swagger

Os dados expostos pela API acima são restaurados de tempos em tempos, não se preocupe com isso. 


**1 - Construa uma interface que liste todas as empresas e seus dados conforme a API acima;**

**Endpoint:** /api/company **(GET)**

Informações:

Os campos a serem mostrados na interface devem ser:
- Avatar (imagem)
- Razão social
- Quantidade de funcionários
- Situação (Ativo/Inativo)

    
    
    
**2 - Agora você deve criar uma nova interface para edição dos dados da empresa;**

**Endpoint:** /api/company/:id **(PUT)**

Informações:

- Não é necessária a edição da imagem. 
- O campo Active não pode ser alterado
    
    
    
**3 - Agora você deve permitir que uma nova empresa seja incluída;**

**Endpoint:** /api/company **(POST)**

Informações:

- O campo Id é gerado automaticamente pela API
    
    
    
**4 - Agora você deve permitir que uma empresa seja excluída;**

**Endpoint:** /api/company/:id **(DELETE)**

Informações:

- Após a exclusão, a empresa será listada mas com o campo Active = False




***EXTRA***

Será considerado um diferencial se você fizer tratamentos de erros, falhas de rede e indicadores de carregamento para melhorar a usabilidade do usuário.
