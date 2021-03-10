# Mini-Projeto 1 – Importando Dados do Banco de Dados Oracle para o HDFS

13º Capítulo vamos realizar o Mini-Projeto 1 - Importando Dados do Banco de Dados Oracle para o HDFS. O Mini-Projeto já veio com Scripts para realizar o Mini-Projeto, porém, não é um passo a passo e contém erros propositais para resolução por parte dos alunos:

<ul>
  <li>Especificação do Mini-Projeto 1</li>
</ul>

# Resolução do Mini-Projeto 1
<ul>
  <li>1-Inicializar o Listener</li>
  <li>2-Inicializar o Banco de Dados Oracle</li>
  <li>3-Verificar conexão do Listener com o Banco de Dados</li>
  <li>4-Testar conexão</li>
  <li>5-Criar o Schema</li>
  <li>6-Conectar ao Banco</li>
  <li>7-Criar uma tabela</li>
  <li>8-Usando SQL Loader para carregar dados no Oracle, criar arquivo loader.dat com os dados</li>
  <li>9-Executando o SQL Loader</li>
  <li>10-Verificar arquivo de Log</li>
  <li>11-Conferir carga de dados</li>
  <li>12-Inicializar HDFS e Yarn</li>
  <li>13-Conceder Privilégios ao usuário Oracle</li>
  <li>14-Temos que conhecer privilégio para diretório de log do Hadoop</li>
  <li>15-Acrescentar o usuário Oracle para o Grupo do Hadoop</li>
  <li>16-Importação de Dados do Oracle para o HDFS</li>
  <li>17-Checagem dos dados no HDFS</li>
</ul>

# Visualização dos Dados
hdfs dfs -cat /user/oracle/saidaprojeto/part-m-00000
<center><img src="https://user-images.githubusercontent.com/61481422/110704388-a7e7c900-81d3-11eb-89e4-d797d4987eea.png" alt="" width="800"></center>
