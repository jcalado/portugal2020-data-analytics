# Análise de dados do Programa Portugal 2020
Os dados analisados neste notebook são fornecidos pelo site dados.gov.pt.

O notebook descarrega automaticamente o dataset e converte o ficheiro XLSX em CSV, por questões de performance. **Nenhum dado é manipulado neste processo.**

## Atualização de dados
Se já tiver um ficheiro operacoes.csv (gerado pelo notebook), mas quiser forçar o download e conversão do ficheiro novamente, pode mudar a variável `download` para `True`.  
Depois do processo concluído, deve voltar a mudar a variável para `False` ou irá gerar uma carga desnecessária no seu sistema e no site dados.gov.pt.