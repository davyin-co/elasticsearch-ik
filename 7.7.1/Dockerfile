# https://github.com/elastic/elasticsearch-docker
FROM elasticsearch:7.7.1

# https://github.com/medcl/elasticsearch-analysis-ik/releases
ENV IK_RELEASE=https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.7.1/elasticsearch-analysis-ik-7.7.1.zip
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch $IK_RELEASE
