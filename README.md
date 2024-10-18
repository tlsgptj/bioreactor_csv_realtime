# bioreactor_csv_realtime
redis 서버임
# 전체 아키텍쳐 흐름
1. ESP32 → Redis: ESP32에서 실시간으로 데이터를 수집하여 Redis에 저장.
2. Redis → Flutter 앱: Redis에서 데이터를 실시간으로 가져와 Flutter 앱에서 표시.
3. Redis → PostgreSQL: 일정 시간마다 또는 특정 이벤트 발생 시 Redis에 저장된 데이터를 PostgreSQL에 저장.
