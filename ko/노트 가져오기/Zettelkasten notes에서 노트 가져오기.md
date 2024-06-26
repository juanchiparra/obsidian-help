---
permalink: import/zettelkasten
---
만약 제트텔카스텐(Zettelkasten) 방식으로 노트 이름과 링크를 설정해왔다면 `[[UID]]`에서 `[[UID 노트 제목]]`으로 링크를 변환해야 할 수 있습니다.

예를 들어, `202301011230 노트 제목`이라는 이름의 노트가 있고, 이 노트를 다른 노트에서 UID만 사용하여 링크를 걸었다면 `[[202301011230]]`와 같이 링크를 설정했을 것입니다. Obsidian은 내부 링크를 해석할 때 노트의 전체 이름을 사용하므로 이러한 링크는 작동하지 않을 것입니다.

보관소 내의 모든 `[[UID]]` 링크를 노트의 전체 이름을 사용하도록 업데이트하려면 [[형식 변환기|형식 변환기]]를 사용하세요.

1. **설정**을 엽니다.
2. **코어 플러그인** 아래에서 **마크다운 형식 가져오기**를 활성화한 후 설정 창을 닫습니다.
3. 응용 프로그램 창의 왼쪽 상단에 있는 **마크다운 형식 가져오기 열기**(ones와 zeros 아이콘)를 선택합니다.
4. **Zettelkasten 링크 고치기**를 활성화합니다.
5. **변환 시작**을 선택합니다. 이렇게 하면 보관소 내의 모든 노트를 변환합니다.

> [!tip] 제트텔카스텐 링크 꾸미기(Zettelkasten link beautifier)
> [[형식 변환기|형식 변환기]]는 링크에서 표시 이름에서 UID를 제거하여 링크를 미화할 수도 있습니다. 예를 들어, `[[UID]]`가 `[[UID 노트 제목|노트 제목]]`로 변환됩니다.
> 
> Zettelkasten 링크를 아름답게 만들려면 형식 변환기 창에서 **Zettelkasten 링크 꾸미기(Zettelkasten link beautifier)** 를 활성화하세요.

또한 Obsidian에서 Zettelkasten 노트를 만드는 데 [[유니크 노트 생성자|유니크 노트 생성자]]를 사용할 수도 있습니다.
