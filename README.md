# solr

#1)Instalar Solr(Qualquer nova versão)
2) Subir o servidor com o comando:
   
   bin/solr start
   
Obs: É preciso estar na pasta do Solr onde existe a pasta bin. 


3) Adicionar os cores pro Solr com os comandos

bin/solr create -c Document
bin/solr create -c DocumentDto
bin/solr create -c DocumentTinyDto
bin/solr create -c Files
bin/solr create -c User

4) Subir o projeto como de costume(Maven clean package e rodar o spring boot)
