# DioSantander-BI-Transformando
Repositorio criado para o desafio de projeto de transformação de dados utilizando o Power Bi

* Todo
- [x] Verifique os cabeçalhos e tipos de dados

- [x] Modifique os valores monetários para o tipo double preciso 

- [x] Verifique a existência dos nulos e analise a remoção 

- [x] Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

- [x] Verifique se há algum departamento sem gerente 

- [x] Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas

- [x] Verifique o número de horas dos projetos 

- [x] Separar colunas complexas 

- [x] Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção 

- [x] Neste processo elimine as colunas desnecessárias. 

- [x] Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo. 

- [x] Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores 

- [x] Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.

- [x] Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir. 
  - Porque precisamos utilizar os valores das duas colunas.
- [x] Agrupe os dados a fim de saber quantos colaboradores existem por gerente

- [x] Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela
