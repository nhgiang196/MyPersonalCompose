

## Cách cài đặt plugin

copy plugin vao thu muc redmine_data , giai nen
docker exec -it redmine_redmine_1 bash
cd /opt/bitnami/redmine
bundle install (nếu có yêu cầu về option thì chạy đúng yêu cầu trước)
touch tmp/restart.txt


	## Cài đặt plugin Im Link

docker exec -it redmine_redmine_1 bash
cd /opt/bitnami/redmine/plugins/
git clone https://github.com/mikitex70/redmine_drawio
cd ..
bundle install
touch tmp/restart.txt


