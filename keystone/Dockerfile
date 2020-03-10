FROM docker.pkg.github.com/cwxlab/osiaas/ubuntu:stein

RUN \
	DEBIAN_FRONTEND=noninteractive apt-get install -y \
		keystone

CMD ["apachectl -D FOREGROUND"]
