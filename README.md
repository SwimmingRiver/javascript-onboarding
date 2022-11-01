# 미션 - 온보딩

## 🔍 진행 방식

- 미션은 **기능 요구 사항, 프로그래밍 요구 사항, 과제 진행 요구 사항** 세 가지로 구성되어 있다.
- 세 개의 요구 사항을 만족하기 위해 노력한다. 특히 기능을 구현하기 전에 기능 목록을 만들고, 기능 단위로 커밋 하는 방식으로 진행한다.
- 기능 요구 사항에 기재되지 않은 내용은 스스로 판단하여 구현한다.

## 📮 미션 제출 방법

- 미션 구현을 완료한 후 GitHub을 통해 제출해야 한다.
  - GitHub을 활용한 제출 방법은 [프리코스 과제 제출](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse) 문서를 참고해
    제출한다.
- GitHub에 미션을 제출한 후 [우아한테크코스 지원](https://apply.techcourse.co.kr) 사이트에 접속하여 프리코스 과제를 제출한다.
  - 자세한 방법은 [제출 가이드](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse#제출-가이드) 참고
  - **Pull Request만 보내고 지원 플랫폼에서 과제를 제출하지 않으면 최종 제출하지 않은 것으로 처리되니 주의한다.**

## 🚨 과제 제출 전 체크 리스트 - 0점 방지

- 기능 구현을 모두 정상적으로 했더라도 **요구 사항에 명시된 출력값 형식을 지키지 않을 경우 0점으로 처리**한다.
- 기능 구현을 완료한 뒤 아래 가이드에 따라 테스트를 실행했을 때 모든 테스트가 성공하는지 확인한다.
- **테스트가 실패할 경우 0점으로 처리**되므로, 반드시 확인 후 제출한다.

### 테스트 실행 가이드

- 테스트 패키지 설치를 위해 `Node.js` 버전 `14` 이상이 필요하다.
- 다음 명령어를 입력해 패키지를 설치한다.

```bash
npm install
```

- 설치가 완료되었다면, 다음 명령어를 입력해 테스트를 실행한다.

```bash
npm test
```

---

## 🚀 기능 요구 사항

아래의 7가지 기능 요구 사항을 모두 해결해야 한다.

1. [문제 1](docs/PROBLEM1.md)
  기능 목록: 1.자릿수 합과 곱의 값 구하기 2.비교할 가장 큰 값 찾기 3. 조건에 맞는 숫자인지 확인 4.비교결과에 따른 숫자반환
2. [문제 2](docs/PROBLEM2.md)
  기능 목록: 1. 입력될 암호문 조건 맞는 지 확인 2. 암호해독 알고리즘(암호문을 담은 배열을 이용해 해독하는 가는 과정을 배열에 저장하며 최종결과물은 다시 문자열로 변환)
3. [문제 3](docs/PROBLEM3.md)
  기능 목록: 1. 1부터 해당 숫자가 있는 배열 2. 조건에 맞는 숫자 판별 3. 3,6,9 를 세어주는 함수
4. [문제 4](docs/PROBLEM4.md)
  기능 목록: 1. ASCII코드로 변환하기 2. 영어 대문자 소문자 구분, 한국어 불가 기준으로 필터링하기 3. 숫자 연산으로 역순으로 ASCII 코드 불러오기
5. [문제 5](docs/PROBLEM5.md)
  기능 목록: 1. 받은 숫자를 나눠줄 기준(5만원,만원,...)을 담은 배열만들기 2. 자리수 기준으로 나눠서 배열로 반환하기
6. [문제 6](docs/PROBLEM6.md)
  기능 목록: 1.사용자 목록에서 메일과 닉네임을 구분하여 각각 다른 배열에 저장 2. 닉네임중 연속되는 두자리 중복 키워드를 저장한 배열 만들기 3. 그 배열 원소와 겹치는 메일들을 분류하여 정렬
7. [문제 7](docs/PROBLEM7.md)
  기능 목록: 1.user의 친구목록 만들기 2.친구목록의 원소의 친구들 구하기 3.방문자에서 친구들 제외하기 4.친구의 친구, 방문자 각각의 목록에 10점 ,1점 부여하기 4.부여한 점수를 기준으로 정렬 

---

## 🎯 프로그래밍 요구 사항

- Node.js 14 버전에서 실행 가능해야 한다. **Node.js 14에서 정상적으로 동작하지 않을 경우 0점 처리한다.**
- `package.json`을 변경할 수 없고 외부 라이브러리(jQuery, Lodash 등)를 사용하지 않는다. 순수 Vanilla JS로만 구현한다.
- 프로그램 종료 시 `process.exit()`를 호출하지 않는다.
- 프로그램 구현이 완료되면 `ApplicationTest`의 모든 테스트가 성공해야 한다. **테스트가 실패할 경우 0점 처리한다.**
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 이름을 수정하거나 이동하지 않는다.

---

## ✏️ 과제 진행 요구 사항

- 미션은 [javascript-onboarding](https://github.com/woowacourse-precourse/javascript-onboarding) 저장소를 Fork & Clone해 시작한다.
- 과제 진행 및 제출 방법은 [프리코스 과제 제출](https://github.com/woowacourse/woowacourse-docs/tree/master/precourse) 문서를 참고한다.
