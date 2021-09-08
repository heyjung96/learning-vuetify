|       Component        | API                       | 설명                                                                                                                                                            |
| :--------------------: | :------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    **Application**     | v-app                     | _필수 컴포넌트_ </br> vuetify에서 v-app 구성요소와 v-navigation-drawer, v-app-bar, v-footer 등과 같은 구성 요소들을 **v-main** 주변에 적절한 크기로 조절해줌.   |
|                        | v-main                    | .                                                                                                                                                               |
|       **Cards**        | v-card                    | .                                                                                                                                                               |
|                        | v-card-title              | 카드 제목의 기본 글꼴 크기와 패딩을 줌. typography 클래스로 덮어쓰기 가능.                                                                                      |
|                        | v-card-subtitle           | 카드 제목의 기본 글꼴 크기와 패딩을 줌. typography 클래스로 덮어쓰기 가능.                                                                                      |
|                        | v-card-text               | 텍스트를 입력하는 곳이다. 카드내에 적절한padding값을 줌..                                                                                                       |
|                        | v-card-actions            | v-btn이나 v-menu 같은 타드를 비치하는데 사용되는 컨테이너. </br> 버튼에 특수 여백을 적용하여 다른 카드 콘텐츠 영역과 적절하게 정렬됨                            |
|       **Alerts**       | v-alert                   | 성공, 정보, 경고 및 오류의 4가지 변형으로 제공됨.                                                                                                               |
|                        |                           |                                                                                                                                                                 |
|     Aspect ratios      | v-responsive              | 섹션을 특정 종횡비로 고정할 수 있음.                                                                                                                            |
|        Avatars         | v-avatar                  | 프로필 사진을 표시하는데 사용됨. 이미지, 아이콘 및 텍스트의 테두리 반경을 동적으로 조정하고 추가할 수 있음.                                                     |
|         Badges         | v-badage                  | 정보에 강조 표시함.                                                                                                                                             |
|         Banner         | v-banner                  | 컴포넌트안에 정보 표시                                                                                                                                          |
|        App bars        | v-app-bar                 | 사이트 탐색바                                                                                                                                                   |
|                        | v-app-bar-nav-icon        | 네비게이션만을 위한 아이콘 버튼. 접었다 폈다 할 수 있게 해줌.                                                                                                   |
|                        | v-app-bar-title           | 화면에서 잘리지 않고 계속 보일 수 있는 옵션을 갖고있는 부분.                                                                                                    |
|        Toolbars        | v-toolbar                 |                                                                                                                                                                 |
|                        | v-toolbar-items           |                                                                                                                                                                 |
|                        | v-toolbar-title           |                                                                                                                                                                 |
|                        | v-app-bar-title           | 화면에서 잘리지 않고 계속 보일 수 있는 옵션을 갖고있는 부분.                                                                                                    |
|       Systembars       | v-system-bar              | 안드로이드 시스템 표시줄처럼 사용 가능.                                                                                                                         |
|   Bottom navigation    | v-bottom-navigation       | 일종의 사이드바. 주로 모바일에서 사용됨.                                                                                                                        |
|     Bottom sheets      | v-bottom-sheet            | 아래에서부터 슬라이드로 올라옴.                                                                                                                                 |
|      Breadcrumbs       | v-breadcrumbs             | 페이지 안에서 네비게이션 도우미                                                                                                                                 |
|                        | v-breadcrumbs-item        | 이동 경로를 나타내는 부분                                                                                                                                       |
|      **Buttons**       | v-btn                     | 아래에서부터 슬라이드로 올라옴.                                                                                                                                 |
|                        | v-btn-toggle              | 그룹으로 여러개가 있을 때, 그룹 중 하나만 선택되게 하는 기능.                                                                                                   |
|        Buttons:        | v-btn                     |                                                                                                                                                                 |
| Floating Action Button | v-sppd-dial               | 단축 다이얼 구성. 버튼 안에 이동 가능한 버튼들을 포함시키고 있음.                                                                                               |
|       Calendars        | v-calendar                |                                                                                                                                                                 |
|                        | v-calendar-daily          |                                                                                                                                                                 |
|                        | v-calendar-monthly        |                                                                                                                                                                 |
|                        | v-calendar-weekly         |                                                                                                                                                                 |
|       Carousels        | v-carousels               | 슬라이드 형식으로 넘어가는 컴포넌트.                                                                                                                            |
|                        | v-carousels-item          | 넘어가는 정보들 ex.이미지..                                                                                                                                     |
|         Chips          | v-chip                    | 작은 정보들를 전달하는데 사용.                                                                                                                                  |
|        Dialogs         | v-dialog                  | 사용자에게 특정 작업에 대해 알리고 중요한 정보를 결정 요구하거나 어러 작업을 포함 할 수 있음.                                                                   |
|        Dividers        | v-divider                 | 구분선                                                                                                                                                          |
|   Expansions panels    | v-expansion-panels        | 아코디언같이 정보를 접을때 사용.                                                                                                                                |
|                        | v-expansion-panel         | 패널 한 줄                                                                                                                                                      |
|                        | v-expansion-panel-header  | 패널 하나의 제목                                                                                                                                                |
|                        | v-expansion-panel-content | 패널 내용                                                                                                                                                       |
|      **Footers**       | v-footer                  | 사이트내의 모든 페이지에서 엑세스되어야함. 일반 정보를 표시하는데 사용                                                                                          |
|                        |                           |                                                                                                                                                                 |
| Form inputs & controls |                           |
|     Autocompletes      | v-autocomplete            | 자동완성 기능                                                                                                                                                   |
|       Checkboxes       | v-checkbox                | 체크박스                                                                                                                                                        |
|                        | v-simple-checkbox         | 테이블용 간단한 체크박스                                                                                                                                        |
|       Comboboxes       | v-combobox                | 검색으로 항목이 가능한 셀렉박스 st.                                                                                                                             |
|      File inputs       | v-file-input              |                                                                                                                                                                 |
|         Forms          | v-form                    | 유효성 검사를 쉽게 추가 할 수 있다는 장점이 있다.                                                                                                               |
|         Inputs         | v-input                   | 사용자 지정 입력을 받기 위해 사용합니다.                                                                                                                        |
|    Overflow Buttons    | v-overflow-btn            | 사용자가 목록에서 항목을 선택할 수 있는 기능을 제공하는 데 사용됩니다                                                                                           |
|     Radio Buttons      | v-radio-group             | 선택 가능한 목록들을 집합화                                                                                                                                     |
|                        | v-radio                   | 선택 가능한 목록(단수)                                                                                                                                          |
|     Range Sliders      | v-range-slider            | 범위를 설정하는 부분을 시각화.                                                                                                                                  |
|        Sliders         | v-slider                  | 단일값을 설정하는 부분을 시각화                                                                                                                                 |
|        Selects         | v-select                  | 옵션화한 목록에서 사용자가 선택해 정보를 수집.                                                                                                                  |
|        Swiches         | v-switch                  | 체크박스 on/off와 비슷한 기능이지만 미학적으로 다름. 고유한 값중에서 선택할 수 있음.                                                                            |
|       Textareas        | v-textarea                | 장문의 텍스트 데이터를 수집하기 위함.                                                                                                                           |
|      Text fileds       | v-text-field              | 비교적 짧은 텍스트를 수집하기 위함.                                                                                                                             |
|                        |                           |                                                                                                                                                                 |
|         Hover          | v-hover                   | 하나의 자식만 갖을 수 있음. 마우스를 위에 대변 이벤트 트리거 가능. </br> v-hover을 제대로 사용하려면 v-slot="{ hover }" 를 포함하거나 prop을 true로 설정해야함. |
|         Icoons         | v-icon                    | Material Design Icons를 이용해 아이콘 사용 가능                                                                                                                 |
|         Images         | v-img                     | 이미지를 더 풍부하게 사용 가능하도록 서포트해줌.                                                                                                                |
|          Lazy          | v-lazy                    | 가시성을 기반으로 동적으로 로드하는데 사용. ex) 스크롤 다운하면서 위치에 도달하면 컴포넌트 등장                                                                 |
|         Lists          | v-list                    | 정보를 표시하는데 사용됨.                                                                                                                                       |
|                        | v-list-group              |                                                                                                                                                                 |
|                        | v-list-item               |                                                                                                                                                                 |
|                        | v-list-item-action        |                                                                                                                                                                 |
|                        | v-list-item-action-text   |                                                                                                                                                                 |
|                        | v-list-item-avatar        |                                                                                                                                                                 |
|                        | v-list-item-content       |                                                                                                                                                                 |
|                        | v-list-item-group         |                                                                                                                                                                 |
|                        | v-list-item-icon          |                                                                                                                                                                 |
|                        | v-list-item-title         |                                                                                                                                                                 |
|                        | v-list-item-subtitle      |                                                                                                                                                                 |
|         Menus          | v-menu                    |                                                                                                                                                                 |
|   Navigation drawers   | v-navigation-drawer       | 주로 응용 프로그램의 페이지에 대한 링크를 보관하는 데 사용되기 때문에 vue-router와 함께 사용됨. </br> v-app의 바로 포함이 되어있음.                             |
|        Overlays        | v-overlay                 | 특정 요소나 일부를 강조하기 위해 사용. ex) 알렛이 뜨면서 밑 바탕은 어두워지는 효과                                                                              |
|       Pagination       | v-Aotocompletes           |                                                                                                                                                                 |
|        Parallax        | v-Aotocompletes           |                                                                                                                                                                 |
|        Pickers         | v-Aotocompletes           |                                                                                                                                                                 |
|        Progress        | v-Aotocompletes           |                                                                                                                                                                 |
|         Sheets         | v-Aotocompletes           |                                                                                                                                                                 |
|    Skeleton loaders    | v-Aotocompletes           |                                                                                                                                                                 |
|       Snackbars        | v-Aotocompletes           |                                                                                                                                                                 |
|       Sparklines       | v-Aotocompletes           |                                                                                                                                                                 |
|        Steppers        | v-Aotocompletes           |                                                                                                                                                                 |
|       Subheaders       | v-Aotocompletes           |                                                                                                                                                                 |
|       **Table**        |                           |                                                                                                                                                                 |
|    Data interators     | v-Aotocompletes           |                                                                                                                                                                 |
|     Simple tables      | v-Aotocompletes           |                                                                                                                                                                 |
|      Data tables       | v-Aotocompletes           |                                                                                                                                                                 |
|          Tabs          | v-Aotocompletes           |                                                                                                                                                                 |
|       Timelines        | v-Aotocompletes           |                                                                                                                                                                 |
|        Tooltips        | v-Aotocompletes           |                                                                                                                                                                 |
|    Virtual scroller    | v-Aotocompletes           |                                                                                                                                                                 |

## 자주사용하는 Props

| Props | 설명                                                                                                                                                          |
| :---: | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| dense | 조밀한 소품은 경고의 높이를 줄여 심플하고 컴팩트한 스타일을 연출합니다.</br> 테두리 소품과 결합하면 스타일과 일관성을 유지하기 위해 테두리 두께가 줄어듭니다. |
| tile  | border-radius를 제거합니다. .                                                                                                                                 |

| | Grouping || Grouping 2 || Not Grouped |
| First Header | Second Header | Third Header | Forth Header | Fifth Header | Sixth Header |
| -------------| :-----------: | -------------: | :----------: | :----------: | ---------------|
| Tall Cell | _Long Cell_ || _Long Long Cell_ |||
| ^^ | **Bold** | 1. first item | _Italic_ | 3. third item | + first point |\
| ^^ | | 1. second item | | 1. forth item | + second point |
| New section | More | Data | ... ------|||
| And more | With an escaped \| || "Try 'quotes' in quotes " |||
[Compicated table]
