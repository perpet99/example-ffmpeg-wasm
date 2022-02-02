# [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm "github ffmpegwasm link") React Example

wasm 기반 ffmpeg를 사용하는 인터페이스 패키지 ffmpeg.wasm react 사용 예제를 정리하기 위한 코드

https://ddochea.tistory.com/147 에 관련 패키지 소개 및 설명글을 작성했습니다.

## 2022.02.02 추가사항
과거에는 브라우저에서 조건없이 허용되었던 SharedArrayBuffer 사용에 대해 보안상 이유로 차단되었습니다.
아래 헤더정보가 있어야 사용가능하며, 웹 배포시 배포한 서비스에 아래 헤더정보를 추가해야합니다.

```
"Cross-Origin-Opener-Policy": "same-origin"
"Cross-Origin-Embedder-Policy": "require-corp"
```
