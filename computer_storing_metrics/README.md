# Monitor de Métricas do Sistema

Este projeto tem como objetivo coletar e armazenar métricas de desempenho do sistema, incluindo uso de CPU, uso de memória e uso de disco, em um arquivo CSV. As métricas são registradas em intervalos regulares, permitindo uma análise do desempenho do sistema ao longo do tempo.

## Tecnologias Utilizadas

- **Python**: A linguagem de programação utilizada para a coleta de métricas.
- **psutil**: Biblioteca Python para obter informações sobre o uso de recursos do sistema.
- **CSV**: Formato de arquivo utilizado para armazenar as métricas coletadas.

## Funcionalidades

- Coleta de métricas de uso de CPU, memória e disco.
- Armazenamento das métricas em um arquivo CSV, com registro de data e hora.
- Capacidade de registrar múltiplas medições em intervalos de um segundo.

## Como Usar

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

3. **Visualização dos Dados**:
   - O arquivo `metricas_sistema.csv` pode ser aberto em qualquer editor de texto ou software de planilha (como Excel ou Google Sheets) para análise e visualização.

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou sugestões! 

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

Para dúvidas ou sugestões, entre em contato comigo em [seu_email@example.com](mailto:seu_email@example.com).
