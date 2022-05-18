# Setting
## 드래그, 우클릭, 복사, 이미지 다운로드 ~~불펌하는 방법~~
- Setting -> Debugger -> Disable JavaScript
- [예시1](https://sunstar2.tistory.com/)
- [예시2](https://blankspace-dev.tistory.com/378)

# Elements
## force element state
- `:hover` `:active` 등 상태 유지해서 개발자도구에서 css 테스트하고 싶을 때

# Network
## Replay XHR
- 마우스 우클릭 -> Replay XHR
- (최신 버전에서는) XHR 요청을 선택하고 -> R키

# Console
## Preserve log upon navigation
- 화면을 새로고침해도 콘솔이 리셋되지 않게하는 옵션
- clear 시에는 리셋됨
## warning 제외하고 보기
![image](https://user-images.githubusercontent.com/82023300/168713345-64d38d51-7b34-4250-963f-76fb6d3eb371.png)
## 다른 패널에서 console 패널 함께 보기
- `esc`로 on/off
## 에디터처럼 임의로 HTML 수정하기
```
document.body.contentEditable = true
document.designMode=’on’
```
# Source
## 개발자 도구에서 무한루프에 들어갔을 때 빠져나오는 방법
- Sources > 일시정지 > 계속하기 버튼을 꾹 누르면 > 정지 버튼
