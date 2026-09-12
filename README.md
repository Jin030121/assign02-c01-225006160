Assignment 02
22500616 / 장진

W3Schools CSS Demo를 참고하여 기본 HTML 구조를 가진 웹 페이지를 제작하고 같은 HTML에 서로 다른 CSS 스타일을 적용하여 디자인 및 레이아웃 변화를 십습했습니다.

Vercel Deploy URL: https://assign02-c01-22500616-r5dz.vercel.app/
Landing Page: https://assign02-c01-22500616-r5dz.vercel.app/index.html
No Style Page: https://assign02-c01-22500616-r5dz.vercel.app/nostyle.html
Style 1 Page: https://assign02-c01-22500616-r5dz.vercel.app/style1.html
Style 2 Page: https://assign02-c01-22500616-r5dz.vercel.app/style2.html

Weekly Review – Week 2
README.md에 Weekly Review – Week 2를 작성합니다.

Key Learning: 이번 주 배운 핵심 내용 3가지
HTML vs CSS: HTML과 CSS의 역할을 자신의 말로 간단히 정리
Bootstrap 사용법 : Bootstrap 사용하는 이유 및 사용법 간단히 정리
Problem & Solution: 실습 중 발생한 문제와 해결 과정 1가지
AI Usage: AI를 어떤 부분에 활용했으며, 생성된 코드를 어떻게 확인/수정했는지 작성
Reflection: 새롭게 알게 된 점 또는 궁금한 점 1가지


Key Learning
1. HTML과 CSS 분리: 동일한 HTML 구조라도 어떤 CSS 스타일시트를 적용하느냐에 따라 전혀 다른 디자인과 레이아웃을 표현할 수 있음을 배웠습니다.
2. 주요 CSS 레이아웃 속성 활용: display(Flexbox,Block), margin, padding, border, background-color 등의 속성을 활용하여 웹 페이지 요소의 위치와 스타일을 제어하는 방법을 익혔습니다.
3. Git & GitHub 버전 관리: 파일 생성 및 수정 단계별로 git commit을 분할하며 기록하고 최종 코드를 remote repository에 push하는 과정을 더 확실하게 알 수 있게 되었습니다.

HTML vs CSS
HTML: 웹 페이지의 뼈대와 구조(제목, 본문, 링크, 리스트 등)를 정의하는 언어입니다.
CSS: HTML로 만든 뼈대에 색상, 폰트, 여백, 레이아웃 등 시각적인 스타일을 입히는 언어입니다.

Bootstrap 사용법
이번 과제에서는 Bootstrap 사용이 제외되었으나, Bootstrap은 미리 디자인된 CSS 클래스와 컴포넌트를 제공하여 빠르고 반응형인 웹 사이트를 제작할 수 있게 돕는 CSS 프레임워크임을 알게 되었습니다.

Problem & Solution
문제: W3Schools 예제와 똑같은 레이아웃을 구현할 때 display 속성과 여백 설정이 어긋나는 현상이 발생했습니다.
해결: display: flex와 gap 속성을 활용해 본문과 사이드바를 유연하게 배치하고 box-sizing: border-box를 적용하여 패딩과 테두리가 전체 폭을 넘지 않도록 조정하며 해결했습니다.

AI Usage
HTML 기본 구문 검수와 W3Schools 스타일시트의 레이아웃 분석 과정에서 AI 도구를 보조 비서로 활용했습니다. AI가 제안한 CSS 코드 중 헥사코드 색상값을 직관적인 색상 이름 lightgreen, mediumseagreen 등으로 수정하였습니다.

Reflection
동일한 뼈대를 가지고 스타일시트 교체만으로 완전히 느낌을 줄 수 있고 사용자에게도 새로운 경험을 제공할 수 있다는 점이 인상 깊었습니다. 다음에는 CSS Grid를 이용한 반응형 웹 디자인에 대해 더 깊이 배워보고 싶습니다.