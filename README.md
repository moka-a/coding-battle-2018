# Coding Battle 2018

## 참가자 및 개발환경

- albireo770 : Golang
- imsukmin : node 적당한 버전
- lastone9182 : python 3.6
- sjjeong : Kotlin 1.2.4
- wan2land (GM)

## 개발환경 테스트 실행하기

모든 프로세서 실행은 typescript를 통해서 이루어집니다. 패키지 버전 고정을 위해 yarn.lock파일을 사용중입니다.
따라서, 패키지 매니저는 yarn을 사용하는게 좋습니다.

```bash
yarn install
yarn test
```

테스트에서는 매개변수로 1, 2, 3의 배열을 전달하고, 테스트용 프로그램은 이 3개의 값을 sum 한 결과를 담고 있습니다.
따라서 1 + 2 + 3의 결과인 6이 출력되며, 위 커맨드의 결과로서 다음과 같이 출력됩니다.

```
build complete!
[ '6', '6', '6', '6' ]
process complete!
```
