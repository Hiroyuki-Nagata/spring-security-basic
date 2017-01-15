# Spring-security-basic

## How to use

* Maven���C���X�g�[�����Ĉȉ��̃R�}���h�F

```
$ mvn install
```

* ���[�J���ł̋N���e�X�g
* ���[�J����Redis��p�ӂ��� `REDIS_HOST` `REDIS_PORT` �̊��ϐ������ꂼ��w�肵�Ă�������

```
$ mvn jetty:run
$ REDIS_HOST=localhost REDIS_PORT=6379 mvn install jetty:run
```


## Heroku

* heroku-toolbelt���C���X�g�[�����Ĉȉ��̃R�}���h�F

```
$ heroku deploy:war --war target/sec.war --app ${application-id}
```
