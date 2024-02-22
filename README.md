# ⛰️ [산 넘어 산 SSuk 개발일지](https://www.notion.so/growing-ssuk/SSUK-H.github.io)

진정한 개발자가 되기 위한 험난한 여정을 블로그를 통해 기록하기 위한 공간입니다.
<br />
<br />

### 🤔 왜 깃헙 블로그인가?

현재 Notion으로 일정관리와 공부기록은 하고 있지만 오직 글을 쓰는 데에만 주의를 기울일 수 있는 환경이 필요했습니다.

깃헙 블로그(Github blog)의 정식 명칭은 깃헙 페이지(Github page)라고 합니다.
깃헙 블로그를 활용하면 포트폴리오를 위한 블로그 관리와 업로드를 깃헙에서 할 수 있기 때문에 코드 리뷰와 공유 그리고 커밋을 관리하는 일 등을 한 번에 해결 수 있고, 마크업 언어로 만든 파일을 그대로 깃헙에 올리기만 하면 자동으로 변환이 되어 업로드되기 때문에 블로글 운영과 관리가 효율적일 것 같았습니다. 마지막으로 타 블로그들과 달리 내가 원하는 대로 커스터마이징할 수 있다는 점이 가장 좋아 선택하게 되었습니다.

### 👩‍💻 깃헙 블로그 만들기

#### 시작하기

1. 레포지토리 클론하기: `git clone [레포지토리URL]`
2. Jekyll 및 의존성 설치하기: `bundle install`
3. 로컬 서버에서 실행하기: `bundle exec jekyll serve`

#### 블로그 구성 및 커스터마이징

1. \_config.yml 설정: 사이트의 기본 설정을 담고 있는 \_config.yml 파일을 수정하여 블로그의 제목, 설명, URL 등을 설정합니다.

2. 테마 커스터마이징: Flexton 테마의 HTML, CSS, JavaScript 파일을 수정하여 블로그의 디자인과 기능을 사용자화합니다.

3. 포스트 작성: \_posts 디렉토리에 Markdown 형식으로 블로그 포스트를 작성하며, 파일 이름은 YYYY-MM-DD-title.md 형식을 따릅니다.

#### 블로그 배포

1. GitHub에 푸시

2. GitHub Pages 설정: 활성화가 필요한 경우 레포지토리의 GitHub Pages를 활성화하고, 소스를 설정합니다. 사이트가 자동으로 빌드되고 배포되며, 배포 과정과 상태는 GitHub Actions의 워크플로우 로그에서 확인할 수 있습니다.

이 깃헙 블로그는 [jekyll](https://jekyllrb-ko.github.io/)과 [Flexton](https://github.com/artemsheludko/flexton) 테마를 사용하여 만들어졌습니다.
