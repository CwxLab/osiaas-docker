FROM docker.pkg.github.com/cwxlab/osiaas/ubuntu:stein

RUN \
	apt-get update && \
	apt-get install -y \
		mariadb-server && \
	apt-get clean

RUN \
	rm -rf /var/lib/mysql/* && \
	mkdir /var/run/mysqld && \
	chown mysql:mysql /var/run/mysqld/

CMD ["mysqld"]
