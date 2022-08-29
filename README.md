# WAI-ARIA
구조, 기준, 의미, 구분, 방법 등의 일반적인 구분방법

## Aria Roles
### tag roles
일반 텍스트를 이미지 처리한 경우 : (예시) `<img role="text">`

버튼이 블록요소를 감쌀 수 없는 경우 : (예시) `<li role="button">`

<table>
  <colgroup>
    <col style="width:15%">
    <col style="width:20%">
    <col style="width:20%">
    <col style="width:auto">
  </colgroup>
  <thead>
    <tr>
      <th scope="col">분류</th>
      <th scope="col">구분</th>
      <th scope="col">이름</th>
      <th scope="col">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="8">양식</td>
      <td>입력서식</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/form" target="_blank" title="새창열림" class="g-link-basic">role="form"</a></td>
      <td>동일한 HTML요소 &lt;form&gt;</td>
    </tr>
    <tr>
      <td>자유형식 입력텍스트</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/textbox" target="_blank" title="새창열림" class="g-link-basic">role="textbox"</a></td>
      <td>동일한 HTML요소 &lt;input type="text"&gt;, &lt;textarea&gt;, aria-multiline="" 속성으로 줄바꿈 처리 적용</td>
    </tr>
    <tr>
      <td>일반형식 입력텍스트</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/input" target="_blank" title="새창열림" class="g-link-basic">role="input"</a></td>
      <td>동일한 HTML요소 &lt;input type="text"&gt;</td>
    </tr>
    <tr>
      <td>라디오</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/radio" target="_blank" title="새창열림" class="g-link-basic">role="radio"</a></td>
      <td>동일한 HTML요소 &lt;input type="radio"&gt;, "라디오그룹"으로 묶어주어야 함.</td>
    </tr>
    <tr>
      <td>체크박스</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/checkbox" target="_blank" title="새창열림" class="g-link-basic">role="checkbox"</a></td>
      <td>동일한 HTML요소 &lt;input type="checkbox"&gt;</td>
    </tr>
    <tr>
      <td>선택목록</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/combobox" target="_blank" title="새창열림" class="g-link-basic">role="combobox"</a></td>
      <td>동일한 HTML요소 &lt;select&gt;</td>
    </tr>
    <tr>
      <td>선택옵션</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/option" target="_blank" title="새창열림" class="g-link-basic">role="option"</a></td>
      <td>동일한 HTML요소 &lt;option&gt;</td>
    </tr>
    <tr>
      <td>슬라이더</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles-2/slider" target="_blank" title="새창열림" class="g-link-basic">role="slider"</a></td>
      <td>동일한 HTML요소 &lt;input type="range"&gt;</td>
    </tr>
    <tr>
      <td rowspan="6">표</td>
      <td>표</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/table" target="_blank" title="새창열림" class="g-link-basic">role="table"</a></td>
      <td>동일한 HTML요소 &lt;table&gt;</td>
    </tr>
    <tr>
      <td>행그룹</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/rowgroup" target="_blank" title="새창열림" class="g-link-basic">role="rowgroup"</a></td>
      <td>동일한 HTML요소 &lt;tbody&gt;, &lt;thead&gt;</td>
    </tr>
    <tr>
      <td>행</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/row" target="_blank" title="새창열림" class="g-link-basic">role="row"</a></td>
      <td>동일한 HTML요소 &lt;tr&gt;</td>
    </tr>
    <tr>
      <td>제목(열)</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/columnheader" target="_blank" title="새창열림" class="g-link-basic">role="columnheader"</a></td>
      <td>동일한 HTML요소 &lt;th scope="col"&gt;, 그리드인 경우 aria-colindex=""와 같이 사용됨</td>
    </tr>
    <tr>
      <td>제목(행)</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/rowheader" target="_blank" title="새창열림" class="g-link-basic">role="rowheader"</a></td>
      <td>동일한 HTML요소 &lt;th scope="row"&gt;, 그리드인 경우 aria-colindex=""와 같이 사용됨</td>
    </tr>
    <tr>
      <td>내용</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/cell" target="_blank" title="새창열림" class="g-link-basic">role="cell"</a></td>
      <td>동일한 HTML요소 &lt;td&gt;</td>
    </tr>
    <tr>
      <td rowspan="5">HTML5</td>
      <td>네비게이션</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/navigation" target="_blank" title="새창열림" class="g-link-basic">role="navigation"</a></td>
      <td>동일한 HTML요소 &lt;nav&gt;</td>
    </tr>
    <tr>
      <td>일반 섹션</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/section" target="_blank" title="새창열림" class="g-link-basic">role="section"</a></td>
      <td>동일한 HTML요소 &lt;section&gt;</td>
    </tr>
    <tr>
      <td>Article</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/article" target="_blank" title="새창열림" class="g-link-basic">role="article"</a></td>
      <td>동일한 HTML요소 &lt;article&gt;</td>
    </tr>
    <tr>
      <td>메인컨텐츠</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/main" target="_blank" title="새창열림" class="g-link-basic">role="main"</a></td>
      <td>동일한 HTML요소 &lt;main&gt;</td>
    </tr>
    <tr>
      <td>그래픽문서</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/figure" target="_blank" title="새창열림" class="g-link-basic">role="figure"</a></td>
      <td>동일한 HTML요소 &lt;figure&gt;</td>
    </tr>
    <tr>
      <td rowspan="4">기본요소</td>
      <td>버튼</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/button" target="_blank" title="새창열림" class="g-link-basic">role="button"</a></td>
      <td>동일한 HTML요소 &lt;button&gt;</td>
    </tr>
    <tr>
      <td>이미지</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/img" target="_blank" title="새창열림" class="g-link-basic">role="img"</a></td>
      <td>동일한 HTML요소 &lt;img&gt;</td>
    </tr>
    <tr>
      <td>링크</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/link" target="_blank" title="새창열림" class="g-link-basic">role="link"</a></td>
      <td>동일한 HTML요소 &lt;a&gt;</td>
    </tr>
    <tr>
      <td>선</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles-2/separator" target="_blank" title="새창열림" class="g-link-basic">role="separator"</a></td>
      <td>동일한 HTML요소 &lt;hr&gt;</td>
    </tr>
    <tr>
      <td rowspan="3">목록, 정의요소</td>
      <td>목록의 그룹</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/list" target="_blank" title="새창열림" class="g-link-basic">role="list"</a></td>
      <td>동일한 HTML요소 &lt;ul&gt;, &lt;ol&gt;</td>
    </tr>
    <tr>
      <td>목록의 단일항목</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/listitem" target="_blank" title="새창열림" class="g-link-basic">role="listitem"</a></td>
      <td>동일한 HTML요소 &lt;li&gt;, &lt;dt&gt;</td>
    </tr>
    <tr>
      <td>데이터리스트</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/listbox" target="_blank" title="새창열림" class="g-link-basic">role="listbox"</a></td>
      <td>동일한 HTML요소 &lt;datalist&gt; (사파리 미지원 태그)</td>
    </tr>
    <tr>
      <td rowspan="10">비슷한 HTML요소</td>
      <td>주요 제목</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/heading" target="_blank" title="새창열림" class="g-link-basic">role="heading"</a></td>
      <td>비슷한 HTML요소 &lt;h1&gt;~&lt;h6&gt;</td>
    </tr>
    <tr>
      <td>중요한 섹션</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/region" target="_blank" title="새창열림" class="g-link-basic">role="region"</a></td>
      <td>비슷한 HTML요소 &lt;section&gt;, 중요한 내용을 포함하는 인식 가능한 섹션</td>
    </tr>
    <tr>
      <td>그리드</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/grid" target="_blank" title="새창열림" class="g-link-basic">role="grid"</a></td>
      <td>비슷한 HTML요소 &lt;table&gt;, aria-colcount="" 와 같이 사용됨</td>
    </tr>
    <tr>
      <td>그리드 내용</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/gridcell" target="_blank" title="새창열림" class="g-link-basic">role="gridcell"</a></td>
      <td>비슷한 HTML요소 &lt;td&gt;, 그리드인 경우 aria-colindex=""와 같이 사용됨</td>
    </tr>
    <tr>
      <td>정의 제목</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/term" target="_blank" title="새창열림" class="g-link-basic">role="term"</a></td>
      <td>비슷한 HTML요소 &lt;dt&gt;</td>
    </tr>
    <tr>
      <td>정의 내용</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/definition" target="_blank" title="새창열림" class="g-link-basic">role="definition"</a></td>
      <td>비슷한 HTML요소 &lt;dd&gt;</td>
    </tr>
    <tr>
      <td>슬라이더</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/range" target="_blank" title="새창열림" class="g-link-basic">role="range"</a></td>
      <td>비슷한 HTML요소 &lt;input type="range"&gt;</td>
    </tr>
    <tr>
      <td>스핀버튼</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles-2/spinbutton" target="_blank" title="새창열림" class="g-link-basic">role="spinbutton"</a></td>
      <td>비슷한 HTML요소 &lt;input type="number"&gt;</td>
    </tr>
    <tr>
      <td>Contentinfo</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/contentinfo" target="_blank" title="새창열림" class="g-link-basic">role="contentinfo"</a></td>
      <td>비슷한 HTML요소 &lt;footer&gt;</td>
    </tr>
    <tr>
      <td>보완적인 랜드 마크</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/complementary" target="_blank" title="새창열림" class="g-link-basic">role="complementary"</a></td>
      <td>비슷한 HTML요소 &lt;aside&gt;</td>
    </tr>
    <tr>
      <td rowspan="4">기타</td>
      <td>라디오 그룹</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/radiogroup" target="_blank" title="새창열림" class="g-link-basic">role="radiogroup"</a></td>
      <td>"라디오그룹" 으로 역할정의</td>
    </tr>
    <tr>
      <td>섹션 제목</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/sectionhead" target="_blank" title="새창열림" class="g-link-basic">role="sectionhead"</a></td>
      <td>추상적인 역할</td>
    </tr>
    <tr>
      <td>선택 목록</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/select" target="_blank" title="새창열림" class="g-link-basic">role="select"</a></td>
      <td>추상적인 역할</td>
    </tr>
    <tr>
      <td>텍스트</td>
      <td>role="text"</td>
      <td>이미지를 텍스트로만 읽도록 사용<br>마크업에 의해 분리된 텍스트를 한번에 읽도록 사용</td>
    </tr>
  </tbody>
