# index

front서버: 티브로드 70%, 나머지 80%

/: db 로그 및 기타로그, /zeta-data: STB에서 올라오는 재핑로그 및 front 모듈 로그

\(db로그의 경우, 쿼리 실행한 로그들 날려줌\)

mysql root pw: mobinet

실행 쿼리 로그 제거: purge binary logs before '2019-07-25 00:00:00';

edge서버: 정해진거 없이 많으면 로그 삭제

/: master 모듈 로그 및 기타로그, /data: front에서 가져온 재핑로그

