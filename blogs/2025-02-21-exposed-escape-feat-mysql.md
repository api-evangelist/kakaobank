---
title: "Exposed에서 도망 간 Escape를 찾습니다 (feat. MySQL)"
url: "/posts/2502-exposed-with-mysql-troubleshooting/"
date: "2025-02-21"
feed_url: "https://tech.kakaobank.com/index.xml"
---
어느 날, 모니터링 시스템에서 ‘SQLSyntaxErrorException’이 발생했다는 알림을 받았습니다. Exposed와 MySQL로 구성된 서비스에서 이스케이프(Escape) 문자열 처리와 관련된 문제가 발생한 것인데요. 4단계에 걸친 디버깅 과정을 거쳐 오류 로그를 분석한 끝에 Exposed가 문제의 원인이었음을 밝혀냈습니다.
