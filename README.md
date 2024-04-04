# AZ-900-Ferramentas-de-implanta-o

# Ferramentas de Gerenciamento e Implantação

As ferramentas para interagir com o Azure são:
Portal do Azure
Azure PowerShell
Azure Cloud Shell
Interface de Linha de Comando (CLI)

São ferramentas diferentes com comandos diferentes, porém a finalidade é a mesma.

# Azure ARC ()

É uma solução da Microsoft que estende os serviços do Azure para recursos localizados fora da nuvem da Microsoft.
Com isso, trabalhamos com infraestrutura local e outros provedores de nuvens.
Em resumo, o Azure Arc oferece flexibilidade, consistência e controle para cargas de trabalho distribuídas em diversos ambientes.

# Azure ARM (Azure Resource Manager)

Fornece uma camada de gerenciamento que permite criar, atualizar e excluir recursos na assinatura do Azure.

O Azure ARC permite o gerenciamento de recursos em outras nuvens, são elas:
AWS E GCP (Google Cloud)


# Infraestrutura como Código

Caso seja preciso criar uma infraestrutura, onde precisamos criar várias máquinas virtuais, vários outros recursos, tendo um código padrão para criação, onde só alteramos as configurações, será um processo muito mais eficiente.





# Modelos do ARM

Os modelos do ARM são arquivos JSON, que podem ser usados para criar e implantar a infraestrutura do Azure sem a necessidade de escrever comandos de programação. 
Os pré-requisitos são:
Sintaxe declarativa
Resultados repetíveis
Orquestração
Arquivos modulares
Validação integrada
Código exportável

Sobre os modelos, temos:
Modelo Resource Manager (Um Modelo Enviado)
Infraestrutura como código sem modelo (Várias chamadas PUT imperativas)

# Azure Bicep

É uma linguagem de modelagem de infraestrutura como código (IaC) desenvolvida pela Microsoft para simplificar e aprimorar a criação e gerenciamento de recursos no Azure.  Onde oferece uma sintaxe mais limpa, legível e concisa para descrever recursos e suas dependências. Com o Bicep, os usuários podem definir infraestrutura de maneira declarativa, especificando recursos, propriedades e configurações em arquivos .bicep. Esses arquivos são compilados em modelos ARM equivalentes, facilitando a implantação de infraestrutura de maneira eficiente e consistente por meio de automação. O Azure Bicep simplifica o desenvolvimento, manutenção e colaboração em projetos de infraestrutura na nuvem do Azure. Os comandos do Bicep funcionam apenas na Microsoft.

# Resumindo, o Bicep é uma linguagem específica de domínio (DSL) que usa sintaxe declarativa para implantar recursos apenas dentro do  Azure.


