FROM  elasticsearch:7.9.3

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

# kuromojiをインストール
RUN elasticsearch-plugin  install analysis-kuromoji

# RUN elasticsearch-plugin remove x-pack
