ARG     BUILD_VERSION
FROM  	docker.u236.org/homed-web:2.2.8
COPY    homed-web.conf /root/
COPY    run.sh /
RUN     rm -rf /etc/homed
RUN     chmod +x /run.sh
CMD  	["/run.sh"]
