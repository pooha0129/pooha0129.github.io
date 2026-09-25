# 탑등반물 캐릭터챗 이미지

GitHub Pages 공개 기본 URL: `https://pooha0129.github.io/`

이미지는 아래 폴더에 넣습니다. 경로와 대소문자를 정확히 지킵니다.

| 폴더 | 용도 | 예시 |
| --- | --- | --- |
| `MAP` | 장소·층 배경 | `MAP/1.webp` |
| `CHAR` | 인물·표정 | `CHAR/serin_smile.webp` |
| `MON` | 몬스터 | `MON/karg.webp` |
| `CG` | 사건·연출 | `CG/gate_open.webp` |

파일 ID는 영문 소문자·숫자·밑줄을 쓰고 확장자를 `.webp`로 통일합니다. URL을 브라우저에서 열었을 때 이미지 자체가 보여야 합니다. GitHub의 `blob/` 주소는 캐챗 이미지 주소로 쓰지 않습니다.

## 캐챗 프롬프트용 템플릿

```text
기본 URL: https://pooha0129.github.io/
장소: MAP/{장소ID}.webp
인물: CHAR/{인물ID}_{표정ID}.webp
몬스터: MON/{몬스터ID}.webp
이벤트: CG/{이벤트ID}.webp

이미지 출력: ![이미지 설명](기본 URL과 파일 경로를 합친 완성된 URL)
실제로 업로드하고 공개 URL을 확인한 파일 ID만 사용한다.
없는 조합을 추측해 만들지 않는다.
```

`MAP/1.webp`는 연결 테스트용 그림이며 실제 세계관 장면에는 사용하지 않습니다.

기존 `today-promise` 플래너 저장소와 주소는 그대로 유지합니다.
