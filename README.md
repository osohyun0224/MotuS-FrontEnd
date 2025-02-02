<div align="center">
    <img width="720px" src="https://github.com/MotuS-Web/MotuS-FrontEnd/assets/35104213/f138f900-a288-49ec-ae92-ee70525beb36" />
    <br/>
    <h2>MotuS ─ 비대면 운동 학습 플랫폼<br/>Frontend Repository</h2>
</div>

### [Check FrontEnd README.md in English](https://github.com/MotuS-Web/MotuS-FrontEnd/blob/master/README-ENG.md)

---

## 🔥 Main Contributor

|                                      오소현                                      |                                      김경재                                      |
| :------------------------------------------------------------------------------: | :------------------------------------------------------------------------------: |
| <img width="150px" src="https://avatars.githubusercontent.com/u/53892427?v=4" /> | <img width="150px" src="https://avatars.githubusercontent.com/u/35104213?v=4" /> |
|                                    한림대학교                                    |                                    한림대학교                                    |
|                                빅데이터전공 4학년                                |                                빅데이터전공 2학년                                |
|                  [@osohyun0224](https://github.com/osohyun0224)                  |                   [@PortalCube](https://github.com/PortalCube)                   |

## 🧑🏻‍💻 How to Setup

1. 리포지토리를 클론하고 클론한 디렉토리에 들어갑니다.

```bash
git clone https://github.com/MotuS-Web/MotuS-FrontEnd
cd MotuS-FrontEnd
```

2. .env 파일을 열고 임시 값을 모두 지운 다음, 미리 세팅한 Spring 서비스와 AI 서비스 URL을 입력합니다.

```env
VITE_SPRING_URL=[Spring 서비스의 URL]
VITE_AI_URL=[AI 서비스의 URL]
```

3. Node 18 이상을 준비한 다음, 다음의 명령어를 실행하여 개발 서버를 엽니다.

```javascript
npm install
npm start build
npm run dev
```

주의: 본 레포지토리를 Production으로 배포하려는 경우, 사용자의 웹캠에 접근할 수 있도록 반드시 HTTPS 환경으로 배포하시기 바랍니다.

## 📚 Libraries

|     **Stack**     |            **Version**            |                                                                                                             **Why**                                                                                                             |
| :---------------: | :-------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|       React       |             `18.2.0`              |                     많은 사용자들이 오랜 기간동안 사용하여 다른 프레임워크에 비해 오픈 소스 생태계가 활발하며, <br/> 컴포넌트 단위로 분리하여 개발을 할 수 있어 분업하기 좋고 생산성이 탁월하기 때문에 도입                     |
|       Redux       |              `8.1.2`              | 모든 상태 업데이트를 액션으로 정의하고, <br/> 액션 정보에 기반하여 Reducer에서 상태를 업데이트하기 때문에 <br/> 상태를 더욱 쉽게 예측 가능하게 하여 유지보수 측면에 긍정적인 효과가 있어 <br/> 상태 관리를 하는 컨테이너로 채택 |
| @reduxjs/toolkit  |              `1.9.5`              |      Redux를 사용하면서 생기는 boilerplate 코드를 줄이고, <br/> Redux 코드 작성에 필요한 도구와 헬퍼를 갖추기 위함. <br/> 또한 불변성을 유지하면서 상태 업데이트를 간소화하고, <br/> 비동기 작업을 쉽게 관리하기 위해 도입      |
| Styled-Components |              `6.0.6`              |                                                                                        스타일 작성의 생산성 향상을 위하여 CSS-in-JS 도입                                                                                        |
|       axios       |              `1.5.0`              |                                                                                                  API 통신에 사용하기 위해 도입                                                                                                  |
|      Vercel       | [Link](motus-frontend.vercel.app) |                                 다른 개발 팀과의 협업 시 프론트 개발 현황을 vercel로 호스팅한 것으로 확인이 가능해 이해를 도움. <br/> 또한 빌드 도구로 활용해 개발시 오류를 바로 확인이 가능함.                                 |

## 💡 Contribution

MotuS 프론트엔드 레포지토리에 기여해주셔서 감사합니다! Contribution 가이드는 [CONTRIBUTING.md](CONTRIBUTING.md)에서 확인해주세요.
