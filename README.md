# i_solr  based on official solr docker 8.5 but base image was replaced to ubuntu:20.04
mkdir solrdata
docker run -t --rm -v "$PWD/solrdata":/var/solr i_solr:$TAG

