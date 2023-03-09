### [과제] 숙련주차 과제 답안 작성

- +기타<br/>
  todo.js: initial state에서 불필요한 괄호와 배열 이름 제거, isDone값을 false, true로 분배하여 Working과 Done에서 전부 보이게 함, <br/>configStore.js: 불필요한 콤마 제거 const rootReducer = combineReducers({ todos });

- 추가하기 버튼을 클릭해도 추가한 아이템이 화면에 표시되지 않음.<br/>
  Form.jsx: action creator addTodo가 동작하도록 코드 작성(기존에 있던 코드를 독해하기 어려워서 본인 수준에 맞게 바꿈)<br/>
  todo.js: ADD_TODO의 return문 변경

<br/>

- 추가하기 버튼 클릭 후 기존에 존재하던 아이템들이 사라짐.<br/>
  todo.js: ADD_TODO의 return문 변경

  <br/>

- 삭제 기능이 동작하지 않음.<br/>
  todo.js -> Reducer에 DELETE_TODO switch문 추가

  <br/>

- 상세 페이지에 진입 하였을 때 데이터가 업데이트 되지 않음.<br/>
  todo.js: return문의 todo를 todos로 변경

  <br/>

- 완료된 카드의 상세 페이지에 진입 하였을 때 올바른 데이터를 불러오지 못함.<br/>
  Detail.jsx: useEffect, dispatch를 사용하여 id값을 payload로 넘겨줌<br/>
  +'이전으로' 클릭시 오류:해결X

  <br/>

- 취소 버튼 클릭시 기능이 작동하지 않음.<br/>
  list.jsx: todo.id와 todo.isDone도 payload로 함께 넘겨줘야 함.

  <br/>

- 배포
