**PRT(Peer Review Template)**
> written by 제민욱 

VScode 로컬 세팅을 하시면서, 여러 이슈들이 생겼고 이를 해결하는 과정에서 아쉽게도 프로젝트에 많은 시간을 할당하지 못했던 것 같습니다.
개인적으로 환경 세팅이 정말 힘들었는데, 환경세팅의 벽을 꼭 이겨내셨으면 좋겠습니다.😭😭

- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부


- [ ]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [ ]  모델 선정 이유
    - [ ]  Metrics 선정 이유
    - [ ]  Loss 선정 이유


- [ ]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [ ]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [ ]  각 실험을 시각화하여 비교하였나요?
    - [ ]  모든 실험 결과가 기록되었나요?

- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [x]  배운 점
    - [x]  아쉬운 점
    - [x]  느낀 점
    - [x]  어려웠던 점

<img width="743" alt="Screenshot 2024-06-12 at 5 34 19 PM" src="https://github.com/minkj1992/aiffel/assets/37536298/cbe4a808-7f0c-4691-8711-104b2f02f655">

비록 세팅을 완벽히 끝내진 못하였지만, 앞으로 있을 프로젝트에서 필요한 작업들인 것 같아요, 개인적으로는 conda로 하는게 가장 의존성 에러가 발생하지 않아서 추천드립니다.
또한 vscode를 사용하신다면 extension들도 잘 활용하면 좋을 것 같습니다. 🔥🔥

- [vscode extension 노마드 코드 추천](https://www.youtube.com/watch?v=ya78lQi5vVI)
- [Best python vscode extension](https://dev.to/bobbyiliev/7-best-vs-code-extensions-for-python-developers-4e9d)

아래는 맥북에서 conda 세팅하는 방법입니다. (만약 conda 사용하신다면 poetry, pyenv 사용하는 글은 읽지 않으셔도 됩니다.)

1. [Mac에서 아나콘다 + vscode 세팅하기 영상](https://www.youtube.com/watch?v=0Hhqf8L-b_0)
2. [Install](https://docs.conda.io/projects/conda/en/stable/) 사이트에서 macos로 다운받으면 되요
3. [Start Conda](https://docs.conda.io/projects/conda/en/stable/user-guide/getting-started.html)