</table>

### wiget roles
<table>
  <colgroup>
    <col style="width:15%">
    <col style="width:20%">
    <col style="width:20%">
    <col style="width:auto">
  </colgroup>
  <thead>
    <tr>
      <th scope="col">분류</th>
      <th scope="col">구분</th>
      <th scope="col">이름</th>
      <th scope="col">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="12">기능</td>
      <td>탭 메뉴그룹</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/tablist" target="_blank" title="새창열림" class="g-link-basic">role="tablist"</a></td>
      <td>ul 그룹 요소에 적용</td>
    </tr>
    <tr>
      <td>탭 메뉴목록</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/presentation" target="_blank" title="새창열림" class="g-link-basic">role="presentation"</a></td>
      <td>li 목록 요소에 적용 (시맨틱 마크업의 역할을 무효화 함)</td>
    </tr>
    <tr>
      <td>탭 메뉴링크</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/tab" target="_blank" title="새창열림" class="g-link-basic">role="tab"</a></td>
      <td>a 이벤트 요소에 적용</td>
    </tr>
    <tr>
      <td>탭 내용</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/tabpanel" target="_blank" title="새창열림" class="g-link-basic">role="tabpanel"</a></td>
      <td>div 컨텐츠 활성화 요소에 적용</td>
    </tr>
    <tr>
      <td>Dialog</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/dialog" target="_blank" title="새창열림" class="g-link-basic">role="dialog"</a></td>
      <td>대화 상자는 사용자가 정보를 입력하거나 응답하도록하는 데 가장 자주 사용되는 모달입니다.</td>
    </tr>
    <tr>
      <td>Tooltip</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/tooltip" target="_blank" title="새창열림" class="g-link-basic">role="tooltip"</a></td>
      <td>요소에 대한 설명을 표시하는 문맥 팝업</td>
    </tr>
    <tr>
      <td>트리목록</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/tree" target="_blank" title="새창열림" class="g-link-basic">role="tree"</a></td>
      <td>축소 및 확장 할 수있는 하위 수준 중첩 그룹을 포함 할 수있는 유형의 목록입니다.</td>
    </tr>
    <tr>
      <td>트리의 옵션 항목</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/treeitem" target="_blank" title="새창열림" class="g-link-basic">role="treeitem"</a></td>
      <td>트리 항목 요소의 하위 수준 그룹이 포함되어있는 경우 확장되거나 축소 될 수있는 트리 내의 요소입니다.</td>
    </tr>
    <tr>
      <td>트리 그리드</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/treegrid" target="_blank" title="새창열림" class="g-link-basic">role="treegrid"</a></td>
      <td>트리와 같은 방법으로 행을 확장 및 축소 할 수있는 그리드입니다.</td>
    </tr>
    <tr>
      <td>진행표시줄</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles-2/progressbar" target="_blank" title="새창열림" class="g-link-basic">role="progressbar"</a></td>
      <td>오랜 시간이 걸리는 작업의 진행 상태를 표시하는 요소입니다.</td>
    </tr>
    <tr>
      <td>스위치</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/switch" target="_blank" title="새창열림" class="g-link-basic">role="switch"</a></td>
      <td>체크 / 체크되지 않은 값과 반대로 on / off 값을 나타내는 체크 박스 유형</td>
    </tr>
    <tr>
      <td>Toolbar</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/toolbar" target="_blank" title="새창열림" class="g-link-basic">role="toolbar"</a></td>
      <td>컴팩트 한 시각적 형태로 표현 된 일반적으로 사용되는 기능 버튼 또는 컨트롤 모음.</td>
    </tr>
    <tr>
      <td rowspan="18">의미</td>
      <td>메뉴바</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/menubar" target="_blank" title="새창열림" class="g-link-basic">role="menubar"</a></td>
      <td>수평으로 제시되는 메뉴</td>
    </tr>
    <tr>
      <td>메뉴그룹</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/menu" target="_blank" title="새창열림" class="g-link-basic">role="menu"</a></td>
      <td>선택목록 제공</td>
    </tr>
    <tr>
      <td>메뉴목록</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/menuitem" target="_blank" title="새창열림" class="g-link-basic">role="menuitem"</a></td>
      <td>선택사항의 옵션으로만 사용되므로 선택된 상태는 적용하지 않음</td>
    </tr>
    <tr>
      <td>메뉴선택</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/menuitemradio" target="_blank" title="새창열림" class="g-link-basic">role="menuitemradio"</a></td>
      <td>하나만 선택 할 수 있는 메뉴목록, aria-checked와 함께 사용됨</td>
    </tr>
    <tr>
      <td>메뉴선택</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/menuitemcheckbox" target="_blank" title="새창열림" class="g-link-basic">role="menuitemcheckbox"</a></td>
      <td>여러개 선택 할 수 있는 메뉴목록, aria-checked와 함께 사용됨</td>
    </tr>
    <tr>
      <td>스크롤바</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/scrollbar" target="_blank" title="새창열림" class="g-link-basic">role="scrollbar"</a></td>
      <td>영역 내의 내용 스크롤을 제어하는 ​​그래픽 객체입니다.</td>
    </tr>
    <tr>
      <td>상태표시줄</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles-2/status" target="_blank" title="새창열림" class="g-link-basic">role="status"</a></td>
      <td>상태 역할은 경고에 대해 중요하지 않은 권고 정보를 사용자에게 제공하는 데 사용됩니다.<br>하지만 반드시 이것이 사용자에게 발표된다는 것을 의미하지는 않습니다.</td>
    </tr>
    <tr>
      <td>Timer</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/timer" target="_blank" title="새창열림" class="g-link-basic">role="timer"</a></td>
      <td>시작 지점에서부터의 경과 시간 또는 끝 지점까지 남은 시간을 나타내는 숫자 카운터가 포함 된 라이브 영역 유형입니다.</td>
    </tr>
    <tr>
      <td>Marquee</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/marquee" target="_blank" title="새창열림" class="g-link-basic">role="marquee"</a></td>
      <td>중요하지 않은 정보가 자주 변경되는 라이브 영역 유형입니다.</td>
    </tr>
    <tr>
      <td>검색</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/search" target="_blank" title="새창열림" class="g-link-basic">role="search"</a></td>
      <td>검색 기능</td>
    </tr>
    <tr>
      <td>검색상자</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/searchbox" target="_blank" title="새창열림" class="g-link-basic">role="searchbox"</a></td>
      <td>검색 기준을 지정하기위한 텍스트 상자 유형입니다.</td>
    </tr>
    <tr>
      <td>경고 메세지</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/alert" target="_blank" title="새창열림" class="g-link-basic">role="alert"</a></td>
      <td>사용자에게 경고하기 위해 메시지를 전달하는 데 사용됩니다. 해당 요소가 활성화 될 때 전달됨.</td>
    </tr>
    <tr>
      <td>경고 대화상자</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/alertdialog" target="_blank" title="새창열림" class="g-link-basic">role="alertdialog"</a></td>
      <td>경고 메시지가 들어있는 대화 상자 유형으로, 초기 포커스는 대화 상자의 요소로 이동함.</td>
    </tr>
    <tr>
      <td>배너</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/banner" target="_blank" title="새창열림" class="g-link-basic">role="banner"</a></td>
      <td>페이지 별 콘텐츠가 아닌 사이트 중심 콘텐츠가 대부분 포함 된 배너영역</td>
    </tr>
    <tr>
      <td>수학 표현식</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/math" target="_blank" title="새창열림" class="g-link-basic">role="math"</a></td>
      <td>수학 표현식을 나타내는 내용</td>
    </tr>
    <tr>
      <td>정적 목차</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/directory" target="_blank" title="새창열림" class="g-link-basic">role="directory"</a></td>
      <td>정적 목차와 같이 그룹 구성원에 대한 참조 목록입니다.</td>
    </tr>
    <tr>
      <td>기사목록</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/feed" target="_blank" title="새창열림" class="g-link-basic">role="feed"</a></td>
      <td>스크롤을 통해 기사의 목록에 추가되거나 제거 될 수있는 기사의 스크롤 가능한 목록</td>
    </tr>
    <tr>
      <td>문서</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/document" target="_blank" title="새창열림" class="g-link-basic">role="document"</a></td>
      <td>보조 기술 사용자가 읽기 모드로 탐색 할 수있는 콘텐츠가 포함 된 요소입니다.</td>
    </tr>
    <tr>
      <td rowspan="12">기타</td>
      <td>Landmark</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/landmark" target="_blank" title="새창열림" class="g-link-basic">role="landmark"</a></td>
      <td>저자가 지정한 특정 목적과 관련이 있고 사용자가 섹션을 쉽게 탐색하고 페이지 요약에 나열 할 수 있기를 원하는만큼 중요한 내용을 포함하는 인식 가능한 섹션</td>
    </tr>
    <tr>
      <td>명령</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/command" target="_blank" title="새창열림" class="g-link-basic">role="command"</a></td>
      <td>조치를 수행하지만 입력 데이터를 수신하지 않는 위젯 형태</td>
    </tr>
    <tr>
      <td>Composite</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/composite" target="_blank" title="새창열림" class="g-link-basic">role="composite"</a></td>
      <td>탐색 가능한 자손 또는 소유 된 자식요소를 포함 할 수있는 위젯</td>
    </tr>
    <tr>
      <td>Log</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/log" target="_blank" title="새창열림" class="g-link-basic">role="log"</a></td>
      <td>새 정보가 의미있는 순서로 추가되고 오래된 정보가 사라질 수있는 라이브 영역 유형입니다.</td>
    </tr>
    <tr>
      <td>Roletype</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/roletype" target="_blank" title="새창열림" class="g-link-basic">role="roletype"</a></td>
      <td><span class="g-txt-disabled">인스턴스를 이해하고 작동시키는 데 사용할 수있는 개념</span></td>
    </tr>
    <tr>
      <td>어플리케이션</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/application" target="_blank" title="새창열림" class="g-link-basic">role="application"</a></td>
      <td></td>
    </tr>
    <tr>
      <td>없음</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/none" target="_blank" title="새창열림" class="g-link-basic">role="none"</a></td>
      <td>내제된 원시적 역할을 매핑시키지 않음</td>
    </tr>
    <tr>
      <td>그룹</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/group" target="_blank" title="새창열림" class="g-link-basic">role="group"</a></td>
      <td>보조 기술에 의해 페이지 요약이나 목차에 포함되지 않는 사용자 인터페이스 개체 집합입니다.</td>
    </tr>
    <tr>
      <td>노트</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/note" target="_blank" title="새창열림" class="g-link-basic">role="note"</a></td>
      <td>내용이 소문자이거나 자원의 주요 내용을 보조하는 부분</td>
    </tr>
    <tr>
      <td>구조</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/structure" target="_blank" title="새창열림" class="g-link-basic">role="structure"</a></td>
      <td>문서 구조 요소. 구조적 역할 자체가 모두 접근성 API에 매핑되는 것은 아니지만 보조 기술에 대한 컨텐츠 적응을 지원하거나 위젯 역할을 만드는 데 사용됩니다.</td>
    </tr>
    <tr>
      <td>위젯</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/widget" target="_blank" title="새창열림" class="g-link-basic">role="widget"</a></td>
      <td>그래픽 사용자 인터페이스 (GUI)의 대화 형 구성 요소</td>
    </tr>
    <tr>
      <td>Window</td>
      <td><a href="http://www.a11yhelp.org/index.php/roles/window" target="_blank" title="새창열림" class="g-link-basic">role="window"</a></td>
      <td>브라우저 또는 응용 프로그램 창.</td>
    </tr>
  </tbody>
</table>

## Aria Properties
<table>
  <colgroup>
    <col style="width:15%">
    <col style="width:20%">
    <col style="width:20%">
    <col style="width:auto">
  </colgroup>
  <thead>
    <tr>
      <th scope="col">분류</th>
      <th scope="col">구분</th>
      <th scope="col">속성</th>
      <th scope="col">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="14">Global</td>
      <td>변경 알림</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-atomic" target="_blank" title="새창" class="g-link-basic">aria-atomic</a></td>
      <td>true 또는 false를 나타내는 값. 기본값은 False입니다.</td>
    </tr>
    <tr>
      <td>컨트롤</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-controls" target="_blank" title="새창" class="g-link-basic">aria-controls</a></td>
      <td>"idname" : 제어할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>서술 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-describedby" target="_blank" title="새창" class="g-link-basic">aria-describedby</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>상세 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-details" target="_blank" title="새창" class="g-link-basic">aria-details</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>읽기흐름 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-flowto" target="_blank" title="새창" class="g-link-basic">aria-flowto</a></td>
      <td>"idname" : 다중 참조할 요소의 ID 값을 읽어줄 순서대로 입력합니다.</td>
    </tr>
    <tr>
      <td>오류메시지 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-errormessage" target="_blank" title="새창" class="g-link-basic">aria-errormessage</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>메뉴 또는 대화 상자 존재여부</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-haspopup" target="_blank" title="새창" class="g-link-basic">aria-haspopup</a></td>
      <td>존재하는 경우 속성과 함께 "true" 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>단축키 설명</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-keyshortcuts" target="_blank" title="새창" class="g-link-basic">aria-keyshortcuts</a></td>
      <td>"alt+ArrowRight Delete alt+ctrl+m" : 구현된 단축키를 입력합니다. 다중입력 가능</td>
    </tr>
    <tr>
      <td>레이블</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-label" target="_blank" title="새창" class="g-link-basic">aria-label</a></td>
      <td>"대체정보" : 문자열 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>레이블 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-labelledby" target="_blank" title="새창" class="g-link-basic">aria-labelledby</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>소유</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-owns" target="_blank" title="새창" class="g-link-basic">aria-owns</a></td>
      <td>현재 개체의 직계 자식이 아닌 요소를 포함하여 자식 개체의 목록을 설정하거나 검색합니다. <br>
        "idname" : 참조할 요소의 ID 값을 입력합니다.
      </td>
    </tr>
    <tr>
      <td>업데이트 요소</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-live" target="_blank" title="새창" class="g-link-basic">aria-live</a></td>
      <td>"polite" : 현재 작업을 방해하지 않을 때만 사용자에게 업데이트를 알립니다. <br>
        "off" : 현재 해당 지역에 집중되어 있을 때만 사용자에게 업데이트를 알립니다.<br>
        "assertive" : 업데이트 즉시 사용자에게 알립니다.
      </td>
    </tr>
    <tr>
      <td>관련 설정</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-relevant" target="_blank" title="새창" class="g-link-basic">aria-relevant</a></td>
      <td>보조 기술로 어떤 유형의 변경이 관련되어 있으며 발표되어야하는지에 대한 힌트를 제공합니다.<br>
        "additions" : 요소 노드는 라이브 영역 내의 액세스 가능성 트리에 추가됩니다.<br>
        "additions text" : 값의 조합 인 "추가 텍스트"와 동일합니다.<br>
        "all" : 모든 값의 조합에 해당하는 "추가 제거 텍스트"<br>
        "removals" : 라이브 영역 내의 텍스트 내용, 대체 텍스트 또는 요소 노드는 액세스 가능성 트리에서 제거됩니다.<br>
        "text" : 텍스트 컨텐츠 또는 대체 텍스트가 액세스 라이브러리의 모든 하위 항목에 추가됩니다.
      </td>
    </tr>
    <tr>
      <td>역할설명</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-roledescription" target="_blank" title="새창" class="g-link-basic">aria-roledescription</a></td>
      <td>"attachment button" : 역할설명을 입력합니다.</td>
    </tr>
    <tr>
      <td rowspan="16">Widget</td>
      <td>자동 완성</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-autocomplete" target="_blank" title="새창" class="g-link-basic">aria-autocomplete</a></td>
      <td>"none" : 가장 최근에 사용한 5개의 검색어를 나열하여 제안 된 값을 표시<br>
        "inline" : 텍스트 입력 내에서 값 완성 예측을 표시하는 인라인 모델<br>
        "list" : a에서 가능한 값 모음을 표시하는 목록 모델<br>
        "both" : inline, list 입력이 두 가지 모델을 동시에 제공하는 경우
      </td>
    </tr>
    <tr>
      <td>오류메시지 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-errormessage" target="_blank" title="새창" class="g-link-basic">aria-errormessage</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>메뉴 또는 대화 상자 존재여부</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-haspopup" target="_blank" title="새창" class="g-link-basic">aria-haspopup</a></td>
      <td>존재하는 경우 속성과 함께 "true" 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>계층 수준 (h1~h6)</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-level" target="_blank" title="새창" class="g-link-basic">aria-level</a></td>
      <td>"6" : 목차와 같은 단계를 입력합니다. (role="heading" 제공하는 경우 사용됨)</td>
    </tr>
    <tr>
      <td>대화상자 확인</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-modal" target="_blank" title="새창" class="g-link-basic">aria-modal</a></td>
      <td>모달인 경우 속성과 함께 "true" 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>멀티라인 (textarea)</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-multiline" target="_blank" title="새창" class="g-link-basic">aria-multiline</a></td>
      <td>여러줄인 경우 속성과 함께 "true" 값을 입력합니다. (role="textbox" 제공하는 경우 사용됨)</td>
    </tr>
    <tr>
      <td>다중선택 (multiple)</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-multiselectable" target="_blank" title="새창" class="g-link-basic">aria-multiselectable</a></td>
      <td>"true" 다중 선택, "false" 하나만 선택 (role="combobox" 제공하는 경우 사용됨)</td>
    </tr>
    <tr>
      <td>방향</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-orientation" target="_blank" title="새창" class="g-link-basic">aria-orientation</a></td>
      <td>true 또는 false를 나타내는 값. 기본값은 False입니다.</td>
    </tr>
    <tr>
      <td>Plaeholder</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-placeholder" target="_blank" title="새창" class="g-link-basic">aria-placeholder</a></td>
      <td>placeholder="" 속성과 마찬가지로 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>읽기전용</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-readonly" target="_blank" title="새창" class="g-link-basic">aria-readonly</a></td>
      <td>읽기전용인 경우 속성과 함께 "true" 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>필수입력</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-required" target="_blank" title="새창" class="g-link-basic">aria-required</a></td>
      <td>필수입력인 경우 속성과 함께 "true" 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>정렬</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-sort" target="_blank" title="새창" class="g-link-basic">aria-sort</a></td>
      <td>표 또는 그리드의 항목의 정렬 여부를 나타냅니다.<br>
        "ascending" : 오름차순으로 정렬<br>
        "descending" : 내림차순으로 정렬<br>
        "none" : 정렬하지 않음<br>
        "other" : 다른 정렬방식이 적용됨
      </td>
    </tr>
    <tr>
      <td>최대값</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-valuemax" target="_blank" title="새창" class="g-link-basic">aria-valuemax</a></td>
      <td>"100" : 알려진 최대 값이 있는 경우 최대값을 입력합니다.</td>
    </tr>
    <tr>
      <td>최소값</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-valuemin" target="_blank" title="새창" class="g-link-basic">aria-valuemin</a></td>
      <td>"-100" : 알려진 최소 값이 있는 경우 최소값을 입력합니다.</td>
    </tr>
    <tr>
      <td>현재값</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-valuenow" target="_blank" title="새창" class="g-link-basic">aria-valuenow</a></td>
      <td>"0" : 현재값을 입력합니다.</td>
    </tr>
    <tr>
      <td>텍스트값</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-valuetext" target="_blank" title="새창" class="g-link-basic">aria-valuetext</a></td>
      <td>"Sunday" : aria-valuenow를 읽을 수 있는 텍스트 대안을 정의합니다.</td>
    </tr>
    <tr>
      <td rowspan="3">Live Region</td>
      <td>변경 알림</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-atomic" target="_blank" title="새창" class="g-link-basic">aria-atomic</a></td>
      <td>true 또는 false를 나타내는 값. 기본값은 False입니다.</td>
    </tr>
    <tr>
      <td>업데이트 요소</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-live" target="_blank" title="새창" class="g-link-basic">aria-live</a></td>
      <td>"polite" : 현재 작업을 방해하지 않을 때만 사용자에게 업데이트를 알립니다. <br>
        "off" : 현재 해당 지역에 집중되어 있을 때만 사용자에게 업데이트를 알립니다.<br>
        "assertive" : 업데이트 즉시 사용자에게 알립니다.
      </td>
    </tr>
    <tr>
      <td>관련 설정</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-relevant" target="_blank" title="새창" class="g-link-basic">aria-relevant</a></td>
      <td>보조 기술로 어떤 유형의 변경이 관련되어 있으며 발표되어야하는지에 대한 힌트를 제공합니다.<br>
        "additions" : 요소 노드는 라이브 영역 내의 액세스 가능성 트리에 추가됩니다.<br>
        "additions text" : 값의 조합 인 "추가 텍스트"와 동일합니다.<br>
        "all" : 모든 값의 조합에 해당하는 "추가 제거 텍스트"<br>
        "removals" : 라이브 영역 내의 텍스트 내용, 대체 텍스트 또는 요소 노드는 액세스 가능성 트리에서 제거됩니다.<br>
        "text" : 텍스트 컨텐츠 또는 대체 텍스트가 액세스 라이브러리의 모든 하위 항목에 추가됩니다.
      </td>
    </tr>
    <tr>
      <td rowspan="16">Relationship</td>
      <td>현재 활성화 된 자손을 식별</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-activedescendant" target="_blank" title="새창" class="g-link-basic">aria-activedescendant</a></td>
      <td>"idname" : 활성화된 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>총 열 개수</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-colcount" target="_blank" title="새창" class="g-link-basic">aria-colcount</a></td>
      <td>"16" : 총 합계를 입력합니다.</td>
    </tr>
    <tr>
      <td>열 위치</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-colindex" target="_blank" title="새창">aria-colindex</a></td>
      <td>"2" : 열 위치를 입력합니다.</td>
    </tr>
    <tr>
      <td>열 병합</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-colspan" target="_blank" title="새창" class="g-link-basic">aria-colspan</a></td>
      <td>"2" : 병합된 열 수를 입력합니다.</td>
    </tr>
    <tr>
      <td>컨트롤</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-controls" target="_blank" title="새창" class="g-link-basic">aria-controls</a></td>
      <td>"idname" : 제어할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>서술 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-describedby" target="_blank" title="새창" class="g-link-basic">aria-describedby</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>상세 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-details" target="_blank" title="새창" class="g-link-basic">aria-details</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>읽기흐름 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-flowto" target="_blank" title="새창" class="g-link-basic">aria-flowto</a></td>
      <td>"idname" : 다중 참조할 요소의 ID 값을 읽어줄 순서대로 입력합니다.</td>
    </tr>
    <tr>
      <td>오류메시지 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-errormessage" target="_blank" title="새창" class="g-link-basic">aria-errormessage</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>레이블 참조</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-labelledby" target="_blank" title="새창" class="g-link-basic">aria-labelledby</a></td>
      <td>"idname" : 참조할 요소의 ID 값을 입력합니다.</td>
    </tr>
    <tr>
      <td>소유</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-owns" target="_blank" title="새창" class="g-link-basic">aria-owns</a></td>
      <td>현재 개체의 직계 자식이 아닌 요소를 포함하여 자식 개체의 목록을 설정하거나 검색합니다. <br>
        "idname" : 참조할 요소의 ID 값을 입력합니다.
      </td>
    </tr>
    <tr>
      <td>번호 및 위치</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-posinset" target="_blank" title="새창">aria-posinset</a></td>
      <td>현재 listitems 또는 treeitem의 집합에서 요소의 번호 또는 위치를 정의<br>
        "5" : 순서에 맞는 값을 입력합니다. (순서 목록은 ol li 구조로 사용)
      </td>
    </tr>
    <tr>
      <td>총 행 수</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-rowcount" target="_blank" title="새창" class="g-link-basic">aria-rowcount</a></td>
      <td>"5" : 총 행 수를 입력합니다.</td>
    </tr>
    <tr>
      <td>행 번호 및 위치</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-rowindex" target="_blank" title="새창" class="g-link-basic">aria-rowindex</a></td>
      <td>"5" : 행 번호 및 위치를 입력합니다.</td>
    </tr>
    <tr>
      <td>행 병합</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-rowspan" target="_blank" title="새창" class="g-link-basic">aria-rowspan</a></td>
      <td>"2" : 행을 병합한 수를 입력합니다.</td>
    </tr>
    <tr>
      <td>총 항목 수</td>
      <td><a href="http://www.a11yhelp.org/index.php/properties/aria-setsize" target="_blank" title="새창" class="g-link-basic">aria-setsize</a></td>
      <td>"10" : listitems또는 treeitem의 전체 항목의 수를 입력합니다.</td>
    </tr>
  </tbody>
