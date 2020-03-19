FROM docker.pkg.github.com/cwxlab/osiaas/ubuntu:stein

RUN \
	DEBIAN_FRONTEND=noninteractive apt-get install -y \
		keystone

CMD ["/usr/sbin/apachectl -D FOREGROUND"]
