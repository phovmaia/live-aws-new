# just another readme <3

Bora lá, começar a brincadeira!
Vamos começar a escrever todo esse conteúdo junto e vamos aprendendo e tirando dúvidas juntos.

- instalar tudo que precisamos
  - git
  - terraform
  - terragrunt
  - aws-cli
  - leapp.cloud
- criar conta na aws

## objetivo

    *step by step*
desenhar arquitetura (draw.io)
entender cada serviço que usaremos (AWS)
criar modulos e provisionar recursos (terraform + terragrunt)
criar pipelines (github actions)

## Notas importantes do projeto

  1. prd e dev são ambientes completamente isolados e em contas diferentes da AWS
  2. teremos 3 contas: root, dev e prd
  3. usaremos o serviço "AWS Organizations" para criar as contas seguindo as boas práticas
  4. a conta root não terá acesso a nada, apenas para criar as outras contas
