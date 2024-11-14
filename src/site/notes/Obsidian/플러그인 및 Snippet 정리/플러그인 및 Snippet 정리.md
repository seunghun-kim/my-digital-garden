---
{"dg-publish":true,"dg-path":"Obsidian/플러그인 및 Snippet 정리.md","permalink":"/obsidian/snippet/","noteIcon":"","created":"2024-10-27T02:33:48.829+09:00","updated":"2024-11-14T13:53:56.379+09:00"}
---


> [!NOTE] 별점 기준
> ⭐⭐⭐: 필수 플러그인
> ⭐⭐: 있으면 좋은 플러그인(권장)
> ⭐: 제한적인 활용도
> ⛔: 비추천
> M: MAKE.md로 대체 가능
# 1 플러그인
## 1.1 UI
### 1.1.1 Calendar (⭐)
[플러그인 열기](obsidian://show-plugin?id=calendar)
- 캘린더 Pane을 열 수 있음
  ![|300](/img/user/Obsidian/attachments/플러그인-20241106173659903.webp)
- 날짜를 누르면 해당하는 날의 Daily Note로 이동/생성
- 옵션에서 week number를 켜면 Weekly Note 사용 가능
### 1.1.2 Bartender
WIP
### 1.1.3 Custom File Explorer Sorting (⭐⭐|M)
> [!INFO] MAKE.md
> MAKE.md 플러그인 사용 시 드래그&드롭으로 파일 순서를 원하는대로 설정할 수 있음

[플러그인 열기](obsidian://show-plugin?id=custom-sort)
- 폴더와 파일 정렬을 원하는 대로 설정할 수 있게 하는 플러그인
- 정렬 방법은 2가지 ([자세히 보기](https://kaminik.tistory.com/entry/%ED%8C%8C%EC%9D%BC%EA%B3%BC-%ED%8F%B4%EB%8D%94%EC%9D%98-%EC%88%9C%EC%84%9C%EB%A5%BC-%EB%B3%80%EA%B2%BD%ED%95%98%EB%8A%94-Custom-File-Explorer-Sorting-%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8))
	- `sortspec.md` 파일에 정렬 방법을 명시
		- `sortspec.md`가 있는 폴더와 그 하위 폴더에 적용됨
		- Folder Note 플러그인을 사용할 경우 `sortspec.md` 대신 해당 폴더의 노트에 대신 작성해도 적용됨
	- 북마크 후 북마크 내에서 순서를 변경
- 유사 플러그인: [Bartender](#1.2%20Bartender)
### 1.1.4 Folder Notes (⭐⭐|M)
> [!INFO] MAKE.md
> MAKE.md 플러그인 기본 기능

[플러그인 열기](obsidian://show-plugin?id=folder-notes)
- 기본적으로 폴더의 기능만 하는 옵시디언의 폴더 자체에 문서를 작성할 수 있게 해주는 플러그인
- 옵시디언을 노션과 비슷하게 사용 가능
### 1.1.5 Iconize (⭐|M)
> [!INFO] MAKE.md
> MAKE.md 플러그인 기본 기능

[플러그인 열기](obsidian://show-plugin?id=obsidian-icon-folder)
- 폴더와 파일 옆에 아이콘을 표시
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106192700509.webp)
### 1.1.6 Omnisearch (⭐⭐)
[플러그인 보기](obsidian://show-plugin?id=omnisearch)
- 기본 검색기능 보완
- 가중치 기반으로 연관도가 높은 검색결과를 상단에 보여줌
### 1.1.7 Style Settings
WIP
## 1.2 편집
### 1.2.1 Advanced Tables (⭐⭐⭐)
[플러그인 열기](obsidian://show-plugin?id=table-editor-obsidian)
- 표 수정을 쉽게 해주는 플러그인
- 기능
  ![|300](/img/user/Obsidian/attachments/플러그인-20241106173000516.webp)
	- Auto formatting
	- Excel-like table navigation (tab/enter between cells and rows)
	- [Spreadsheet formulas!](https://github.com/tgrosinger/advanced-tables-obsidian/blob/main/docs/help.md#using-formulas-in-markdown-tables)(배우기 어려워서 못 쓰고 있음)
	- Add, remove, and move columns and rows
	- Set column alignment (left, center, right)
	- Sort rows by a specified column
	- Export to CSV
### 1.2.2 Code Styler (⭐)
[플러그인 열기](obsidian://show-plugin?id=code-styler)
- 코드 블록을 커스터마이징할 수 있음
- 색상 테마
  ![|500](/img/user/Obsidian/attachments/플러그인-20241106174246166.webp)
- inline code block 스타일
  ![|200](/img/user/Obsidian/attachments/플러그인-20241106180457468.webp)
- 코드 블록 폴딩
- 라인 단위 하이라이팅
  ![](/img/user/Obsidian/attachments/플러그인-20241106181543385.webp)
### 1.2.3 Editing Toolbar (⭐)
[플러그인 보기](obsidian://show-plugin?id=editing-toolbar)
- 에디터 상단에 텍스트 수정 툴바를 띄워줌
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106191354969.webp)
- 유사 플러그인: [cMenu](obsidian://show-plugin?id=cmenu-plugin)
### 1.2.4 ExcaliDraw (⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-excalidraw-plugin)
- 스케칭 도구
- 기능이 많아서 플러그인 페이지에서 확인 요망
### 1.2.5 Kanban (⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-kanban)
- 문서에 칸반 뷰 추가
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106193527672.webp)
### 1.2.6 Latex Suite (⭐⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-latex-suite)
- Latex 수식 작성 지원 툴
- 수식 작성 단축어(예: `1/4` -> `\frac{1}{4}` 자동 변환됨)
- 수식 preview
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106194002397.webp)
- Syntax Highlighting
  ![|300](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106193920289.webp)
### 1.2.7 Number Headings (⭐)
[플러그인 보기](obsidian://show-plugin?id=number-headings-obsidian)
- Heading에 자동으로 번호 매김
- 본 문서처럼 레벨에 따라 `1`, `1.2`, `1.2.1`, ... 번호를 매기는 커맨드 지원
### 1.2.8 Outliner (⭐⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-outliner)
- 불릿 편집을 더 편하게 하는 플러그인
- 키보드 단축키
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106195155355.webp)
- 드래그 & 드롭
- 폴딩
### 1.2.9 Sheets Extended
WIP
## 1.3 Vault 관리
### 1.3.1 Clear Unused Images (⭐)
[플러그인 열기](obsidian://show-plugin?id=oz-clear-unused-images)
- 사용되지 않는 이미지들과 파일들을 삭제
- 이미지, 파일 삭제를 구분해서 실행할 수 있으며, 각각의 커맨드 존재
  ![](/img/user/Obsidian/attachments/플러그인-20241106174008211.webp)

> [!Warning] 주의사항
> 확인 과정 없이 바로 삭제해버리므로 사용 전 Vault를 백업해놓아야 함
### 1.3.2 Consistent Attachments and Links (⭐⭐)
[플러그인 열기](obsidian://show-plugin?id=consistent-attachments-and-links)
- Vault의 파일들을 규칙에 맞게 관리할 수 있도록 지원하는 플러그인
- **규칙을 설정하기에 따라, Obsidian이 아닌 일반적인 Markdown 에디터로 옵시디언의 파일들을 문제 없이 편집할 수 있게 됨**
- Link 형식 통일
	- Wikilinks(`![[]]`)와 Markdown(`[]()`) 방식 중 한 종류로 통일
	- 링크 경로를 상대경로로 통일
- Attachment 경로 통일
	- 현재 Vault의 Attachment 경로 설정에 맞춰 기존 파일들을 전부 자동으로 이동시킴

> [!Warning] 주의사항
> Auto Collect Attachments 옵션은 끄고 사용 권장. 켜면 Obsidian이 매우 느려지고 버그가 생김

### 1.3.3 Git (⭐⭐⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-git)
- Vault를 git으로 관리하는 경우, Obsidian 자체에서 repository를 관리하도록 해주는 플러그인
- 수동/자동 백업 옵션
### 1.3.4 Image Converter (⭐⭐⭐)
[플러그인 보기](obsidian://show-plugin?id=image-converter)
- 이미지 붙여넣을 때 자동으로 포맷 변환, 압축
	- Vault 용량 줄이는 데 효과적
- 이미 문서에 있는 이미지를 포맷 변환, 압축
### 1.3.5 Importer (⭐⭐⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-importer)
- 메모 앱, 웹사이트 등의 문서 임포트 지원
	- [Import from Apple Notes](https://help.obsidian.md/import/apple-notes)
	- [Import from Bear](https://help.obsidian.md/import/bear)
	- [Import from Evernote](https://help.obsidian.md/import/evernote)
	- [Import from Google Keep](https://help.obsidian.md/import/google-keep)
	- [Import from Microsoft OneNote](https://help.obsidian.md/import/onenote)
	- [Import from Notion](https://help.obsidian.md/import/notion)
	- [Import from Roam Research](https://help.obsidian.md/import/roam)
	- [Import from HTML files](https://help.obsidian.md/import/html)
	- [Import from Markdown files](https://help.obsidian.md/import/markdown)
- [Image Converter](#3.4%20Image%20Converter%20(⭐⭐⭐)), [Commander](#Commander)와 조합해서 불러온 뒤 자동으로 첨부된 이미지를 압축하는 스크립트 작성 가능해 보임
## 1.4 자동화 / 외부 툴
### 1.4.1 Advanced URI (⭐)
[플러그인 열기](obsidian://show-plugin?id=obsidian-advanced-uri)
- 외부 애플리케이션에서 옵시디언을 조작할 수 있게 하는 옵시디언의 URI의 확장 플러그인
- 옵시디언이 기본 제공하는 URI의 제한적인 기능에 추가로 더 복잡한 작업 가능
- [사용법 문서(한국어)](https://kaminik.tistory.com/entry/%EC%99%B8%EB%B6%80%EC%97%90%EC%84%9C-%EB%85%B8%ED%8A%B8%EB%A5%BC-%EC%A1%B0%EC%9E%91%ED%95%A0-%EC%88%98-%EC%9E%88%EB%8A%94-Advanced-URI-%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8)
- [공식 문서](https://publish.obsidian.md/advanced-uri-doc/Home)

### 1.4.2 Commander
WIP
### 1.4.3 DataView (⭐⭐)
[플러그인 열기](obsidian://show-plugin?id=dataview)
- 특정 태그가 달린 파일을 모아서 쿼리
	- 태그 = 테이블처럼 사용할 수 있음
	- 테이블, 리스트, 태스크 뷰 지원
#### 1.4.3.1 사용 예시
- 레시피 목록별 개별 문서가 존재하고, 문서들을 모아서 보여주는 예시
- 각 레시피 문서는 속성값을 가진 frontmatter와 `#recipes` 태그를 가짐
  ![|150](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인-20241106185512912.webp)![|170](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인-20241106185545098.webp)
- 레시피 목록을 보여주는 문서에는 `#recipes` 테이블에서 `category`와 `cook_time`을 불러오는 쿼리를 작성
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인-20241106185732054.webp)
- 쿼리 작성이 끝나면 `#recipes` 태그가 달린 모든 문서가 테이블로 정리되어 보여짐
  ![](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인-20241106185816078.webp)

### 1.4.4 Snippet Commands (⭐)
[플러그인 열기](obsidian://show-plugin?id=snippet-commands-obsidian)
- Options -> Appearance -> CSS Snippets 토글을 커맨드화시킴
#### 1.4.4.1 사용 예시
- 현재 Vault에는 4종류의 Snippet이 있음
  ![](/img/user/Obsidian/attachments/플러그인-20241106172641583.webp)
- `hide-folder-and-files` Snippet을 단축키로 토글하기 위해, Options -> Hotkeys에서 `Snippet Commands: Toggle hide-folder-and-files`에 단축키를 바인딩
  ![](/img/user/Obsidian/attachments/플러그인-20241106172731266.webp)
- 이제 옵션 창을 켜지 않고도 단축키를 누르면 `hide-folder-and-files` 스니펫을 토글할 수 있음
### 1.4.5 Pandoc (⭐)
[플러그인 보기](obsidian://show-plugin?id=obsidian-pandoc)
- Pandoc에서 지원하는 모든 형식으로 문서를 내보낼 수 있음
  ![|300](/img/user/Obsidian/플러그인 및 Snippet 정리/attachments/플러그인 정리-20241106195408209.webp)
> [!Warning] 주의사항
> 컴퓨터에 [Pandoc을 설치](https://pandoc.org/installing.html)해야 동작함
### 1.4.6 Pomodoro Timer
WIP
# 2 스니펫
## 2.1 Anuppuccin Theme Extended Colorschemes
[스니펫 보기](https://github.com/AnubisNekhet/AnuPpuccin/blob/main/snippets/extended-colorschemes.css)
Anuppuccin 테마의 확장 컬러
## 2.2 Image Dimmer
```CSS fold
/* Written by seunghun kim */
.theme-dark .markdown-preview-view img {
    opacity: 0.5;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-source-view img {
    opacity: 0.5;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-preview-view img:hover {
    opacity: 1;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-source-view img:hover {
    opacity: 1;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-preview-view .internal-embed.pdf-embed {
    opacity: 0.5;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-source-view .internal-embed.pdf-embed {
    opacity: 0.5;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-preview-view .internal-embed.pdf-embed:hover {
    opacity: 1;
    transition: opacity 0.3s ease-in-out;
}
  
.theme-dark .markdown-source-view .internal-embed.pdf-embed:hover {
    opacity: 1;
    transition: opacity 0.3s ease-in-out;
}
```

다크 모드에서 이미지 투명도를 조절해 어둡게 보이도록 하는 스니펫.
이미지에 마우스를 올리면 원본을 볼 수 있음.

## 2.3 테이블 세로 정렬
```CSS
table {
    --table-cell-vertical-alignment: middle;
}
.markdown-rendered tr {
    height: unset;
}
```

[Sheets Extended](#1.2.9%20Sheets%20Extended)의 셀 병합 기능을 이용할 때 같이 사용해야 하는 스니펫.
테이블 내용이 세로로 가운데 정렬되도록 함.

## 2.4 파일 및 폴더 가리기
```CSS
/* Hiding the Attachment folder */
div[data-path$="attachments"],
div[data-path$="attachments"] + div.nav-folder-children {
  display: none;
}
  
/* Hiding all 'sortspec.md' files */
div[data-path$="sortspec.md"] {
  display: none;
}
```

파일 목록에서 특정 파일이나 폴더를 보이지 않게 가리는 스니펫.
`data-path$=`은 최하위 폴더까지 재귀적으로 적용되고, `data-path=`은 특정 경로에만 적용됨.

위 코드는 `attachment`라는 이름의 모든 폴더와 `sortspec.md`라는 이름의 모든 파일을 가림.

[Snippet Commands](#1.4.4%20Snippet%20Commands%20(⭐)) 플러그인과 조합해서 숨김 파일들의 visibility를 단축키로 토글할 수 있음.