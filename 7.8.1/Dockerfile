# https://github.com/elastic/elasticsearch-docker
FROM elasticsearch:7.8.1

# https://github.com/medcl/elasticsearch-analysis-ik/releases
ENV IK_RELEASE=https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.8.1/elasticsearch-analysis-ik-7.8.1.zip
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch $IK_RELEASE
