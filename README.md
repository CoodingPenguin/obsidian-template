<div align="center">
    <img alt="logo" src="./logo.png"  width="128" height="128" />
    <h1>Obsidian Template</h1>
    <p>내가 사용하는 Obsidian 설정 및 템플릿 모음</p>
</div>

## 🚀 시작하기

[Obsidian](https://obsidian.md/)은 마크다운 문법으로 글을 작성할 수 있는 크로스 플랫폼 노트 앱입니다. Obsidian은 처음 사용하신다면 [15분만에 훑어보는 옵시디언 사용법 - 생산성 빌리언 시안](https://www.youtube.com/watch?v=ZuEu8SDqHOE)에서 간단한 사용법을 익힐 수 있습니다!

### 옵션 변경하기

#### 편집기 > 행 번호 표시

> 끄기 → 켜기

#### 파일 및 링크 > 삭제된 파일

> 시스템 휴지통으로 이동 → Obsidian 휴지통(.trash 폴더)으로 이동

#### 파일 및 링크 > 내부 링크를 항상 업데이트

> 끄기 → 켜기

#### 파일 및 링크 > 새 노트를 만들 위치

> 보관소의 최상위 폴더 → 아래에 지정된 폴더

- 지정 폴더로 보관함으로 사용할 폴더로 지정해주세요. (ex. 보관함)

#### 파일 및 링크 > 모든 파일 확장명 인식

> 끄기 → 켜기

#### 파일 및 링크 > 새 첨부 파일을 만들 위치

> 보관소의 최상위 폴더 → 아래에 지정된 폴더

- 첨부 파일을 저장할 폴더로 지정해주세요. (ex. 자료/이미지)

#### 테마 > 테마

Obsidian 테마로 [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin)을 사용하고 있습니다.

AnuPpuccin 적용 방법은 [AnuPpuccin 옵시디언 테마: 최고의 디자인과 다양한 옵션 - 안피곤 성장블로그](https://anpigon.tistory.com/332)을 참고해주세요!

![AnuPpuccin Notion 다크 모드 테마](https://raw.githubusercontent.com/AnubisNekhet/AnuPpuccin/main/assets/colorschemes/notion-dark.webp)

> [!CAUTION]
> 2023년 11월 이후로 더이상의 업데이트가 없어 언제든지 이슈가 생길 수 있습니다.

#### 테마 > 글꼴

- 인터페이스 글꼴: [Pretandard Variable](https://github.com/orioncactus/pretendard)
- 텍스트 글꼴: [Pretandard Variable](https://github.com/orioncactus/pretendard)
- 모노스페이스 글꼴: Monaco

#### 테마 > CSS 스니펫

폴더 경로 `vault/.obsidian/snippets` 에 다음 CSS 파일을 추가해주세요.

##### custom-separators.css

사이드바 폴더 사이에 구분선을 추가합니다.

```css
/*
    File Explorer Separators
    So this is super handy, I found a way to add visual separators below and above navigation items in the file explorer. 
    This works nicely along side the 'Custom File Explorer Sorting' plugin, and there's a thread on their github about my solution.
    You need to customize the rule below in accordance with your file structure.
    These styles go with
    https://github.com/replete/obsidian-minimal-theme-css-snippets
*/
:root {
  --replete-custom-separators-vertical-padding: 6px;
  --replete-custom-separators-left-margin: -12px;
}

/* Separator below */
.nav-folder-children > [class*="nav-"]:has([data-path="보관함"])::after {
  content: "";
  display: block;
  height: 1px;
  width: calc(100% + 32px);
  background: var(--divider-color);
  margin: var(--replete-custom-separators-vertical-padding) 0 var(
      --replete-custom-separators-vertical-padding
    )
    var(--replete-custom-separators-left-margin);
}

/* Separator above */
.nav-folder-children > [class*="nav-"]:has([data-path="자료"])::before {
  content: "";
  display: block;
  height: 1px;
  width: calc(100% + 32px);
  background: var(--divider-color);
  margin: var(--replete-custom-separators-vertical-padding) 0 var(
      --replete-custom-separators-vertical-padding
    )
    var(--replete-custom-separators-left-margin);
}
```

##### extended-colorschemes.css

기본 테마 외에 제공하는 추가 테마입니다. Atom, Notion 등의 테마가 제공됩니다. [여기](https://github.com/AnubisNekhet/AnuPpuccin/blob/main/snippets/extended-colorschemes.css)에서 코드 복사 후 스니펫을 추가해주세요.

#### 커뮤니티 플러그인

"커뮤니티 플러그인 사용"을 허용해주세요.

### 플러그인 설치하기

| 플러그인 | 필수 | 사용 이유 | 비고 |
| -------- | ---- | --------- | ---- |
|          |      |           |      |

#### Better Word Count

#### Calendar

#### Contextual Typography

#### Custom File Explorer Sorting

#### Dataview

#### File Explorer Note Count

#### Folder Notes

#### Git

#### Sortable

#### Style Settings

####

## 💬 사용하기

## 📚 참고 자료
