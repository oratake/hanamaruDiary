FROM mysql/mysql-server:5.7

ENV MYSQL_DATABASE=db \
  MYSQL_USER=user \
  MYSQL_PASSWORD=password \
  MYSQL_ROOT_PASSWORD=secret \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf