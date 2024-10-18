# bioreactor_csv_realtime
redis 서버임
# 전체 아키텍쳐 흐름
1. ESP32 -> 서버 : ESP32에서 서버로 데이터를 전송(MQTT)
2. 서버 -> Redis(캐싱) : 서버는 실시간 데이터를 Redis에 캐싱
3. 서버 -> PostgreSQL : 영구 저장을 위해 서버는 PostgreSQL에 데이터 저장
4. 
