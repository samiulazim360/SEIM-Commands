# SEIM-Commands
essential commands
#curl -s https://artifacts.elastic.co/GPG-KEY-elasticsearch | gpg --no-default-keyring --keyring
gnupg-ring:/usr/share/keyrings/elasticsearch.gpg --import && chmod 644
/usr/share/keyrings/elasticsearch.gpg



2. #echo "deb [signed-by=/usr/share/keyrings/elasticsearch.gpg]
https://artifacts.elastic.co/packages/7.x/apt stable main" | tee /etc/apt/sources.list.d/elastic-7.x.list
