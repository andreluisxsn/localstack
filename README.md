### Para utilizar o localstack

  - Rodando o localstack no Docker
  
    docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstack

    Necessário o aws-cli

    Após criar o container e fazer a configuração fictícia do aws-cli, você já está apto a utilizar o terraform/aws localmente sem necessidade de ter uma account     na aws.
