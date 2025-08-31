<!-- README.md -->
# 보성고등학교 카드게임 멘토링 프로젝트

본 프로젝트는 보성고등학교 학생들을 위한 프로그래밍 및 게임 기획 멘토링을 목적으로 제작된 1:1 전략 카드게임입니다. 플레이어는 운과 전략, 그리고 강력한 아이템을 활용하여 상대보다 먼저 자신에게 주어진 비밀 미션을 완수해야 합니다.

## 📖 프로젝트 개요

이 게임의 핵심 목표는 **'6장으로 구성된 목표 덱을 정해진 순서까지 완벽하게 완성하는 것'** 입니다. 단순한 카드 수집을 넘어 순서까지 맞춰야 하는 전략적 깊이와, 게임의 판도를 뒤흔드는 다양한 아이템을 통해 매 순간 긴장감 넘치는 플레이를 경험할 수 있습니다.

본 리포지토리는 게임의 규칙, 아이템 목록, 그리고 기술적인 구현 방식을 상세히 설명하는 문서들로 구성되어 있습니다.

## 📚 문서 구조

*   **[게임 규칙 설명서 (GAME_RULES.md)](./GAME_RULES.md)**
    *   게임의 목표, 준비 과정, 턴의 흐름, 행동 규칙 등 게임을 플레이하기 위해 알아야 할 모든 정보를 담고 있습니다. **게임을 처음 접하는 분은 반드시 이 문서를 먼저 읽어보세요.**

*   **[아이템 전체 목록 (ITEM_LIST.md)](./ITEM_LIST.md)**
    *   게임에 등장하는 모든 공격, 방어, 유틸리티 아이템의 상세한 효과와 획득 확률을 정리한 문서입니다.

*   **[기술 명세서 (TECHNICAL_SPECIFICATION.md)](./TECHNICAL_SPECIFICATION.md)**
    *   이 게임의 개발에 사용된 기술 스택, 서버 아키텍처, 핵심 로직, 보안 정책 등을 기술한 개발 문서입니다.

## 💻 기술 스택 (Tech Stack)

*   **Backend**: Python
*   **Frontend**: HTML, CSS, JavaScript (JSX, React or a similar library implied)
*   **Server**: Direct IP Hosting with sequential game room IDs
*   **Authentication**: JWT (JSON Web Token) for game room access control

## 🚀 시작하기

게임을 이해하고 싶다면 **[게임 규칙 설명서](./GAME_RULES.md)** 부터 읽어보시는 것을 추천합니다.
