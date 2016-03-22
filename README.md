# solr-tutorial

## Install

yum install lucidworks-hdpsearch

## Start
Start the examples

bin/solr start -e techproducts

Check Solr Status

$ bin/solr status

Collection Name

Create a core

bin/solr create -c adobe_code

Post the example

bin/post -c adobe_code example/exampledocs/*.xml

http://localhost:8983/solr/adobe_code/select?q=video&fl=id,name,price

http://172.16.106.130:8983/solr/adobe_code/browse

