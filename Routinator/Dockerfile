FROM nlnetlabs/routinator

RUN routinator init -f --accept-arin-rpa
ENTRYPOINT ["/sbin/tini", "--", "routinator"]
CMD ["server", "--rtr", "173.16.238.12:3332", "--http", "173.16.238.12:9556"]
