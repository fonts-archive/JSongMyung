# J송명

[배포처 바로가기](https://jikjisoft.com/freefont/5f9661e088228e152ce089f4)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `JSongMyung`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/JSongMyung.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/JSongMyung.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'JSongMyung';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/JSongMyung-Regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/JSongMyung-Regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/JSongMyung-Regular.otf') format('opentype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/subsets/JSongMyung-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/JSongMyung/subsets/JSongMyung-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "JSongMyung", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
J송명은 오픈 라이선스 폰트(OFL)입니다.
OFL은 글꼴 및 관련 소프트웨어를 위해 특별히 설계된 자유로운 무료 소스 라이선스입니다.
OFL은 협력 방식으로 글꼴 및 관련 소프트웨어의 전세계 개발, 공유 및 개선을 위한 법적 프레임 워크 및 인프라를 제공합니다.
글꼴 작성자는 사용, 번들링, 수정 및 재배포를 허용하는 공통 라이센스에 따라 작업을 릴리스 할 수 있습니다.
공유 가치를 장려하고 특정 컴퓨팅 플랫폼이나 환경에 국한되지 않으며 다른 조직이나 개인이 사용할 수 있습니다.
```
