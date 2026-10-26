# 엔지니어랩 소방설비기사 — GitHub Pages 업로드 안내

- 홈페이지 주소: https://fire-engineer-course.github.io/
- Organization: `fire-engineer-course`
- Repository: `fire-engineer-course.github.io`
- Visibility: **Public**
- Branch: `main`
- Folder: `/(root)`
- Pages Source: `Deploy from a branch`

## 처음 배포하는 방법

1. GitHub에서 `fire-engineer-course` Organization이 실제로 생성 가능하고 본인 계정에 생성·관리 권한이 있는지 확인합니다. 해당 Organization이 없다면 먼저 만듭니다.
2. Organization 아래에 이름이 정확히 `fire-engineer-course.github.io`인 **Public** 저장소를 생성합니다.
3. 제공된 ZIP 파일의 **압축을 풉니다.**
4. 압축을 해제하면 나오는 `index.html`, `assets` 폴더, `favicon.png`, `robots.txt`, `sitemap.xml`, `.nojekyll`, `README.md`를 **저장소 최상위(root)** 에 업로드합니다. `fire-engineer-course-site` 등의 폴더를 통째로 한 단계 더 넣지 마세요.
5. 업로드를 `main` 브랜치에 커밋합니다. `main`이 아니라면 기본 브랜치를 `main`으로 맞춥니다.
6. 저장소의 **Settings → Pages → Build and deployment** 로 이동합니다.
7. Source에서 **Deploy from a branch**, Branch에서 **main**, Folder에서 **/(root)** 를 선택하고 **Save** 합니다.
8. 배포가 반영된 후 `https://fire-engineer-course.github.io/` 에 접속해 페이지가 열리고 CSS·이미지가 제대로 표시되는지 확인합니다. 압축 해제 후에는 `index.html` 파일을 더블클릭해도 CSS와 이미지가 정상 표시됩니다.
9. 상단 **쿠폰 혜택** 버튼, **랜딩 이미지 전체**, 본문의 **시크릿코드 프로모션 링크**를 클릭해 다음 주소가 새 탭에서 열리는지 확인합니다. `https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288`
10. 내용을 수정하려면 파일을 수정하고 동일한 저장소 최상위 경로에 다시 업로드·커밋합니다. 기존 파일을 교체하면 자동으로 새 버전이 배포됩니다.

## 파일 구조

```text
index.html
favicon.png
robots.txt
sitemap.xml
.nojekyll
README.md
assets/
  css/style.css
  images/landing.webp      (첨부 원본: 936 × 8416 픽셀, 크롭/다운스케일 없음)
  images/thumbnail.webp    (1:1, 1254 × 1254 픽셀)
```

## SEO 안내

- `index.html`에 페이지 title, description, canonical, Open Graph, Twitter Card, WebSite/WebPage JSON-LD를 포함했습니다.
- `robots.txt`와 `sitemap.xml`은 `https://fire-engineer-course.github.io/`을 기준으로 설정했습니다.
- 배포 뒤 검색엔진 웹마스터 도구에서 사이트 소유확인 및 사이트맵을 등록할 수 있습니다. 검색 결과 노출과 반영 시점은 보장되지 않습니다.
- 쿠폰과 판매 중인 강좌는 변동될 수 있으므로 공식 엔지니어랩 안내에서 최종 확인해야 합니다.

## 연결 주소

- 랜딩 이미지 URL: `https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288`
- 고정 헤더 CTA URL: `https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288`
- 본문 강의 안내 링크: `https://engineerlab-guide.netlify.app/fire-protection/`
- 시크릿코드 e7288 섹션 링크: `https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288`

**주의:** 제공된 랜딩 이미지에 소방설비기사 외 다른 자격증 과정 홍보와 프로모션 안내가 포함되어 있습니다. 해당 이미지의 문구가 모든 소방설비기사 강좌에 그대로 적용된다고 해석해서는 안 됩니다. 랜딩 이미지·헤더 CTA는 사용자가 지정한 엔지니어랩 프로모션 페이지로 연결됩니다. 원본 이미지는 임의로 수정하지 않았습니다.

## ZIP 압축 해제 후 미리보기

- `index.html`과 `assets` 폴더를 **같은 상위 폴더** 안에 둔 채 `index.html`을 더블클릭하세요.
- `./assets/css/style.css` 및 `./assets/images/landing.webp` 상대경로를 사용하므로 인터넷 없이 파일로 열어도 레이아웃과 이미지가 표시됩니다.
- 링크 클릭 시 외부 웹사이트로 이동하려면 인터넷 연결이 필요하며, 검색엔진용 canonical/OG 주소는 실제 GitHub Pages 배포 주소를 유지합니다.
