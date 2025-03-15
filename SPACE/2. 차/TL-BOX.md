
### 트렁크 뒤쪽 왼쪽 화이트 박스

```dataview
table 종류, 위치, 상세위치, 갯수, 설명
from "/"
where contains(위치, [[TL-BOX]])
sort 위치 ASC
```