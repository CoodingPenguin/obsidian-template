<div align="center">
    <img alt="logo" src="./logo.png"  width="128" height="128" />
    <h1>Obsidian Template</h1>
    <p>내가 사용하는 Obsidian 설정 및 템플릿 모음</p>
</div>

## 💭 Obsidian이란?

[Obsidian](https://obsidian.md/)은 마크다운 문법으로 글을 작성할 수 있는 크로스 플랫폼 노트 앱입니다. Obsidian은 처음 사용하신다면 [15분만에 훑어보는 옵시디언 사용법](https://www.youtube.com/watch?v=ZuEu8SDqHOE)에서 간단한 사용법을 익힐 수 있습니다!

## 📌 목차

- [⚙️ 설정](#️-설정)
  - [옵션 변경하기](#옵션-변경하기)
  - [플러그인 설치하기](#플러그인-설치하기)
- [📋 템플릿](#-템플릿)
- [📚 부록](#-부록)
  - [PARA(Project, Area, Resource, Archive)](#paraproject-area-resource-archive)
  - [Obsidian 커뮤니티](#obsidian-커뮤니티)
  - [Notion 대체 가능 여부](#notion-대체-가능-여부)
- [💡 꿀팁](#-꿀팁)


## ⚙️ 설정

### 옵션 변경하기

#### 편집기

- **새 탭을 위한 기본 화면**: 편집 화면 → 읽기 화면
- **행 번호 표시**: 끄기 → 켜기

#### 파일 및 링크

- **삭제된 파일**: 시스템 휴지통으로 이동 → Obsidian 휴지통(.trash 폴더)으로 이동
- **내부 링크를 항상 업데이트**: 켜기
- **새 노트를 만들 위치**: 보관소의 최상위 폴더 → 아래에 지정된 폴더
  - 지정 폴더로 보관함으로 사용할 폴더로 지정해주세요. (ex. 보관함)
- **모든 파일 확장명 인식**: 켜기
- **새 첨부 파일을 만들 위치**: 보관소의 최상위 폴더 → 아래에 지정된 폴더
  - 첨부 파일을 저장할 폴더로 지정해주세요. (ex. 자료/이미지)

#### 테마

- **테마**: [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin)로 지정
  - 적용 방법은 [AnuPpuccin 옵시디언 테마: 최고의 디자인과 다양한 옵션](https://anpigon.tistory.com/332)을 참고해주세요.
  - 2023년 11월 이후로 업데이트가 진행되지 않아 언제든지 이슈가 생길 수 있습니다.
- **글꼴**: 인터페이스 글꼴, 텍스크 글꼴은 [Pretandard Variable](https://github.com/orioncactus/pretendard)로, 모노스페이스 글꼴은 Monaco로 설정
- **CSS 스니펫**: `vault/.obsidian/snippets` 경로에 2개 스니팻을 추가
  - [custom-separator.css](https://github.com/replete/obsidian-minimal-theme-css-snippets/blob/main/%5Bui%5D%20Custom%20Separators.css): 사이드바 폴더 사이에 구분자를 추가합니다.
  - [extended-colorschemes.css](https://github.com/AnubisNekhet/AnuPpuccin/blob/main/snippets/extended-colorschemes.css): 기본 테마 외 [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin)에서 제공하는 테마를 추가합니다.

#### 코어 플러그인

- **단어 개수**: 켜기 → 끄기
  - 커뮤니티 플러그인인 [Better Word Count](https://github.com/lukeleppan/better-word-count)로 대체합니다.

#### 데일리 노트

- **날짜 형식**: "YYYY-MM-DD [업무일지]"로 지정
- **새 파일 경로**: "업무일지"로 지정
- **템플릿 파일 경로**: "자료/템플릿/업무일지 템플릿"으로 지정

#### 백링크

- **문서 내 백링크**: 켜기

#### 템플릿

- **템플릿 폴더 경로**: "자료/템플릿"
- **시간 서식**: "YYYY-MM-DDTHH:mm:ss"

#### 코어 플러그인

- **슬래시 명령어**: 켜기
- **Properties view**: 켜기

#### 커뮤니티 플러그인

"커뮤니티 플러그인 사용"을 허용해주세요.

![커뮤니티 플러그인 허용](./img/community-plugin-allowment.png)

### 플러그인 설치하기

<table>
    <thead>
        <tr>
            <th width="22%">플러그인</th>
            <th width="8%" align="center">필수</th>
            <th width="40%">사용 이유</th>
            <th width="30%">비고</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://github.com/lukeleppan/better-word-count">Better Word Count</a></td>
            <td align="center">❌</td>
            <td>문서의 단어 개수 뿐만 아니라 드래그 영역의 단어 개수를 표시</td>
            <td>코어 플러그인 단어 개수 끄기</td>
        </tr>
        <tr>
            <td><a href="https://github.com/liamcain/obsidian-calendar-plugin">Calendar</a></td>
            <td align="center">🟢</td>
            <td>캘린더 인터페이스 및 특정 날짜의 데일리 노트 생성 기능 제공</td>
            <td>마지막 업데이트 3년 전</td>
        </tr>
        <tr>
            <td><a href="https://github.com/SebastianMC/obsidian-custom-sort">Custom File Explorer Sorting</a></td>
            <td align="center">🟢</td>
            <td>사이드바 폴더와 파일을 마음대로 정렬</td>
            <td></td>
        </tr>
        <tr>
            <td><a href="https://github.com/blacksmithgu/obsidian-dataview">Dataview</a></td>
            <td align="center">🟢</td>
            <td>vault를 데이터베이스처럼 쿼리할 수 있고 JavaScript API를 제공함</td>
            <td></td>
        </tr>
        <tr>
            <td><a href="https://github.com/ozntel/file-explorer-note-count">File Explorer Note Count</a></td>
            <td align="center">❌</td>
            <td>사이드바 폴더에 자료 개수를 표시</td>
            <td>마지막 업데이트 1년 전</td>
        </tr>
        <tr>
            <td><a href="https://github.com/LostPaul/obsidian-folder-notes">Folder Notes</a></td>
            <td align="center">🟢</td>
            <td>폴더에 인덱스 파일을 생성할 수 있음</td>
            <td>xpgo의 Folder Note는 더이상 개발되지 않아 이 플러그인으로 설치</td>
        </tr>
        <tr>
            <td><a href="https://github.com/denolehov/obsidian-git">Git</a></td>
            <td align="center">❌</td>
            <td>Git을 사용한 싱크 기능 제공</td>
            <td></td>
        </tr>
        <tr>
            <td><a href="https://github.com/reorx/obsidian-paste-image-rename">Paste Image Rename</a></td>
            <td align="center">❌</td>
            <td>이미지를 복사 붙여넣기 할 때 이름을 수정할 수 있는 다이얼로그 제공</td>
            <td></td>
        </tr>
        <tr>
            <td><a href="https://github.com/mgmeyers/obsidian-style-settings">Style Settings</a></td>
            <td align="center">❌</td>
            <td>CSS 스니펫의 설정을 쉽게 변경할 수 있는 인터페이스 제공</td>
            <td><a href="https://github.com/AnubisNekhet/AnuPpuccin">AnuPpuccin</a>에서 제공하는 추가 설정 수정 시 필요</td>
        </tr>
        <tr>
            <td><a href="https://github.com/pjeby/tag-wrangler">Tag Wrangler</a></td>
            <td align="center">❌</td>
            <td>별도 패널에서 태그 이름 수정, 병합, 검색 기능 제공</td>
            <td></td>
        </tr>
        <tr>
            <td><a href="https://github.com/SilentVoid13/Templater">Templater</a></td>
            <td align="center">🟢</td>
            <td>개선된 템플릿 기능 제공</td>
            <td></td>
        </tr>
    </tbody>
</table>

#### Dataview

- **Enable Inline Queries**: 켜기

#### Folder Notes

- **File Explorer > Underline the name of folder notes**: 끄기

#### Paste Image Rename

- **Image name pattern**: `{{DATE:YYYY-MM-DD}}

#### Style Settings

- **AnuPpuccin > File Editor & Markdown Elements**
  - **Callouts > Callout Style**: Default → Sleek
  - **Checkboxes > Enable Custom Checkboxes**: 켜기
  - **Checkboxes > Enable Speech Bubbles**: 켜기
  - **Tables > Enable Table Styling**: 켜기
  - **Tables > Enable Custom Table Width**: 켜기
  - **Tables > Center Tables**: 켜기
  - **Tables > `<th>` Highlight**: 켜기
  - **Tables > `<td>` Highlight**: None → Alternative Rows
  - **Tables > `<td>` Text Align**: Center → Left
- **AnuPpuccin > Typography**
  - **Headings > Enable Custom Heading Colors**: 켜기
- **AnuPpuccin > Workspace**
  - **File Browser > Enable file icons**: 켜기
  - **File Borswer > Enable floating vault title**: 켜기
  - **File Browser > Enable folder icons for collapse indicators**: 켜기  
  - **Rainbow Folders > Rainbow style**: None → Simple
  - **Rainbow Folders > Simple Folder Settings > Enable title recolor**: 켜기
  - **Rainbow Folders > Simple Folder Settings > Enable icon recolor (For icon folder users)**: 켜기
  - **Rainbow Folders > Simple Folder Settings > Enable collapse indent recolor**: 켜기
  - **Rainbow Folders > Simple Folder Settings > Enable collapse indicator**: 켜기
  - **Rainbow Folders > Simple Folder Settings > Enable subfolder color inheritance**: 켜기
  - **Workout Layout > Background fix for applying colors**: 켜기
- **AnuPpuccin Themes Extended**
  - **Toggle extended light theme**: 켜기
  - **Toggle extended dark theme**: 켜기
  - **Light theme flavor**: Nord → Notion
  - **Dark theme flavor**: Nord → Dark(Generic)

#### Templater

- **Template folder location**: "자료/ 템플릿"
- **Trigger Templater on new file creation**: 켜기

## 📋 템플릿

- **보관함**: 노트가 새로 생성되는 폴더로 Inbox 기능과 동일
- **메모장**: 공부하면서 참고한 자료 링크를 스크랩하는 폴더
- **업무일지**: 오늘 업무를 계획, 기록, 회고하는 폴더
    - [한달차 쭈니어의 업무일지 작성](https://velog.io/@nibble/%ED%95%9C%EB%8B%AC%EC%B0%A8-%EC%AD%88%EB%8B%88%EC%96%B4%EC%9D%98-%EC%97%85%EB%AC%B4%EC%9D%BC%EC%A7%80-%EC%9E%91%EC%84%B1)의 템플릿을 참고했습니다.
- **프로젝트**: Jira와 비슷하게 이슈 상태를 관리, 기록하고 프로젝트별 회의록을 저장하기 위한 폴더
- **주간회의, 기타회의**: 주간회의, 스터디, 기술세션 등을 정리하는 폴더
- **자료**: 이미지, 문서 자료, 커뮤니티 플러그인 설정 파일을 저장하는 폴더

## 💡 꿀팁

- **개발자 도구 켜기**: `⌘ + ⌥ + I`
- **샌드박스 vault 생성하기**: 도움말 > 샌드박스 보관소
    - 휘발성이라 저장이 필요한 경우 작업한 내용을 옮겨주세요.
- **리본 메뉴 변경하기**: 테마 > 리본 메뉴 > 관리

## 📚 부록

### PARA(Project, Area, Resource, Archive)

- [PARA Method(노트 관리법) 옵시디언 적용 및 후기](https://alive-wong.tistory.com/53)
- [해리의 미코시](https://www.harrymikoshi.com/vault/note/5d3dba80-2a20-11ed-a908-6bd771176436)

### Obsidian 커뮤니티

- [Obsidian 옵시디언 사용자 모임 네이버 카페](https://cafe.naver.com/obsidianary)
- [Obsidian 옵시디언 사용자 모임 카카오톡 오픈채팅](https://open.kakao.com/o/gSwzeNAd)

### Notion 대체 가능 여부

- [[Notion Migration] 노션에서 넘어오시는 분들을 위한, 차이점과 대안](https://cafe.naver.com/obsidianary/9863)
