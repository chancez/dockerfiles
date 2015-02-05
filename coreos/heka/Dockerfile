FROM mozilla/heka

RUN cd build && make install
ADD hekad.toml /etc/hekad.toml
ENTRYPOINT ["hekad", "-config", "/etc/hekad.toml"]
