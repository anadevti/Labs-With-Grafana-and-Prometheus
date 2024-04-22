# Labs With Grafana and Prometheus

Este repositório contém meus laboratórios e exemplos práticos para explorar e aprender a integrar Grafana e Prometheus para monitoramento de aplicações e infraestruturas.

## Descrição

Grafana é uma ferramenta de visualização e análise que permite transformar dados de diversas fontes em painéis gráficos dinâmicos. Prometheus, por sua vez, é um sistema de monitoramento e alerta de código aberto que coleta e armazena suas métricas como dados de séries temporais.

Este projeto visa oferecer um ambiente de aprendizagem para configurar e usar ambas as ferramentas em conjunto para monitoramento eficaz.

## Pré-Requisitos

Antes de começar, certifique-se de ter instalado:

- Docker
- Docker Compose

Estas ferramentas facilitarão a execução dos exemplos de forma isolada e controlada.

## Configuração e Instalação

Para começar a usar este repositório:

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/anadevti/Labs-With-Grafana-and-Prometheus.git
2. Navegue até o diretório do repositório:
   ```bash
   cd Labs-With-Grafana-and-Prometheus

3. Execute o seguinte comando para iniciar os containers via Docker Compose:
    ```bash
    docker-compose up



Isso irá levantar os serviços do Prometheus e Grafana, configurados para comunicação entre si.

## Utilização
Após iniciar os serviços, você pode acessar o Grafana em http://localhost:3000. Utilize as seguintes credenciais para login:

Usuário: 
admin
Senha:
admin
Recomendo alterar a senha no primeiro acesso por questões de segurança.

## Acessando Prometheus
Acesse em: http://localhost:9090/

