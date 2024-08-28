## Hi there 👋

## GitHub Snake Animation 🐍

이 리포지토리에는 GitHub 기여도 그래프를 기반으로 뱀 애니메이션을 생성하는 GitHub Actions 워크플로가 포함되어 있습니다. 뱀이 기여도 그래프의 점들을 따라 움직이며, 기여도를 시각적으로 표현합니다!

이 애니메이션은 매일 자정에 자동으로 업데이트되며, 리포지토리에 푸시나 PR이 있을 때도 새로 생성됩니다. 아래의 애니메이션은 다크 모드와 라이트 모드에 맞게 표시됩니다.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dist/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="dist/github-snake.svg" />
  <img alt="github-snake" src="dist/github-snake.svg" />
</picture>

## 설정 방법 🛠️

1. **리포지토리 설정**:
   - `.github/workflows/snake.yml` 파일에서 `github_user_name` 필드를 본인의 GitHub 사용자 이름으로 설정하세요.
   - 애니메이션 파일의 스타일이나 색상을 변경하고 싶다면, `outputs` 필드를 수정하세요.

2. **워크플로 실행**:
   - 이 리포지토리는 매일 자정과 `main` 브랜치에 푸시 또는 PR이 있을 때마다 자동으로 뱀 애니메이션을 생성합니다.

3. **애니메이션 표시**:
   - 위에서 제공된 코드를 사용하여 GitHub 프로필이나 README에 애니메이션을 표시할 수 있습니다.

## 기여하기 🌟

이 프로젝트에 기여하고 싶다면, 자유롭게 PR을 제출하거나 이슈를 생성해 주세요.

## 라이선스 📄

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](./LICENSE) 파일을 참고하세요.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
