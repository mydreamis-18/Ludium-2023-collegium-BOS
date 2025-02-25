## Mission
아래 DeFi 애플리케이션을 구현해주세요.
- 위젯: `idknwhoru.near/widget/collegium.bos.wk2.LiquityOpenTroveSepoliaExample`
- 추가 요청 사항은 다음과 같습니다. 
    - [x] `openTrove`가 성공한 지갑은 `closeTrove`가 실행되기 전까지 `이 지갑은 이미 활성화된 트로브가 있습니다.` 메세지를 표시해주세요.
        - hint 1: 이미 활성화된 트로브를 알아 낼 수 있는 방법은 `state.isOpenTrove === true` 입니다.
          ![bos_2주차_과제_1번](./bos_2주차_과제_1번.png)
    - [x] `borrowWrapper` 컴포넌트의 스타일을 외부 css파일을 불러와서 적용해보세요.
        - hint 1: [fetch API](https://docs.near.org/bos/api/fetch)를 사용하세요.
        - hint 2: `https://raw.githubusercontent.com/LudiumAgwn/collegium-bos-wk2/main/assets/code/liquity-widget.css`를 불러와주세요.
          ![bos_2주차_과제_2번](./bos_2주차_과제_2번.png)
    - [x] `openTrove` 기능의 가스 비용을 최적화 하기 위해 NICR이라는 값을 계산해야 합니다. openTrove 함수에 NICR을 계산하는 기능을 추가해주세요.
        - NICR = Ether / LUSD * 100
        - hint 1: [ethers.js](https://docs.near.org/bos/tutorial/ethers-js) api 기능을 사용해서 계산해주세요
        - hint 2: hint 1의 자료가 부족할 경우 [이 문서](https://docs.ethers.org/v5/)를 참고해주세요.
          ![bos_2주차_과제_3번](./bos_2주차_과제_3번.png)

- 배포한 bos 컴포넌트 링크: https://near.org/near/widget/ComponentDetailsPage?src=6adbe3aca46fef824ed95c24b625c18fd7c6d978ff713ea11a22cd5b028940f2/widget/collegium.bos.wk2.LiquityOpenTroveSepoliaExample
- [결과물 확인 안내](https://github.com/LudiumAgwn/collegium-bos-wk2/tree/mission_result)
