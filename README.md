# 볼링 게임 점수판
## 진행 방법
* 볼링 게임 점수판 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## 기능구현 목록
* 프레임 생성
  * 1구 플레이까지 쓰러뜨린 핀 수 계산
  * 2구 플레이까지 쓰러뜨린 핀 수 계산
  * 이전 프레임 추가점수 구하기
    * spare 시, 추가 점수 계산
    * strike 시, 추가 점수 계산
  * 점수 계산
* 결과체크
  * 1구에 모두 쓰러뜨리면 strike
  * 2구에 모두 쓰러뜨리면 spare
  * 그렇지 않으면 miss
* 10프레임까지 진행되는 볼링을 생성
* 첫 투구수를 받아서 스트라이크인지 판단
* 두번째 투구수를 받아서 스페어인지 미스인지 판단
* 10번 프레임 스타라이크 또는 스페어 처리 시, 투구수를 하나 추가
