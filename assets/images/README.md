# 🖼️ 챗봇 프로필 이미지 폴더

이 폴더에 챗봇의 프로필 이미지를 추가하세요.

## 권장 사항

- **파일명**: `bot-avatar.png` 또는 `bot-avatar.jpg`
- **크기**: 200x200 픽셀 이상 권장
- **형식**: PNG, JPG, WEBP 지원
- **비율**: 1:1 정사각형 권장 (원형으로 표시됨)

## 이미지 적용 방법

`index.html` 파일에서 아래 코드를 찾아 수정하세요:

```html
<!-- 기존 코드 (이모지 아바타) -->
<div class="bot-avatar" id="botAvatar">
    🤖
</div>

<!-- 이미지로 변경 -->
<div class="bot-avatar" id="botAvatar">
    <img src="assets/images/bot-avatar.png" alt="AI 상담사">
</div>
```

## 무료 아바타 리소스

- [Unsplash](https://unsplash.com) - 무료 고품질 이미지
- [Avatar Generator](https://getavataaars.com) - 아바타 생성기
- [Multiavatar](https://multiavatar.com) - 다양한 아바타 스타일


