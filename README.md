## 사용방법
이 어플리케이션을 구동하는 방법은, 일단 레포지토리를 로컬로 clone해주세요
그 다음, 아래의 커맨드를 사용하여 필요한 RubyGem을 설치해주세요.

```
$ bundle install --without production
```

그 다음, 데이터베이스를 마이그레이션해주세요

```
$ rails db:migrate
```
마지막으로, 테스트를 실행하여 제대로 동작하는지 확인해주세요.

```
$ rails test
```
테스트가 무사히 종료되었다면, Rails서버를 실행시켜주세요.

```
$ rails server
```