</table>

## Aria States
<table>
  <colgroup>
    <col style="width:15%">
    <col style="width:20%">
    <col style="width:20%">
    <col style="width:auto">
  </colgroup>
  <thead>
    <tr>
      <th scope="col">분류</th>
      <th scope="col">구분</th>
      <th scope="col">속성</th>
      <th scope="col">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="8">Widget </td>
      <td>양식 선택됨</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-checked" target="_blank" title="새창" class="g-link-basic">aria-checked</a></td>
      <td>role="checkbox", role="radio" 를 사용한 경우에 쓰여짐</td>
    </tr>
    <tr>
      <td>현재항목</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-current" target="_blank" title="새창" class="g-link-basic">aria-current</a></td>
      <td>"page" : 현재 페이지<br>
        "step" : 현재 단계<br>
        "location" : 현재 위치<br>
        "date" : 현재 날짜<br>
        "time" : 현재 시간<br>
        "true" : 현재 항목<br>
        "false" : 형재 항목을 나타내지 않음
      </td>
    </tr>
    <tr>
      <td>비활성</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-disabled" target="_blank" title="새창" class="g-link-basic">aria-disabled</a></td>
      <td>"true" 포커스 가능하나 변경불가상태 "false" 요소의 사용 가능</td>
    </tr>
    <tr>
      <td>확장/축소</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-expanded" target="_blank" title="새창" class="g-link-basic">aria-expanded</a></td>
      <td>"true" 확장됨 "false" 축소됨</td>
    </tr>
    <tr>
      <td>숨김</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-hidden" target="_blank" title="새창" class="g-link-basic">aria-hidden</a></td>
      <td>"true" 접근성 API에 감춰집니다. "false" 접근성 API에 노출됩니다.</td>
    </tr>
    <tr>
      <td>무효화</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-invalid" target="_blank" title="새창" class="g-link-basic">aria-invalid</a></td>
      <td>"grammar" : 문법 오류인 경우<br>
        "false" : 오류가 없는 경우<br>
        "spelling" : 맞춤법 오류인 경우<br>
        "true" : 유효성 검사 오류인 경우
      </td>
    </tr>
    <tr>
      <td>누른상태</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-pressed" target="_blank" title="새창" class="g-link-basic">aria-pressed</a></td>
      <td>"false" : 요소가 눌려지지만 현재 눌려지지 않습니다.<br>
        "mixed" : 혼합모드 값을 나타냅니다.<br>
        "true" : 눌릷니다.<br>
        "undefined" : 눌려지지 않습니다.
      </td>
    </tr>
    <tr>
      <td>위젯 선택됨</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-selected" target="_blank" title="새창" class="g-link-basic">aria-selected</a></td>
      <td>"true" 선택됩니다. "false" 선택되지 않았습니다.</td>
    </tr>
    <tr>
      <td>Live Region</td>
      <td>업데이트중</td>
      <td><a href="http://www.a11yhelp.org/index.php/states/aria-busy" target="_blank" title="새창" class="g-link-basic">aria-busy</a></td>
      <td>"true" 요소가 업데이트 중입니다. "false" 요소의 예상 업데이트가 없습니다.</td>
    </tr>
  </tbody>
</table>
