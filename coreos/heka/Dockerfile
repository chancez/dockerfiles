FROM ecnahc515/heka:0.9.0

ADD hekad.toml /etc/hekad.toml
ADD json.lua /usr/share/heka/lua_decoders/json.lua
ENTRYPOINT ["hekad"]
