---

copyright:

  years: 2018
lastupdated: "2018-05-07"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}


# O que é um recurso?
{: #resource}

Um recurso é qualquer coisa que possa ser criada, gerenciada e contida em um [grupo de recursos](/docs/resources/resourcegroups.html#rgs). Alguns exemplos incluem apps, instâncias de serviço, clusters de contêineres, volumes de armazenamento e servidores virtuais. Todas as instâncias de serviço que podem ser incluídas em um grupo de recursos, quando criadas no catálogo, são chamadas de recursos e são gerenciadas usando o controle de acesso IAM. Os serviços que suportam o uso do [funções do IAM para acesso](/docs/iam/users_roles.html#iamusermanrol) e organização em um grupo de recursos são serviços ativados por IAM.

Nem todos os serviços suportam o uso de grupos de recursos e IAM neste momento. Todas as instâncias de serviço incluídas em organizações e espaços do Cloud Foundry, quando criadas no catálogo, são distintamente diferentes dos serviços ativados por IAM. Os serviços do Cloud Foundry não têm conexão com grupos de recursos e usam [funções do Cloud Foundry para gerenciamento de acesso](/docs/iam/cfaccess.html#cfaccess). Esses serviços são chamados de serviços do Cloud Foundry. Conforme os serviços ativam o suporte para o IAM e grupos de recursos, você é notificado sobre a capacidade de [migrar instâncias existentes do Cloud Foundry para um grupo de recursos](/docs/resources/instance_migration.html#migrate).


