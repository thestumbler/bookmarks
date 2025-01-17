Logging
=======

* function/method의 시작과 끝 부분에 log를 넣자
  * 너무 많은 log를 남기는 게 보기 힘들 수는 있지만, 확인이 어려운 거 보다는 좋다
  * 최소한 해당 function/method 내부가 문제인지 외부가 문제인지는 확인이 가능하다
* 같은 API server를 여러 개의 section으로 나눠서 운영할 때 좋은 logging은 뭘까?
  * 서로 호출하는 동작이 있는데, logging을 나눠서 각각 저장하는 게 좋은가, 한 곳에 모아서 구분해서 보는 게 좋은가?
* [로그 기깔나게 잘 디자인하는 법](https://www.slideshare.net/jeongsangbaek/ss-80795259)
* [LoggingThe Ultimate Guide - your open-source resource for understanding, analyzing, and troubleshooting system logs](https://www.loggly.com/ultimate-guide/)
* [Centralized Logging at Signal](http://www.signal.co/dev-log/centralized-logging/)
* [DESIGNING A SEARCH SYSTEM FOR LOG DATA — PART 2](http://www.philipotoole.com/designing-a-search-system-for-log-data-part-2/)
* [Logging을 System.out으로 하면 안되는 이유](http://silentsoft.tistory.com/13)
* [Centralized Log Server 를 위한 기본 세팅 (EC2 + ElasticSearch + Logstash + filebeat + kibana)](http://knphouse.tistory.com/85)
* [log 생성하기](http://downman.tistory.com/155)
* [How-to: Log Analytics with Solr, Spark, OpenTSDB and Grafana](http://blog.cloudera.com/blog/2017/03/how-to-log-analytics-with-solr-spark-opentsdb-and-grafana/)
* [#review AWS + Tajo를 이용한 '테라 렉 로그 분석 이야기'](http://ohyecloudy.com/pnotes/archives/aws-tajo-tera-lag-log/)
* **[#ndc_15 #review 쿠키런 로그 시스템 - 바쁘고 가난한 개발자를 위해](http://ohyecloudy.com/pnotes/archives/ndc15-cookie-run-log-system/)**
* [Conetix Network Operations Centre Build Part 3 - Metrics and Monitoring](https://www.conetix.com.au/blog/conetix-network-operations-centre-build-part-3)
* [정적 기록자는 이제 그만](https://justhackem.wordpress.com/2017/07/07/no-more-static-logger/)
* [로그 데이터로 유저 이해하기](http://woowabros.github.io/woowabros/2017/07/30/logdata.html)
* [로그를 잘 남기기](https://ash84.net/2017/09/29/how-do-you-keep-your-logs/)
* [구글 스택드라이버를 이용한 애플리케이션 로그 모니터링](http://bcho.tistory.com/1214)
* [The Architecture of the Next CERN Accelerator Logging Service](https://databricks.com/blog/2017/12/14/the-architecture-of-the-next-cern-accelerator-logging-service.html)
* Building a Distributed Log from Scratch
  * [Part 1: Storage Mechanics](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-1-storage-mechanics/)
  * [Part 2: Data Replication](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-2-data-replication/)
  * [Part 3: Scaling Message Delivery](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-3-scaling-message-delivery/)
  * [Part 4: Trade-Offs and Lessons Learned](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-4-trade-offs-and-lessons-learned/)
  * [Part 5: Sketching a New System](https://bravenewgeek.com/building-a-distributed-log-from-scratch-part-5-sketching-a-new-system/)
* [Part 1: Building a Centralized Logging Application](https://medium.com/eulercoder/part-1-building-a-centralized-logging-application-5a537033da0a)
* [Logging in Android](https://android.jlelse.eu/logging-in-android-cfcd50cdc1ae)
* **NDC18 〈야생의 땅: 듀랑고〉의 데이터 엔지니어링 이야기: 로그 시스템 구축 경험 공유**
  * [1부](https://www.slideshare.net/ssuser380e9c/ndc18-95524337)
  * [2부](https://www.slideshare.net/ssuser380e9c/ndc18-2-95522893)
* [logrotate 사용하기 (CentOS 기준)](http://jybaek.tistory.com/761)
* [How To Write Error Messages That Don’t Suck](https://medium.freecodecamp.org/how-to-write-error-messages-that-dont-suck-f31c53b64c3e)
* **[로그 파일은 좋다](https://libsora.so/posts/log-file-is-good/)** 실제 구현에서 겪을 수 있는 상황에 대한 이야기라 좋음
* [더 나은 개발자로 성장합는 팁, " 로그를 잘 남기세요."](https://www.youtube.com/watch?v=HxzlJWMcHng)
* [로그 시스템의 개념과, 구글 스택드라이버 그리고 삼성전자 사례](https://bcho.tistory.com/1330)

# [Fluentd](http://www.fluentd.org/)
* [분산 로그 & 데이타 수집기 Fluentd](http://bcho.tistory.com/1115)
* [Personal Logging으로 삽질하기 #1](https://medium.com/@HatusneMiku3939/personal-logging%EC%9C%BC%EB%A1%9C-%EC%82%BD%EC%A7%88%ED%95%98%EA%B8%B0-1-d40ae348ac5e)
* [Personal Logging으로 삽질하기 #2](https://medium.com/@HatusneMiku3939/personal-logging%EC%9C%BC%EB%A1%9C-%EC%82%BD%EC%A7%88%ED%95%98%EA%B8%B0-2-36677466b8b8)
* [fluentd와 함께하는 검색 데이터 수집](https://dailyhotel.io/fluentd%EC%99%80-%ED%95%A8%EA%BB%98%ED%95%98%EB%8A%94-%EA%B2%80%EC%83%89-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%88%98%EC%A7%91-b76932a8dc2a)
* [Fluentd에서 PubSub로 데이터 보내기](https://jungwoon.github.io/bigquery/2017/11/13/BigQuery-Lecture-1/)
* [CNCF, Fluentd 프로젝트 졸업을 발표](https://www.44bits.io/ko/post/news--fluentd-has-graduated-cncf)
* [Fluentd vs. Logstash: A Comparison of Log Collectors](http://logz.io/blog/fluentd-logstash)
* [Fluentd로 데이터파이프라인 구축하기 kafka→kafka→s3](https://blog.voidmainvoid.net/261)

# Library
* [Apache logging services](https://logging.apache.org)
* [LOGAI – AUTOMATED LOG ANALYTICS FOR VALIDATION](https://ko.hortonworks.com/blog/logai-automated-log-analytics-validation/)
  * Hortonworks의 HDP 테스트에서 나온 로그를 분석하는 도구
  * 시스템에서 빈도(frequency), 동시 발생(co-occurence), 기타 상관 모델을 사용하여 에러를 하이라이트하고, trace와 기타 내용
  * Web UI 제공
* [LogDevice - a scalable and fault tolerant distributed log system](https://github.com/facebookincubator/LogDevice)
  * [LogDevice: a distributed data store for logs](https://code.fb.com/core-data/logdevice-a-distributed-data-store-for-logs/)
  * [Open-sourcing LogDevice, a distributed data store for sequential data](https://logdevice.io/blog/2018/09/12/open-sourcing-announcement.html)
* [Logswan is a fast Web log analyzer using probabilistic data structures](https://github.com/fcambus/logswan)
* [Palallax - Open Source Log Analyzer for Palo Alto Networks Next-Generation Firewall](http://www.ap-com.co.jp/ja/paloalto/palallax/index_en.html)
* [YALV - Yet Another Log Viewer](http://marsinvasion.github.io/yalv/)
