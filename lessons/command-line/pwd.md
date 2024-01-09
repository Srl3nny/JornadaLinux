# pwd (Print Working Directory)

Tudo em Linux é arquivo, você entenderá isso ao longo da jornada pelo prompt. Todo arquivo é organizado em um estrutura de diretórios hierarquica. O primeiro diretório no filesystem é chamado de root (não confunda com o usuário). O diretório root tem muito diretórios e arquivos. Abaixo uma exemplo de como é uma árvore de diretórios:

<pre>/
|-- bin
|   |-- arq1
|   |-- arq2
|-- etc
|   |-- arq3
|   `-- dir1
|       |-- arq4
|       `-- arq5
|-- home
|-- var
</pre>

A Localização desses arquivos é referênciada pelos paths. Por exemplo, podemos ter uma pasta documentos dentro do diretório home do usuário bruno, ficando assim: /home/bruno/documentos.

Durante a navegação é interessante saber onde você se encontra, e para isso temos o comando *pwd*

<pre>$ pwd</pre>

