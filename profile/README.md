# Terraform Magalu Cloud Modules

Bem-vindo a organização de módulos do Terraform MGC! Esta organização é dedicada ao desenvolvimento e manutenção de módulos reutilizáveis para a infraestrutura como código usando Terraform.

## Visão Geral

O objetivo desta organização é fornecer uma coleção de módulos Terraform que podem ser utilizados para gerenciar a infraestrutura de maneira eficiente e padronizada. Esses módulos são projetados para serem reutilizáveis e configuráveis, facilitando a implementação de boas práticas na gestão da infraestrutura.

## Estrutura do Repositório

Cada módulo está contido em seu próprio repositório e segue uma estrutura padrão para facilitar o uso e contribuição. A estrutura geral de um repositório de módulo é a seguinte:

- `main.tf`: Arquivo principal de configuração do Terraform.
- `versions.tf`: Especifica as versões dos provedores que o módulo suporta.
- `variables.tf`: Declaração de variáveis usadas pelo módulo.
- `outputs.tf`: Declaração de outputs do módulo.
- `README.md`: Documentação do módulo, incluindo exemplos de uso e instruções de configuração.


## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir com novos módulos ou melhorias nos módulos existentes, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma nova branch para suas alterações: `git checkout -b minha-feature`.
3. Faça o commit das suas alterações: `git commit -m 'Adiciona nova feature'`.
4. Envie para o repositório remoto: `git push origin minha-feature`.
5. Abra um Pull Request para revisão.

## Documentação

Os módulos são da comunidade e seguem as documentações oficiais da Magalu Cloud, que podem ser consultadas para maiores informações:
- [Documentação do Provider Terraform Magalu Cloud](https://registry.terraform.io/providers/MagaluCloud/mgc/latest/docs)
- [Documentação da Magalu Cloud](https://docs.magalu.cloud/)
