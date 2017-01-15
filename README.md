# Spring-security-basic

## How to use

* Mavenをインストールして以下のコマンド：

```
$ mvn install
```

* ローカルでの起動テスト
* ローカルにRedisを用意して `REDIS_HOST` `REDIS_PORT` の環境変数をそれぞれ指定してください

```
$ mvn jetty:run
$ REDIS_HOST=localhost REDIS_PORT=6379 mvn install jetty:run
```


## Heroku

* heroku-toolbeltをインストールして以下のコマンド：

```
$ heroku deploy:war --war target/sec.war --app ${application-id}
```
