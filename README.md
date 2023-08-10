# Netflix Clone

HTML/CSS

<h3>🔗 css 속성 설정 시 기본 설정</h3>

: 브라우저가 자동으로 padding, margin을 부여하기 때문에 미리 값을 조정한다.

- {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  }

ul {
list-style: none;
}

a {
text-decoration: none;
}

🔗 `background` 속성

1. background-color: 배경 색상

2. background-image: 배경 이미지 지정
   background-image: url('경로');

3. background-repeat: 배경 이미지가 주어진 영역에 꽉 차지 않는 경우 이미지를 반복할 방식을 결정
   `repeat`: 가로 세로 영역 모든 방향
   `repeat-x`: 가로 방향
   `repeat-y`: 세로 방향
   `no-repeat`: 반복 안함

4. background-position: 이미지 위치
   배경 이미지가 반복된다면 위치를 지정할 필요는 없으므로 `no-repeat`과 자주 사용

5. background-size: 배경 이미지의 크기
   기본값은 auto(배경 이미지의 실제 크기)
   `cover`: 배경 이미지가 잘리더라도 주어진 영역을 완전히 덮을 수 있도록 이미지 크기를 맞춘다.
   `contain`: 빈 공간이 생기더라도 배경 이미지가 주어진 영역 안에 모두 들어올 수 있도록 이미지 크기를 맞춘다.

6. background-attachment: 스크롤 시 배경 이미지가 주어진 영역과 함께 따라갈지 그대로 있을지 결정

`scroll`: 주어진 영역과 함께 스크롤된다.
`fixed`: 영역이 스크롤되더라도 고정된다.

🔗 background 단축 속성

주어진 속성을 함께 사용할 수 있다.

예) background: url('../img/background.jpg') no-repeat center center/cover;
