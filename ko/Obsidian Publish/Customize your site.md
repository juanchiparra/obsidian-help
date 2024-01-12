이 페이지에서는 [[Introduction to Obsidian Publish|Obsidian Publish]] 사이트의 모양과 느낌을 사용자 정의하는 방법을 설명합니다.

## Static assets

다음 파일을 사이트에 [[Publish and unpublish notes#Publish notes|출판]]하여 사이트를 사용자 정의할 수 있습니다:

- `publish.css`를 추가하여 사용자 정의 CSS를 적용
- `publish.js`를 추가하여 사용자 정의 JavaScript를 적용
- `favicon-32x32.png`를 추가하여 파비콘(favicon) 설정

**참고:**

- Obsidian은 CSS 또는 JavaScript 파일을 지원하지 않으므로 다른 응용 프로그램을 사용하여 이러한 파일을 만들고 편집해야 합니다.
- `publish.css` 및 `publish.js` 모두 보관소의 루트 디렉터리(`/`)에 있어야 합니다.
- 기본적으로 `publish.css` 및 `publish.js`는 파일 탐색기에 표시되지 않지만 **변경 사항 출판** 대화 상자에서 여전히 출판할 수 있습니다.
- `publish.js`와 사용자 정의 JavaScript를 사용하려면 [[Set up a custom domain|사용자 정의 도메인 설정]]이 필요합니다.

파비콘의 경우, Obsidian Publish는 다음과 같은 네이밍 규칙을 지원합니다. 여기서 `32`는 픽셀 단위의 아이콘 크기입니다:

- `favicon-32.png`
- `favicon-32x32.png`
- `favicon.ico`

다음과 같은 크기 중 하나 이상을 제공하는 것이 좋습니다:

- `favicon-32x32.png`
- `favicon-128x128.png`
- `favicon-152x152.png`
- `favicon-167x167.png`
- `favicon-180x180.png`
- `favicon-192x192.png`
- `favicon-196x196.png`

## Use a community theme

사이트에 커뮤니티 테마 중 하나를 사용하려면:

1. 기본 파일 탐색기에서 보관소를 엽니다.
2. 보관소 설정 폴더(default: `.obsidian`)로 이동합니다.
3. `themes` 폴더로 이동합니다.
4. 사용하려는 사이트를 위한 테마의 CSS 파일을 복사합니다.
5. 파일을 보관소 폴더에 붙여넣습니다.
6. 파일의 이름을 `publish.css`로 바꿉니다.
7. `publish.css`를 [[Publish and unpublish notes#Publish notes|출판]]합니다.

**참고:**

- 스타일이 몇 분 안에 변경되지 않는 경우 브라우저 캐시를 새로 고침해야 할 수 있습니다.
- [[Manage sites#View site options|사이트 옵션]]에서 라이트 모드와 다크 모드를 전환할 수 있습니다.

> [!tip] 테마 개발
> 원하는 테마를 찾지 못하십니까? 직접 [Publish 테마 만들기](https://docs.obsidian.md/Themes/Obsidian+Publish+themes/Build+a+Publish+theme) 방법을 배워보세요.

## Enable UI features

사이트의 몇 가지 UI 기능을 토글할 수 있으며, 그 중에는 그래프 뷰나 목차도 포함됩니다.

[[Manage sites#View site options|사이트 옵션]]의 **Reading experience** 및 **Components** 섹션에서 사용 가능한 UI 기능을 찾아보세요.

### Customize navigation

Obsidian Publish에서는 [[File explorer|파일 탐색기]]로 발행된 파일 및 폴더의 내비게이션 순서와 표시를 사용자 정의할 수 있습니다. 기본적으로 내비게이션 항목은 출판 순서대로 나열됩니다. 출판되지 않은 노트는 이 패널에 나타나지 않습니다.

#### Accessing Customize navigation options

1. 애플리케이션 창 왼쪽에 있는 리본에서 **변경 사항 출판** (종이 비행기 아이콘)를 선택합니다.
2. **변경 사항 출판** 대화 상자에서 **사이트 옵션 변경** (톱니바퀴 아이콘)을 선택합니다.
3. **구성 요소 설정** 아래에서 **내비게이션 사용자 정의** 옆에 **관리** 버튼을 선택합니다.

**내비게이션**이라고 표시된 새 팝업 창이 **사이트 옵션 변경** 창 위에 나타납니다.

#### Adjust navigation items

**내비게이션 미리 보기** 섹션에서 출판된 콘텐츠의 표시 순서를 조정할 수 있습니다.

1. 조정하려는 폴더나 노트를 선택합니다.
2. 노트나 폴더를 원하는 위치로 올리거나 내립니다.
3. **내비게이션** 창의 오른쪽 하단에서 **완료**를 선택합니다.

출판는 내비게이션 변경 사항을 사이트로 보냅니다.

#### Hide and unhide navigation items

만약 출판한 노트나 폴더가 있지만 내비게이션에서 보이기를 원치 않는 경우, 그 항목을 숨기도록 선택할 수 있습니다.

1. 조정하려는 폴더나 노트를 선택합니다.
2. 마우스 오른쪽 단추를 클릭하고 **내비게이션에서 숨기기**를 선택합니다. 항목은 이제 **내비게이션 미리 보기**에서 사라집니다.
3. **내비게이션** 창의 오른쪽 하단에서 **완료**를 선택합니다.

출판은 내비게이션 변경 사항을 사이트로 보냅니다.

> [!tip] **내비게이션 미리 보기** 제목 오른쪽의 확인란을 선택하여 숨겨진 파일을 표시할 수 있습니다.

#### FAQ

> [!question]- Q1. **내비게이션** 내에서 파일을 한 폴더에서 다른 폴더로 옮길 수 있을까요?
> 아니요.
> 
> 폴더 내의 노트에 대한 파일 내비게이션 구조를 유지해야 합니다. 노트 내의 순서를 조정할 수 있지만 (보관소 루트 포함), 다른 폴더 내에서 폴더 순서를 조정할 수 있습니다.

> [!question]- Q2. **완료**를 선택하기 전에 여러 노트 및 폴더의 순서를 편집할 수 있을까요?
> 네!

> [!question]- Q3. 이러한 변경 사항을 되돌리려면 어떻게 해야 하나요?
> **표시 순서**: **내비게이션 항목 표시 순서** 옆의 **기본값 복원** 아이콘 (반시계 방향 회전 화살표)를 선택하면 내비게이션 항목이 알파벳 순으로 복원됩니다.
>
> **숨김 상태**: **내비게이션에서 페이지 또는 폴더 숨김** 옆의 **기본값 복원** 아이콘 (반시계 방향 회전 화살표)를 선택하면 숨겨진 내비게이션 항목이 복원됩니다.