window_coordinates + scrolling

tomato색 상자를 누르면 getBoundingClientRect()함수가 실행되고 콘솔에 DOMRect가 출력됨.

getBoundingClientRect()함수는 요소의 사이즈,위치에 관련된 다양한 정보를 얻을 수 있음.

Client x, y : 사용자가 보는 페이지에 상관없이 브라우저 window창에서 x와 y가 얼마나 떨어져 있는지가 전달됨.

page의 x, y : 문서의 시작점부터 x, y가 전달됨.



------------------스크롤------------------

window.scrollBy({top:100, left:0, behavior:"smooth"}); : 100만큼 스크롤 이동

window.scrollTo({top:100, left:0, behavior:"smooth"}); : 100으로 스크롤 이동

special.scrollIntoView({behavior:"smooth"}); : special의 위치로스크롤 이동
