# 외부 API를 연동한 뉴스 뷰어 만들기 (비동기 작업)

노션 링크:<br>
https://seokjuna.notion.site/14-API-1-d0a6aad78d6340a3a79647c2302ce80d<br>
https://seokjuna.notion.site/14-API-2-adf4838f41c54c658bb581568aa42194<br>

React:
- UI: NewsItem, NewsList, Categories<br>
- yarn: axios, styled-components, react-router-dom<br>
- function: useState, useEffect<br>
<br>
<img width="976" alt="뉴스 홈" src="https://user-images.githubusercontent.com/102382351/194831197-05f225b1-0eb8-4ede-990b-76fe6285de8f.png">
- newsapi API를 통해 뉴스를 불러오기<br/>
- NewsItem 컴포넌트에서 각 뉴스 정보를 보여주고, NewsList 컴포넌트에서 API를 요청. 뉴스 데이터가 들어 있는 배열을 컴포넌트 배열로 변환하여 렌더링<br/>
<br/>
<img width="973" alt="뉴스 스포츠탭" src="https://user-images.githubusercontent.com/102382351/194831337-9b9ccde4-62e2-45df-86f6-b112d999a8af.png">
- NewsList 컴포넌트에서 props로 받아온 category에 따라 카테고리를 지정하여 API를 요청<br/>
- 리액트 라우터를 적용하여 카테고리 선택에 따라 경로를 달리함



