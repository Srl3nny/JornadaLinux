# pwd (Print Working Directory)

Tudo no Linux é considerado um arquivo, e você entenderá isso ao longo da jornada no prompt de comando. Cada arquivo é organizado em uma estrutura de diretórios hierárquica. O primeiro diretório no sistema de arquivos é denominado 'root' (não confunda com o usuário). O diretório root contém muitos outros diretórios e arquivos. Abaixo, segue um exemplo de como é uma árvore de diretórios

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

A localização desses arquivos é referenciada pelos caminhos (paths). Por exemplo, podemos ter uma pasta chamada 'documentos' dentro do diretório home do usuário Bruno, ficando assim: /home/bruno/documentos.

Durante a navegação, é importante saber onde você está, e para isso, utilizamos o comando *pwd*.

<pre>$ pwd</pre>

