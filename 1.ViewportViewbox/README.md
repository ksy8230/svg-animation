## viewport, viewbox

- viewport는 svg가 보이는 영역이다.
- viewbox를 통해 좌표와 가로, 세로의 비율을 결정한다.
- viewbox 속성값은 순서대로 min-x, min-y, width, height를 의미한다.
- viewport < viewbox 인 경우 svg는 영역에 비해 축소되어 보이게 된다.
- viewport > viewbox 인 경우 svg는 영역에 비해 확대되어 보이게 된다.
- viewport의 width, height를 100%로 변경하면 가변하는 viewport에 맞춰서 viewbox 비율대로 svg 크기가 변한다.
