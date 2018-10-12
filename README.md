## MQTT mosquitto 사용하기

- service start
  - brew service start mosquitto
- service stop
  - brew service stop mosquitto
- service execute
  - /usr/local/sbin/mosquitto - c /usr/local/etc/mosquitto/mosquitto.conf
- message subscribe
  - Mosquito_sub -h [주소] -p [포트] -t[주제,방제목] 
- message publishing
  - Mosquito_pub -h [주소] -p [포트] -t[주제,방제목]  -m [메세지]

