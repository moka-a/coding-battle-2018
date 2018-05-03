# Coding Battle 2018, 패스파인더

개발제한구역의 첫번째 코딩배틀 게임인 패스파인더입니다.

## 참가자 및 개발환경

- wan2land (GM)
- albireo770 : Golang, `go version go1.9.4 darwin/amd64`
- imsukmin : Nodejs, `v9.6.1`
- lastone9182 : Python, `Python 3.6.4`
- sjjeong : Kotlin 1.2.4 `Kotlin version 1.2.41-release-74 (JRE 1.8.0_101-b13)`

## 언어별 개발환경 설정하기

언어에 상관없이 모두 2개의 파일은 반드시 설정이 되어있어야 합니다.

1. Makefile
2. entry.sh

1번 파일을 통해서 빌드를 진행하고, 2번파일을 통해 프로그램을 실행합니다. 이 양식에만 맞춘다면 어떠한 프로그래밍언어도 실행할 수 있습니다. 미리 준비되어있는 파일을 참고하시기 바랍니다.

모든 변수는 entry.sh 파일을 통해서 입력됩니다. 그리고 해당 프로그램은 단한번 실행되고 종료되도록 해야합니다.
즉, stateless 하도록 프로그램을 작성해야하며, state를 필요로 하는 경우 각자 알아서 파일처리로 하시기 바랍니다. [....]

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
