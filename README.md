# just another readme <3

Bora lá, a brincadeira vai começar!

## como vamos seguir a criação do projeto

desenhar arquitetura (draw.io)
entender cada serviço que usaremos (AWS)
criar modulos e provisionar recursos (terraform + terragrunt)
criar pipelines (github actions)

## Notas importantes do projeto

  1. prd e dev são ambientes completamente isolados e em contas diferentes da AWS
  2. teremos 3 contas: root, dev e prd
  3. usaremos o serviço "AWS Organizations" para criar as contas seguindo as boas práticas
  4. a conta root não terá acesso a nada, apenas para criar as outras contas
