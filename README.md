# Qualidade-SW-2017-2
Plano de Gerência de Configuração de Software. 

## 1. Introdução
Esse documento tem como finalidade apresentar as políticas do projeto para controle de gerência de configuração e mudança.

## 2. Planejamento do Gerenciamento de Configuração de Software 

# 2.1. Organização, Responsabilidades e Interfaces
A definição de uma política de gerência de configuração e mudança é muito importante para evitar problemas de atrasos, o que pode acaber acarretando aumentos nos custos do projeto. Portanto, as responsibilidades e atividades abaixo foram definidas para a otimização do processo.

Atividade      | Descrição | Responsável |
--------: | :---: | :---: |
Planejar Configuração do Projeto e Controle de Mudanças | Diretrizes para gerenciamento de configuração, políticas e processos para controlar mudanças | Membros e GPP | 
Configurar Ambientes do Projeto  | Estabelecer ambiente para criação, manutenção e compartilhamento de repositório do projeto | Equipe de GPP | 
Alterar e liberar itens de configuração | Criar espaço de trabalho, permitir acesso à artefatos, realizar mudanças nos artefatos e permitir compartilhamento | Equipe de GPP |
Gerenciar baselines e releases | Garantir que o produto de qualidade seja disponibilizado para releases | Equipe de GPP |
Monitorar e Relatar Status de Configuração | Realizar a validação do produto, garantir a visibilidade dos artefatos	 | Equipe de GPP |
Gerenciar Solicitações de Mudança | Assegurar que mudanças feitas no projeto sejam consistentes, e que essas mudanças sejam informados a todos da equipe | Equipe de GPP |


# 2.2. Ferramentas
O projeto irá utilizar as seguintes ferramentas

Ferramenta      | Versão | Descrição |
--------: | :---: | :---: |
Git | 1.9.1 | Sistema de versionamento de código | 
GitHub | - | Ferramenta paro gerenciamento de documentos e código | 

## 3. Controle e Monitoramento da Configuração de Software
# 3.1. Níveis de controle de configuração

O projeto irá utilizar três níveis de controle de configuração, sendo eles:

Nível      | Descrição |
--------: | :---: |
Controlado | A mudança somente será feita após a aprovação do grupo de GPP | 
Monitorada | A mudança somente será feita a partir de uma política estabelecida para a configuração | 
Comunicada | A alteração pode ser feita por qualquer membro do grupo mediante a comunicação para os outros integrantes | 



## 4 Controle de nomenclatura
O projeto irá utilizar o seguintes padrão na nomenclatura dos arquivos e pastas afim de facilitar a rastreabilidade de um determinado documento.
# Controle de nomes de arquivos

Primeiro arquivo ou pasta do diretorio | Segundo arquivo ou pasta do diretorio | Terceiro arquivo ou pasta do diretorio |
:---: | :---: | :---: | 
01-NOME DO ARQUIVO | 02-NOME DO ARQUIVO |  03-NOME DO ARQUIVO |

# Controle de nomes de commits
Com o intuito de padronizar o fluxo de comunicação nesse processo, é estabelecido um padrão de caracteres para especificar o que exatamente cada novo commit fará.

Deletando um arquivo | Modificando um arquivo | Substituindo um arquivo |
:---: | :---: | :---: | 
DEL-BREVE JUSTIFICATIVA | MOD-PRÉVIA DA MODIFICAÇÃO REALIZADA |  SUB-BREVE DESCRIÇÃO DO ARQUIVO ATUAL |

## 5 controle de tipos de arquivos
Nesse documento os arquivos estão padronizados da seguinte maneira.

Tipo de documento | Formato adotado |
:---: | :---: | 
Template | .docx |
Definição gráfica de atividades | .png |
Template | .docx .xlsx |
