### css - border-image
상단, 하단 이미지는 고정이고 가운데 영역에 동일한 테두리가 있는 경우 사용하기 좋은 방법  
정확히는 `border-image-repeat: stretch;` 속성으로 늘어난다

경우에 따라 background-repeat을 repeat-y로 해서 늘려도 됨

border 영역에만 이미지가 있는 경우는 border-image를 이용하고, 배경에도 이미지가 있으면 background 쓰면 될 듯
