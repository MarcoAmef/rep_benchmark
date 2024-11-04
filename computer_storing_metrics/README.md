# Monitoramento de Métricas do Sistema

Este projeto coleta e registra métricas do sistema, incluindo o uso de CPU, memória e disco, e armazena essas informações em um arquivo CSV. Cada métrica é coletada com o horário correspondente, permitindo um histórico de desempenho do sistema ao longo do tempo. 

## Funcionalidades

- **Monitoramento de CPU**: Coleta do percentual de uso da CPU a cada segundo.
- **Monitoramento de Memória**: Registro do percentual de uso da memória RAM do sistema.
- **Monitoramento de Disco**: Percentual de uso do disco do sistema.
- **Armazenamento de Dados**: Armazena as métricas em um arquivo CSV para facilitar a análise posterior.

## Estrutura do Arquivo CSV

As métricas são salvas no arquivo `metricas_sistema.csv`, com os seguintes campos:

- `Data e Hora`: Data e hora da coleta da métrica no formato `YYYY-MM-DD HH:MM:SS`.
- `Uso CPU (%)`: Percentual de uso da CPU no momento da coleta.
- `Uso Memória (%)`: Percentual de uso da memória RAM no momento da coleta.
- `Uso Disco (%)`: Percentual de uso do disco no momento da coleta.

## Requisitos

- **Python 3.x**

1. **Instalação**:
   - Certifique-se de ter o Python instalado em seu sistema.
   - Instale a biblioteca `psutil` usando o seguinte comando:
     ```bash
     pip install psutil
     ```

2. **Execução**:
   - Clone o repositório ou baixe os arquivos.
   - Execute o script Python:
     ```bash
     python seu_script.py
     ```
   - As métricas serão salvas em um arquivo chamado `metricas_sistema.csv`.

## Funcionalidades

- Coleta de métricas de uso de CPU, memória e disco.
- Armazenamento das métricas em um arquivo CSV, com registro de data e hora.
- Capacidade de registrar múltiplas medições em intervalos de um segundo.

3. **Visualização dos Dados**:
   - O arquivo `metricas_sistema.csv` pode ser aberto em qualquer editor de texto ou software de planilha (como Excel ou Google Sheets) para análise e visualização.
