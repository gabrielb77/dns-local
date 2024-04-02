FROM internetsystemsconsortium/bind9:9.18

COPY cfg/* /etc/bind/

ENTRYPOINT ["/usr/sbin/named"]
CMD ["-g", "-c", "/etc/bind/named.conf", "-u", "bind"]
