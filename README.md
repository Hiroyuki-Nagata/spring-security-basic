# Spring-security-basic

## How to use

* Mavenをインストールして以下のコマンド：

```
$ mvn install
```

* ローカルでの起動テスト：

```
$ mvn jetty:run
```


## Heroku

* heroku-toolbeltをインストールして以下のコマンド：

```
$ heroku deploy:war --war target/sec.war --app ${application-id}
```
