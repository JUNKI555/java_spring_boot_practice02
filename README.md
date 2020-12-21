# Java Spring Boot Practice 02

# Web API EndPoint
- curl http://localhost:8080 -X GET
  - [{id:1,name:test}]
- curl http://localhost:8080/users -X GET
- curl http://localhost:8080/users -X POST -H "Content-Type:application/json" -d '{ "name":"foo" }'
- curl http://localhost:8080/users -X POST -H "Content-Type:application/json" -d '{ "name":"bar" }'
- curl http://localhost:8080/users/3 -X PUT -H "Content-Type:application/json" -d '{ "name":"baz" }'

## Reference sources
- docker-compose 下で Java + Spring Boot + PostgreSQL (JPA編) | 北山淳也 | zenn
  - https://zenn.dev/junki555/articles/de2c9844a1d101
- OpenJDK | DockerHub
  - https://hub.docker.com/_/openjdk
- JDK Project Releases | OpenJDK
  - http://openjdk.java.net/projects/jdk/
- postgres | DockerHub
  - https://hub.docker.com/_/postgres
- Adminer | DockerHub
  - https://hub.docker.com/_/adminer
- Spring Initializr
  - https://start.spring.io/
- Java ORマッパー選定のポイント | SlideShare
  - https://www.slideshare.net/masatoshitada7/java-or-jsug
- Spring Boot アプリケーションプロパティ設定一覧 - Spring リファレンス
  - https://spring.pleiades.io/spring-boot/docs/current/reference/html/appendix-application-properties.html
- SpringBootとPostgreSQLの開発環境をdocker-composeで用意する！上 | Qiita
  - https://qiita.com/gosutesu/items/d2fe4811f4290ad01c4b
- SpringBootとPostgreSQLの開発環境をdocker-composeだけで用意する！下 | Qiita
  - https://qiita.com/gosutesu/items/f45150cbde3f035c54dd
- VSCodeとDockerでSpring Boot + PostgreSQL開発環境を作る(1) | Sales8開発者日記
  - https://ameblo.jp/kazusa-g/entry-12535018096.html
- VSCodeとDockerでSpring Boot + PostgreSQL開発環境を作る(2) | Sales8開発者日記
  - https://ameblo.jp/kazusa-g/entry-12536838291.html
- SpringBootに入門する為の助走本（随時更新） | Qiita
  - https://qiita.com/sugaryo/items/5695bfcc21365f429767
- 今更ながらSpring Data JPAに入門してみた | Qiita
  - https://qiita.com/shukawam/items/6e379df031dccebddd36
- Spring Boot with Docker な開発環境を考える | tiqwablog
  - https://blog.tiqwab.com/2017/03/21/docker-java.html
- 【Spring Boot入門（5）】RestAPI(POST)を作ってみる | 釣りキチエンジニアのブログ
  - https://poppingcarp.com/spring-boot_intro_rest_post/
- Spring MVCのコントローラでの戻り値いろいろ | Qiita
  - https://qiita.com/tag1216/items/3680b92cf96eb5a170f0
- @GeneratedValueを使って主キーを生成する方法 | Qiita
  - https://qiita.com/KevinFQ/items/a6d92ec7b32911e50ffe
- 【Spring】@Autowired と @Component を使用した DI の基本 | 山崎屋の技術メモ
  - https://www.shookuro.com/entry/2016/08/09/175801

## Spring Data REST Reference sources
- Java + Spring Boot + PostgreSQL + Spring Data REST でREST API | 北山淳也 | zenn
  - https://zenn.dev/junki555/articles/509003681bde8b
- Spring JPA Data with REST と Lombokで恐ろしく簡単にREST APIを作成する。 | Qiita
  - https://qiita.com/ukiuni@github/items/fb46680146c4cc8b5187
- Spring Data RESTでのHTTPエンドポイントのカスタマイズ
  - https://www.codeflow.site/ja/article/spring-data-rest-customize-http-endpoints
- Spring Boot with Docker な開発環境を考える | tiqwablog
  - https://blog.tiqwab.com/2017/03/21/docker-java.html
- Tutorial | React.js and Spring Data REST | Spring
  - https://spring.io/guides/tutorials/react-and-spring-data-rest/
- Spring BootでSpring Data RESTを試す | abcdefg.....
  - http://pppurple.hatenablog.com/entry/2017/03/06/221334
- PostgreSQL＋JPAのIDカラムで「relation "hibernate_sequence" does not exist」となったときの対処 | Qiita
  - https://qiita.com/phonypianist/items/07ce9dad37785c7cb892
- sql - ERROR: permission denied for sequence cities_id_seq using Postgres | Stack Overflow
  - https://stackoverflow.com/questions/9325017/error-permission-denied-for-sequence-cities-id-seq-using-postgres
