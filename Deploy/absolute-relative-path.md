## 절대경로, 상대경로

#### 절대경로

**나의 위치**와는 무관하게 쓸 때

`<a href = "http://localhost/indenx.php">` = `<a href ="/index.php"> `

**/** => 최상위 디렉토리

----

#### 상대경로

**나의 위치**와 연관지어 쓸 때

`<a href ="../index.php"> ` 

- ../ => 현재 위치의 부모 디렉토리로
- ./ => 현재 디렉토리
- / => root (절대경로이기도 상대경로이기도, 서버주소가 바뀌면 가리키는 위치가 바뀌니까) 
- 아예 / 안붙이고 바로 디렉토리 명