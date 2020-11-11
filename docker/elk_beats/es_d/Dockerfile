FROM  elasticsearch

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

# kuromojiをインストール
RUN elasticsearch-plugin  install analysis-kuromoji

# RUN elasticsearch-plugin remove x-pack
