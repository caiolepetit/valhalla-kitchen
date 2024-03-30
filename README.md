# valhalla-kitchen

### api-pedido
https://github.com/renanfe/pedido-valhalla-kitchen

### api-pagamento
https://github.com/renanfe/pagamento-valhalla-kitchen

### api-producao
https://github.com/renanfe/producao-valhalla-kitchen

## Como executar o projeto
O projeto é composto por três microserviços desenvolvidos em Java, dois do microserviços utilizam banco de dados postgres e um utiliza mongodb.

Para realizar a execução de todos os containeres será necessário possuir o docker (docker compose) instalado (https://docs.docker.com/engine/install/).

E executar o comando abaixo, após realizar a clonagem do projeto.

```git clone https://github.com/caiolepetit/valhalla-kitchen.git```

```docker-compose up```

## Justificativa utilização padrão Saga Coreografado
Optamos por utilizar o padrão Saga Coreografado, por preferir que cada microserviço seja responsável pelas regras de negócio e também de fluxo. Não tendo dessa forma dependência e um novo ponto de falha 'Orquestrador';
Também foi levado em conta que o padrão escolhido é o mais indicado para fluxos com pouca complexidade.

## Relatório OWASP ZAP
https://drive.google.com/drive/folders/191fbKKitGasZBtdzzPQczHQTc2x-vZ2z?usp=drive_link

## Relatório RIPD
https://docs.google.com/document/d/1jc_X5nlezCIpn--O55OOc2GmKW2SVIBP/edit?usp=drive_link&ouid=118026271297561295223&rtpof=true&sd=true

## Arquitetura do sistema
https://drive.google.com/file/d/1pzd0IfiymNGdQOckFLbNPovJDeZMgLBP/view?usp=drive_link
