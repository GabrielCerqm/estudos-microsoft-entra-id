# Microsoft Entra ID — Registro de aprendizado em IAM

Registro pessoal de Gabriel Cerqueira sobre os conhecimentos trabalhados no laboratório associado à credencial **Microsoft Applied Skills: Get started with identities and access using Microsoft Entra**.

## Objetivo e contexto

Consolidar aprendizados de administração de identidades e acessos em um ambiente temporário de estudo. A experiência envolveu operações administrativas no Microsoft Entra ID e a leitura de configurações de segurança.

Este material é uma reflexão técnica autoral. Não constitui implantação em produção, laboratório reproduzível ou guia de resolução da avaliação. O ambiente original não está disponível para novos testes.

## Áreas trabalhadas

| Área | Aprendizado |
|---|---|
| Usuários | Administração de contas, atributos de perfil e estado de habilitação |
| Licenciamento | Relação entre usuário, local de uso e atribuição de licença |
| Grupos | Diferença entre membros e proprietários e organização de acessos |
| Funções administrativas | Atribuição de permissões e distinção entre funções e associação a grupos |
| Identidades externas | Conceito de colaboração com usuários convidados |
| Proteção de senhas | Leitura e documentação das configurações existentes |
| Redefinição de senhas | Interpretação de métodos de autenticação e do escopo das políticas |
| Acesso Condicional | Análise de atribuições, condições e resultados de simulação |
| Localizações nomeadas | Interpretação de localizações definidas por países ou regiões |
| Documentação | Registro fiel do estado observado, separando evidência de suposição |

## Processo de trabalho

A experiência foi organizada em quatro frentes, descritas em nível conceitual:

1. **Compreensão do ambiente:** identificar o objetivo das atividades e distinguir operações de configuração de consultas para documentação.
2. **Administração de identidades:** trabalhar com contas, grupos, licenciamento e permissões, observando o escopo de cada alteração.
3. **Leitura de segurança:** consultar configurações e reconhecer que políticas de públicos diferentes não devem ser tratadas como equivalentes.
4. **Análise e registro:** interpretar simulações de acesso, relacionar os resultados aos parâmetros utilizados e documentar somente o que foi observado.

Esta síntese não preserva a sequência, os valores ou os resultados específicos da avaliação.

## Principais aprendizados

### Planejar os grupos antes da criação

A experiência reforçou a importância de verificar previamente se um grupo precisa receber funções administrativas. Esse requisito influencia sua criação e não deve ser tratado como uma propriedade comum de edição posterior.

### Separar associação e responsabilidade

Ser membro de um grupo e ser seu proprietário representam responsabilidades diferentes. Da mesma forma, a atribuição de uma função administrativa deve ser analisada pelo acesso que concede.

### Conferir o escopo da configuração

Uma tela referente à política de administradores não basta para descrever toda a configuração de redefinição de senhas da organização. O registro precisa corresponder à configuração e ao público efetivamente analisados.

### Distinguir correspondência e imposição de uma política

Na análise de Acesso Condicional, uma política pode corresponder ao cenário simulado e estar em modo somente relatório. Ler o estado da política é tão importante quanto identificar sua presença no resultado.

### Tratar a simulação como evidência limitada

O resultado depende das entradas utilizadas. A análise deve considerar identidade, recurso e contexto de acesso. Uma simulação não equivale à comprovação de um acesso real bem-sucedido.

## Limitações e transparência

- Ambiente temporário disponibilizado para estudo e avaliação.
- Sem reprodução independente posterior ou ambiente operacional mantido neste repositório.
- Sem alegação de automação, uso de infraestrutura como código ou validação em produção.
- Credencial mencionada como contexto da experiência; link público de verificação ainda não adicionado.

## Preservação do conteúdo da avaliação

Este repositório não inclui enunciados, e-mails do laboratório, respostas, combinações de parâmetros, resultados específicos, capturas da avaliação, arquivos fornecidos pela plataforma ou roteiros para sua resolução.

Também foram excluídos nomes de contas e grupos do cenário, domínios do tenant, endereços IP, identificadores de sessão e quaisquer credenciais. A visibilidade privada não substitui esse cuidado.

## Continuidade dos estudos

Uma possibilidade de evolução é criar um cenário independente para aprofundar a validação de permissões e políticas. Essa reprodução ainda não foi realizada.

---

**Autor:** Gabriel Cerqueira  
**Foco:** Gestão de Identidades e Acessos (IAM) e Segurança da Informação
